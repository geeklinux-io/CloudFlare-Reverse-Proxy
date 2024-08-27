# cf-page-func-proxy

Use Cloudflare Pages Functions as a reverse proxy with custom domain support.

## Getting Start

1.下载或是Fork本仓库

2.修改`_worker.js`中的`url.hostname`为你需要反代的网址



3.打开Cloudflare Dashboard，进入Worker 和 Pages管理页面，选择创建项目，如果在第一步中选择的是fork本仓库，可以使用Pages从GitHUB部署，或者手动下载worker.js修改并上传到Cloudflare中，您需要修改_worker.js中的 `url.hostname="your—proxy-domain";` 为你要反代的地址
