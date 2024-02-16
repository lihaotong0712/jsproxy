# Jsproxy

An online proxy based on ServiceWorker and CloudFlare Workers

## 部署

1. 修改 [www/conf.js](www/conf.js) 和 [cf-worker/index.js](cf-worker/index.js)
2. 发布 `www` 目录 到 `Github Pages` 或 `Cloudflare Pages`
3. 部署 [cf-worker/index.js](cf-worker/index.js) 到 `Cloudflare Workers`

[Document](doc/README.md)

Forked from :
[EtherDream/jsproxy](https://github.com/EtherDream/jsproxy)
[EtherDream/jsproxy-broswer](https://github.com/EtherDream/jsproxy-browser)