### Pocket data collected so far

Folder csvs:
* pocket_data_rewards: 
    - rewards data (output from df_rewards_monthly of pocket_rewards notebook)
    - $ -price via coingecko (assumed 0.2$ and 0.4$ before data available)
    - used total maximum supply estimate 3,900,988,660 (extending current supply with annual inflation of 10% for 10 years) for relative token rewards
    - additional data via poktscan.com
* pocket_chains: maps chain name and RelayChainId (used in pocket_rewards notebook)
* pocket_blocks: mapping of blockheights and dates (used in pocket_rewards notebook)

Data sources:
- https://poktscan.com/explore
- https://poktscan.com/api/graphql (in migration to v2, use fallback meanwhile: https://fallback- api.poktscan.com/)


### Relevant articles/links

- https://docs.pokt.network/learn/glossary/
- https://docs.pokt.network/learn/protocol/servicing/#proof-of-relay-evidence 
- https://forum.pokt.network/t/pip-7-consensus-rule-change-validator-servicer-split-validator-consolidation/1272 (Governance to adjust split between service nodes and validators)
- https://docs.google.com/spreadsheets/u/1/d/1AYrtyIuj94dOwMnLZn6Mrs0kqVJaZTMTZlUIZv4tIQc/edit#gid=968430523 (exploring different emission trajectories for POKT supply from 01/2023)
- https://docs.google.com/spreadsheets/d/18irsRUHXy69oaTtYGvWPVs0kNgkxzQHRxg--f48voIA/edit#gid=0 (interesting DCF valuation of pokt network from 06/2022)
- https://docs.google.com/spreadsheets/d/1R6G1sYwyYo57qfa6QFCtLxIOYcKsUigwMhH3ZHAUZl0/edit#gid=672232669 (PUP-22 FREN calculator)
