# Serenido tools in the MCP Registry

Registry entries for [Serenido's data tools](https://apify.com/serenido), so AI apps that support MCP (Claude, ChatGPT,
Cursor, VS Code and others) can find and use them. Each tool runs on Apify and is reached through Apify's MCP server;
you sign in with your own Apify account.

| Registry name | Tool |
|---|---|
| io.github.serenido/aliexpress-product-details | [AliExpress Product Details](https://apify.com/serenido/aliexpress-product-details) |
| io.github.serenido/aliexpress-search | [AliExpress Search](https://apify.com/serenido/aliexpress-search-reliable) |
| io.github.serenido/aliexpress-dropshipping | [AliExpress Dropshipping](https://apify.com/serenido/aliexpress-dropshipping) |
| io.github.serenido/google-trends | [Google Trends](https://apify.com/serenido/google-trends-reliable) |
| io.github.serenido/coles-woolworths-aldi | [Australian Supermarket Prices](https://apify.com/serenido/au-supermarket-prices) |
| io.github.serenido/bilibili | [Bilibili](https://apify.com/serenido/bilibili-scraper) |
| io.github.serenido/weibo | [Weibo](https://apify.com/serenido/weibo-scraper) |
| io.github.serenido/weibo-hot-search | [Weibo Hot Search](https://apify.com/serenido/weibo-hot-search) |
| io.github.serenido/football-xg | [Football xG](https://apify.com/serenido/football-xg-scraper) |
| io.github.serenido/wechat-official-account | [WeChat Official Account](https://apify.com/serenido/wechat-official-account-scraper) |

Add one to your MCP client with its address, for example `https://mcp.apify.com/?tools=serenido/aliexpress-product-details`.

The files in `servers/` are published by `.github/workflows/publish.yml` (GitHub OIDC sign-in, no secrets).
