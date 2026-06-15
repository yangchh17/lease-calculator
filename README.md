# Mercedes-Benz Lease Comparison Tool

A single-page interactive tool built for a friend comparing two Mercedes-Benz models for a corporate lease in British Columbia. The goal was to make the financial trade-offs easy to explore and share without needing a spreadsheet or any backend.

## What it does

The tool lets you compare lease costs across two vehicles side by side, with real-time recalculation as you adjust the parameters. It accounts for BC-specific tax considerations including GST Input Tax Credit recovery, BC corporate tax deductions based on business-use percentage, and the CRA passenger vehicle lease deduction limit. Beyond the raw lease payments, it also factors in ancillary costs like EV charger installation, fuel vs. electricity estimates, and insurance differentials.

The app has three sections: a cost model with interactive sliders, a vehicle overview comparing key specs and use-case fit, and a side-by-side standard features comparison table.

## Stack

Plain HTML, CSS, and vanilla JavaScript — no frameworks, no build step, no dependencies. Everything runs client-side in a single `.html` file. Designed to be downloaded and opened directly in a browser, or hosted as a static page via GitHub Pages for easy sharing.

## Usage

Open `index.html` in any browser. Adjust the sliders to reflect actual dealer quotes as they come in. Toggle between 36-month and 48-month lease terms to compare total cost of ownership across different scenarios.
