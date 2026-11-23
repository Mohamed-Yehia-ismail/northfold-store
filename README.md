# Northfold

Arabic / English clothing store front for Saudi Arabia and Egypt.

**Live demo:** https://mohamed-yehia-ismail.github.io/northfold-store/

## Features

- 16 products drawn in SVG, with a fabric close-up on hover
- Filters by gender, category, colour family, size and price, plus search and sort
- Product window with colours, sizes, a size guide in centimetres and instalment info
- Bag drawer with a free-shipping progress bar, saved in localStorage
- Market switch (Saudi Arabia / Egypt): currency, shipping, instalments and payment methods
- Full right-to-left Arabic layout, light and dark mode

## Tech

HTML5, CSS3 (custom properties, grid, logical properties for RTL), vanilla JavaScript, inline SVG. No frameworks, no build step.

## Performance and scale

A single static file served from GitHub Pages: no server and no database, so traffic only reaches the CDN. State is kept in `localStorage` with safe fallbacks.

## Run locally

```bash
python3 -m http.server 8000
```

This is a demo project for my portfolio; the business, people and prices are fictional.

## Author

Mohamed Yehia · [GitHub](https://github.com/Mohamed-Yehia-ismail) · [LinkedIn](https://www.linkedin.com/in/mohamed-yehia-ismail)
