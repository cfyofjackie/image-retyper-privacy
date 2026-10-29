# AGENTS.md

## 这个仓库是做什么的

Image Retyper（Chrome 扩展「图片另存为」）的**公开隐私政策网站**，由 GitHub Pages 从 `main` 分支根目录直接发布：
<https://cfyofjackie.github.io/image-retyper-privacy/>

扩展本体在私有仓库 `cfyofjackie/image-retyper`，**不要**在这里放代码、链接私有仓库的 issue，或任何密钥。
结构沿用 `cfyofjackie/zancunhe-privacy`（暂存盒）：一个产品一个仓库，`README.md` + `index.html`，中英双语同页。

## 文件

- `index.html` —— 线上页面（纯静态 HTML，内联 CSS，无构建步骤，手机可读，支持深色模式）。
- `README.md` —— 同一份政策的 Markdown 版本。
- 政策原文来源：私有仓库里的 `store/PRIVACY.md`。三处内容必须保持一致。

## 怎么改

1. 改政策时同时改 `index.html` 和 `README.md`（中英两段都要改），并更新顶部「生效日期 / Effective date」。
2. 联系方式只用本仓库的 issues：<https://github.com/cfyofjackie/image-retyper-privacy/issues>。不要写个人邮箱或电话。
3. 本地预览：`python3 -m http.server` 后打开 `http://localhost:8000/`。

## 新产品怎么加

新产品沿用同样的模式：新建公开仓库 `cfyofjackie/<产品>-privacy`，复制本仓库的 `index.html` / `README.md` / `AGENTS.md` 改内容，然后开启 Pages（main 分支、根目录）：

```bash
gh api -X POST repos/cfyofjackie/<产品>-privacy/pages -f 'source[branch]=main' -f 'source[path]=/'
```

## 发布

- 改动**直接提交并推送到 `main`**，Pages 会在一两分钟内自动重新发布，不需要 PR。
- 禁止强推、禁止改写历史；不要配置自定义域名 / DNS。
