# Closing costs by U.S. state, 2026

Seller and buyer closing costs in all 50 states and the District of Columbia on a $400,000 home and at each state’s median home value: title insurance where each side usually pays for it, settlement, recording and attorney fees, lender charges, and the state and local taxes each side usually pays. State-set costs come from statutes and agencies; other fees are national estimates, stated in the methodology.

- **Web page, charts and methodology:** https://brokerandagent.com/research/closing-costs-by-state
- **Files:** [`data/closing-costs-by-state.csv`](data/closing-costs-by-state.csv) and [`data/closing-costs-by-state.json`](data/closing-costs-by-state.json) (the same rows, with full detail in the JSON)
- **Coverage:** all 50 states and the District of Columbia
- **Last updated:** 2026-10-01
- **Publisher:** [Broker & Agent Solutions](https://brokerandagent.com), a real estate software company in Sarasota, Florida

## Columns (CSV)

| Column | What it is |
|---|---|
| `state_code` | Two-letter postal code |
| `state` | State name (the District of Columbia included) |
| `seller_costs_400k` | The seller’s closing costs on a $400,000 sale, in dollars: title where the seller usually pays, settlement, recording and attorney fees, and the seller’s share of state and local taxes. No commissions, payoff or property tax split. |
| `seller_pct_400k` | Those costs as a percent of the price |
| `buyer_costs_400k` | The buyer’s closing costs on $400,000 with 20% down: lender charges and appraisal, title, settlement, recording and attorney fees, and the buyer’s state taxes. No prepaids or escrow. |
| `buyer_pct_400k` | Those costs as a percent of the price |
| `buyer_with_prepaids_400k` | The buyer’s closing costs plus prepaid interest, a year of insurance and the opening escrow deposit |
| `median_home_value_acs_2024` | Median value of owner-occupied homes, Census ACS 2024 1-year (B25077) |
| `seller_costs_median` | The seller’s closing costs at that median value |
| `buyer_costs_median` | The buyer’s closing costs at that median value, 20% down |
| `seller_biggest_state_cost` | The largest state-set cost on the seller’s side at $400,000 |
| `buyer_biggest_state_cost` | The largest state-set cost on the buyer’s side at $400,000 |
| `attorney_usually_closes` | Whether an attorney usually handles the closing (adds an attorney fee estimate) |
| `title_rates_set_by_state` | Whether the state sets title insurance premiums |
| `last_checked` | When the state’s rules were last checked against their sources |

## Limits

Costs a state sets (transfer and recording taxes, filed title rates) come from statutes and agencies. Fees no state sets, like lender charges, appraisal and settlement fees, are national estimates, so states without big state-set costs can show the same buyer figure. The methodology on the web page lists every estimate.

## License

[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You can copy, share and adapt it, commercially too, as long as you credit Broker & Agent Solutions and link to the source page.

## How to cite

> Broker & Agent Solutions. "Closing costs by U.S. state, 2026." Updated 2026-10-01. https://brokerandagent.com/research/closing-costs-by-state. Licensed under CC BY 4.0.

More on crediting and versions: https://brokerandagent.com/research/use-our-data

## Updates and corrections

The data is reviewed at least every six months and whenever a law changes. Each update is a new release here, so earlier versions stay available. Spot something out of date? Email hello@brokerandagent.com or open an issue, with a source if you have one.

## Related datasets

- [Real estate transfer tax by U.S. state, 2026](https://brokerandagent.com/research/transfer-tax-by-state) · [GitHub](https://github.com/embarkco/transfer-tax-by-state)
- [Property taxes by U.S. state, 2026](https://brokerandagent.com/research/property-taxes-by-state) · [GitHub](https://github.com/embarkco/property-taxes-by-state)
