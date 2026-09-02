# Blind Baker

A compact reference for cooking and baking **ratios**: the reusable proportions behind recipes such as bread, pound cake, pie dough, biscuits, meringue, and classic sauces.

Instead of presenting full recipes, Blind Baker emphasizes the structural relationship between ingredients—for example, `5:3` flour to water for a basic bread dough or `3:2:1` flour to fat to water for pie dough.

## Why ratios

Ratios make recipes easier to reason about and scale. They expose the underlying formula so a cook can adjust batch size or recognize related preparations without depending on one exact set of measurements.

## Implementation

Blind Baker is deliberately simple: one static `index.html` file containing the data, styles, and rendering logic.

- HTML + CSS + vanilla JavaScript
- responsive layout
- automatic light/dark color scheme support
- no dependencies
- no build step

## Run locally

Open `index.html` directly in a browser, or serve the directory with any static web server:

```sh
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Status

Small reference-tool prototype. The ratios are presented as practical culinary references, not as a substitute for recipe-specific technique, ingredient behavior, or food-safety guidance.
