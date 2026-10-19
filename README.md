# Jasper

Jasper 设计师作品集的 GitHub Pages 上线版本。

入口可直接打开，无需 GitHub 或 ChatGPT 登录。网页与视频以 AES-256-GCM 加密保存，访问者在浏览器中输入数字密码后解密。密码不写入公开源码、不存入浏览器持久存储；点击「锁定」即可关闭内容。

入口：`index.html`。加密内容：`content.*.enc` 与 `media.*.enc`。使用 HTTPS 和支持 Web Crypto 的现代浏览器。

此仓库不包含未加密的网页或视频。原始文件保留在私有源码仓库中。
