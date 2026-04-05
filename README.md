# FIRE Calculator

An interactive Financial Independence, Retire Early (FIRE) calculator — find out exactly when you can walk away from work.

**[Access it here](https://haris-alam23.github.io/fire-calculator)**



## Features

- **Real-time projections** — all sliders update instantly, no page reload
- **Inflation-adjusted returns** — uses real return rate, not nominal
- **Portfolio growth chart** — visualizes your portfolio value vs. total contributions vs. your FIRE target
- **Progress tracker** — shows how far along you are today
- Built on the **4% safe withdrawal rule** (Trinity Study)

## How It Works

1. Enter your annual income, expenses, current savings, and age
2. Adjust expected return and inflation rate
3. See your FIRE number (25× annual expenses), years to retirement, and portfolio trajectory

## The Math

- **FIRE Number** = Annual Expenses × 25
- **Real Return** = ((1 + nominal return) / (1 + inflation)) − 1
- Portfolio compounded annually with real return + annual savings contribution

## Usage

No install, no dependencies, no server required.

```bash
git clone https://github.com/haris-alam23/fire-calculator.git
cd fire-calculator
open index.html
```

Or just open `index.html` directly in any browser.

## Tech Stack

- Vanilla HTML / CSS / JavaScript
- [Chart.js](https://www.chartjs.org/) for visualizations

## License

MIT
