# Electrical Lighting Co.

A responsive, single-page storefront **concept/demo** for Electrical Lighting Co., featuring lighting products, electrical accessories, and an interactive lighting showcase.

> **Demo only:** This repository is a frontend preview, not the live retailer's checkout. Product information and prices are illustrative snapshots and may change. Orders cannot be placed through this demo.

## Website preview

![Electrical Lighting Co. responsive storefront preview](https://raw.githubusercontent.com/JFUIX/ElectricalLightingCo./main/screenshots/website-preview.png)

## Features

- Responsive product-category navigation and product grids
- Interactive hero carousel with on/off, brightness, and colour-temperature controls
- Product search filtering within the demo catalogue
- Client-side basket with quantity adjustments, subtotal, and free-delivery progress indicator
- Buying-guide previews and trade-enquiry link
- Dark-mode styling, keyboard focus indicators, and reduced-motion support

## Tech stack

- HTML5
- CSS3 (embedded styles, responsive layouts, CSS animations)
- Vanilla JavaScript (no build step or dependencies)
- Google Fonts: Bricolage Grotesque and Instrument Sans
- Product imagery referenced from the retailer's Shopify CDN

## Run locally

1. Clone this repository:
   ```bash
   git clone "https://github.com/JFUIX/ElectricalLightingCo..git"
   ```
2. Open `index.html` in a modern browser.

Alternatively, serve the folder locally:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project structure

```text
ElectricalLightingCo./
├── index.html   # Page markup, styling, demo data and interactions
└── README.md    # Project documentation
```

## How the demo works

**Lighting preview:** Browse hero slides, toggle the light, adjust brightness, or choose a colour temperature. Carousel autoplay respects reduced-motion preferences and pauses while the tab is hidden.

**Catalogue:** Browse products by category or use the search field to filter the demo's predefined product lists. This is not a live inventory search.

**Basket:** Add products, change quantities, and view the subtotal and delivery threshold. Basket state is held in memory and resets on refresh; checkout is intentionally unavailable.

**External links:** Login, buying guides, and trade enquiries may lead to the retailer's external website. Those destinations and availability should be checked before production use.

## Limitations and next steps

- No Shopify API integration, account authentication, or real checkout
- No live stock, pricing updates, or server-side search
- Basket contents are not persisted between sessions
- Some category links are demo anchors rather than dedicated category pages
- External CDN images require a network connection; missing images use text fallbacks
- Cross-device browser and accessibility testing should be completed before a production launch

## Credits and usage

Frontend demonstration maintained in the [JFUIX GitHub profile](https://github.com/JFUIX). Product names, brand names, images, and related trademarks belong to their respective owners. This demo does not claim to be the official live store.

## Repository

[View source on GitHub](https://github.com/JFUIX/ElectricalLightingCo.)
