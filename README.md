# Image Retyper · 隐私政策 / Privacy Policy

**简体中文** ｜ [English](#english)

在线版本 / Live page: <https://cfyofjackie.github.io/image-retyper-privacy/>

---

## 中文

生效日期：2026-10-29

Image Retyper 是一个 Chrome 扩展，用于把你在网页右键菜单中选中的图片转换为 PNG、JPG 或 WebP 并下载。**我们不收集、不上传、不分享你的任何数据。**

### 本机处理的数据

你主动选择图片后，扩展会读取该图片及其来源 URL，以完成格式转换、文件名生成和下载。图片字节与 URL 仅在浏览器中处理，不发送给 Image Retyper 的开发者或其服务器，不用于分析、广告、画像或追踪。

跨站转换时，浏览器会向你选中的图片原站请求图片。请求可能按 Chrome 的 Cookie 规则携带适用的登录 Cookie；扩展不读取、记录或保存 Cookie。该请求是完成你指定的图片转换所必需的，不会发送到无关第三方。

“每次询问保存位置”偏好（一个开关）保存在 Chrome 扩展存储（`chrome.storage.sync`）中；若你开启了 Chrome 同步，这个开关会由 Chrome 在你的设备间同步，开发者无法读取。下载文件由 Chrome 下载功能写入你选择或默认的本地位置。

### 网站访问权限

处理同源、`data:` 或 `blob:` 图片时，使用你刚刚点击菜单所授权的当前标签页能力。跨站图片需要时，Chrome 会请求你允许访问图片来源网站；拒绝后扩展尝试页面可读取的转换方式，失败则停止。扩展不申请所有网站权限。

### 数据共享与保留

Image Retyper 不运营接收图片或浏览记录的服务器，也不把这些数据转交给任何第三方。不出售、不转移用户数据；不将数据用于与本扩展单一用途无关的目的；不用于确定信用度或放贷。下载文件与本地设置由你和 Chrome 管理，你可在 Chrome 设置或下载目录中自行删除；卸载扩展会移除它保存的设置。

### 儿童、追踪与变化

扩展不面向儿童，不收集账户、联系方式、支付信息或其他个人资料；不包含广告、分析或追踪代码。若未来功能或数据处理方式改变，将先更新扩展和本页顶部的日期，并按适用要求告知用户。

### 联系我们

如有隐私相关问题，请在 GitHub Issues 提问：
<https://github.com/cfyofjackie/image-retyper-privacy/issues>

---

<a id="english"></a>

## English

Effective date: 2026-10-29

Image Retyper is a Chrome extension that converts an image you pick from a webpage's context menu to PNG, JPG, or WebP and downloads it. **We do not collect, upload, or share any of your data.**

### Data handled on your device

After you select an image, the extension reads that image and its source URL to convert it, create a filename, and download the result. Image bytes and the URL are processed in the browser. They are not sent to the Image Retyper developer or any server, and are not used for analytics, advertising, profiling, or tracking.

For a cross-site image, the browser requests the image from the site you selected it on. Chrome may include an applicable login cookie according to its cookie rules. The extension does not read, record, or store cookies. This request is necessary for the conversion you asked for and is not sent to any unrelated third party.

The “ask where to save” preference (a single on/off value) is kept in Chrome extension storage (`chrome.storage.sync`); if Chrome Sync is on, Chrome syncs this value across your devices. The developer cannot access it. Chrome writes downloaded files to the location you choose or your default download folder.

### Site access

Same-origin, `data:`, and `blob:` images use the current-tab access granted by your menu click. A cross-site image may require Chrome to ask for access to that image's host. If you deny it, the extension tries a page-readable conversion and stops if that fails. The extension does not request access to all websites.

### Sharing and retention

Image Retyper does not operate a server that receives images or browsing history and does not share this data with any third party. We never sell or transfer user data; we never use it for purposes unrelated to the extension's single purpose; we never use it to determine creditworthiness or for lending. Settings and downloads are managed by you and Chrome; you can delete them in Chrome settings or your download folder, and uninstalling the extension removes its settings.

### Children, tracking, and changes

The extension is not directed at children and does not collect accounts, contact details, payment information, or other personal data. It contains no advertising, analytics, or tracking code. If features or data handling change, we will update the extension and the date at the top of this page, and notify users as required.

### Contact

For privacy questions, please open a GitHub issue:
<https://github.com/cfyofjackie/image-retyper-privacy/issues>
