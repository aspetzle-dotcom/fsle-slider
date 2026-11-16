# Chaotic LV FSLE noise slider

[Open the interactive slider](https://aspetzle-dotcom.github.io/fsle-slider/).

Compare direct, raw S-map, and HMS S-map FSLE estimates for a chaotic Lotka–Volterra time series. Toggle between 100 and 750 observations while keeping the selected noise percentage. The shorter record uses the first 100 observations of the longer record.

The observation-noise slider covers 0%–80% of the selected clean record's standard deviation in 1% steps. All three curves and the clean reference update with the observation count. Dashed HMS curves identify fits that did not converge.

`index.html` is a standalone file with all data and scripts embedded. It also works offline when downloaded. GitHub Pages serves it from the root of `main`.

To update the live slider, replace `index.html` with the revised standalone export and push to `main`.
