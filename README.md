# Social Security Claim Timing

A single-page app for deciding when to start Social Security. It compares claiming at 62, 65, 67, 70 or any custom month, using the monthly amounts from your SSA Retirement Calculator estimate.

## What it shows

- Which claiming age pays the most for each possible lifespan, with rough odds of each outcome
- Expected lifetime total for each option, weighted by those odds
- Totals collected if you live to a chosen age
- Cumulative benefits chart with breakeven points
- Cost of waiting: how much savings must cover between when you stop working and when checks start
- Breakeven ages for every pair of options

## Use

Open `index.html` in a browser. No build step or server needed. Inputs are saved in that browser's local storage.

## Notes

Life odds come from a simple model of US male mortality and are estimates only. Amounts for custom months are interpolated between the SSA figures. Spousal and survivor benefits and taxes are not included. Not financial advice.
