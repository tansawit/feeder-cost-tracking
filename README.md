# Standard Dataset Feeder Cost Tracking

## Tracked Metrics

### Supported Chains

For each chain (if possible/applicable on said chain):

- Current feeder account balance
- Symbols currently being updated
- Historical chart of feeder transaction gas prices
- Historical chart of daily number of price update transactions
- Last day/month/week/year
  - price update count for each symbol
  - daily feeder transaction count
  - feeder gas cost (for cost estimation)
- 7-day/30-day average
  - feeder transaction gas price (for optimization/cost estimation)
  - feeder transaction gas used (for optimization)
  - average number of symbols updated per feed transaction (for optimization)

### BandChain

- last day/week/month/year
  - request transaction count
