# CoinMarketCap RWA Explorer & Safe-Haven Hedge Calculator

A live Real-World Asset (RWA) analytics and safe-haven hedge simulator built for **Build with CMC: API Hackathon (Round 2)** — **Real World Assets** track (`#BuildwithCMC`).

Powered by live **CoinMarketCap MCP** tool calls (`https://mcp.coinmarketcap.com/mcp`) inside Claude across **PAXG, XAUt, ONDO, USDY, and BTC** (`2026-11-22T07:24:18Z`), deployed as a zero-dependency web app on GitHub Pages.

- **Live Demo:** https://prakhardewangan2005-hash.github.io/cmc-rwa-explorer/
- **CMC MCP Tools Used:** `search_cryptos`, `get_crypto_quotes_latest`, `get_crypto_info`, `get_crypto_metrics`, `get_crypto_latest_news`

## Key Features
- **Live RWA Quotes & Liquidity Table:** Real-time USD prices, 24h/7d/30d/YTD performance, market cap, 24h volume, Vol/MCap ratio, and circulating/max supply.
- **Tokenised Gold Peg & Liquidity Comparator:** Side-by-side PAXG ($3,529.82) vs. XAUt ($3,528.44) spread (+$1.39 / 0.039%), market cap share, volume share, and turnover.
- **Interactive Safe-Haven Allocation Simulator:** Sliders to mix Tokenised Gold, Tokenised Treasuries/RWA (`USDY` or `ONDO`), and `BTC` to compute 30d and YTD cushion vs. 100% BTC.
- **Latest RWA News & Holder Concentration:** Live CoinMarketCap headlines and whale/long-term holder metrics.
- **Live Response Proof & Data Audit:** Collapsible drawer listing exact MCP tool calls, arguments, verbatim excerpts, and 7 API data-quality findings (including XAUt circulating vs. self-reported supply mismatch, BTC whale volume > 21M supply, empty `avgTransactionFee30d`, and empty `USDY` description).
