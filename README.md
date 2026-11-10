# Nagpur Temperatures, 1–9 November 2026

An interactive chart of the daily minimum and maximum temperature in Nagpur from 1 to 9 November 2026, built with [D3.js](https://d3js.org/). The design follows a hand-drawn notebook sketch.

**Live page:** https://YOUR-USERNAME.github.io/nagpur-temperature/

## What it shows

- Each day has a vertical line running from its minimum to its maximum temperature (°C).
- Max temperature dots are red and min temperature dots are blue.
- The y-axis runs from 15° to 35°. The x-axis shows the dates, 1 to 9 November.
- Hover, tap, or tab to a day to see its date, max, min and range.

## Run it locally

The whole chart is a single file, `index.html`. Open it in any modern browser. D3 and the Kalam font load from the internet, so you need to be online.

## Update the data

The temperatures are in the `data` array near the bottom of `index.html`:

```js
{ day: 1, min: 21, max: 30 },
```

To change the y-axis range, edit `Y_MIN` and `Y_MAX` just below it. The colours for the min and max dots are the `--cold` and `--hot` variables at the top of the file.

## Data source

Temperatures from [timeanddate.com](https://www.timeanddate.com/weather/india/nagpur/historic).

## Built with

- [D3.js](https://d3js.org/) v7.9.0
- [Kalam](https://fonts.google.com/specimen/Kalam) font from Google Fonts
- Plain HTML, CSS and JavaScript, with no build step
