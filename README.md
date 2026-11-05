# Treasury Liquidity Map

Models synthetic cash movements and liquidity windows.

## What it includes

- deterministic sample data
- scoring and ranking logic
- command line report
- unit tests
- continuous validation workflow

## Run

```bash
python3 -m treasury_liquidity_map.cli --input data/sample_cashflows.json
```

## Test

```bash
python3 -m unittest discover tests
```
