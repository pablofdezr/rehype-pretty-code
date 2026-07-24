---
"rehype-pretty-code": patch
---

fix: mirror the `--shiki-*` theme variables onto `<code>` in multi-theme configurations, so the documented `code[data-theme*=' ']` selector can apply the theme background without relying on inheritance from `<pre>` (#222)
