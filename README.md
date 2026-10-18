# 🛢️ Commodity Trading — A Quant Finance Career Guide

**Live site:** https://`<your-username>`.github.io/commodity-trading-quant-career/

An educational GitHub Pages project that explains **commodity trading as a career in quantitative finance**. It is a single-page static site (plain HTML/CSS/JS, zero dependencies) covering:

| Section | What you'll find |
|---|---|
| 🏗️ The Market | Energy, metals, agriculture & softs complexes explained |
| 📖 Terminology Decoder | 35+ industry terms (contango, backwardation, roll yield, crack spread, basis, EFP, margin, VaR, CTA carry…) filterable by category |
| 🧰 Key Skills | Math, programming, data engineering and domain knowledge hiring managers weight |
| 🌍 Major Exchanges | CME Group, ICE, LME, EEX, DCE, SHFE/INE, MCX, B3, SGX + clearing houses, PRAs, data vendors |
| 📊 Strategy Families | Trend/momentum, term-structure/carry, stat-arb spreads, event alpha, volatility trading, structuring |
| 🪜 Career Path | QR → Senior Researcher/PM → Trader → Desk Head/Founder, compensation snapshot, who hires, how to break in |
| 📚 Resources | Books, free datasets, practice projects, regulatory notes (CFTC/EMIR) |

## 🚀 Deploy with GitHub Pages

1. Create a new repository named `commodity-trading-quant-career` on GitHub.
2. Push this project to it:
   ```bash
   git init -b main
   git add .
   git commit -m "Commodity trading quant career guide"
   git remote add origin https://github.com/<your-username>/commodity-trading-quant-career.git
   git push -u origin main
   ```
3. Go to **Settings → Pages → Build and deployment → Source** and select **GitHub Actions**.
4. The included workflow (`.github/workflows/pages.yml`) builds and publishes automatically on every push to `main`.
5. Your site goes live at the URL shown in the Pages settings (Actions tab shows progress).

Alternatively, skip the workflow entirely: set Pages source to **Deploy from a branch → `main` / (root)**.

## 🗂️ Project structure

```
├── index.html                  # The full site (self-contained)
├── README.md                   # You are here
└── .github/workflows/pages.yml # GitHub Pages deploy workflow
```

## 🛠️ Local preview

```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## 📝 Notes

- Content is educational only — **not investment advice**. Figures like market size and compensation ranges are approximate and vary by source/year.
- To customize: edit `index.html` directly (all styling is inline), or fork and rebrand the `COMEX·Quant` logo in the nav/footer.

## License

MIT — free to use, adapt and share.
