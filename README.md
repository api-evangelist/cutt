# cutt

cutt (cutt.com) is a Chinese technology company surfaced from the published portfolio of Qiming Venture Partners. As of the 2026-07-20 enrichment pass it has **no reachable public web or developer presence** — the apex does not complete an HTTPS connection and `www.cutt.com` returns 404 for every probed path.

The one surviving subdomain, `zhiyue.cutt.com`, 301-redirects to `api.zhiyueapp.cn`, a live but undocumented JSON API host behind an APISIX 3.4.1 gateway. The `zhiyueapp.cn` domain is registered to 北京简网生活圈科技有限公司 (Beijing Jianwang Life Circle Technology Co., Ltd.), the apparent operating entity.

No OpenAPI, SDK, portal, changelog, status page, or `/.well-known/` document was found. This repo records probed infrastructure evidence only.

- Website: https://cutt.com (unreachable)
- Backed by: qiming
- Artifacts: `security/cutt-domain-security.yml`, `well-known/cutt-well-known.yml`
