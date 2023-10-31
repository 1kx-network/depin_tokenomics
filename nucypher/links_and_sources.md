### Nucypher data collected so far

Folder csvs:
* nucypher_data_rewards: 
    - rewards data (aggregated from dune queries below)
    - data pre 12/2022 (no API data) extrapolated from grafana dashboard (see 2nd bullet below)
    - $-price via coingecko
    - used total maximum supply of 3,890,000,000 for relative token rewards

Data sources:
* Used dune queries (subgraph also available)
    - https://dune.com/queries/2036542 (Total staking rewards)
    - https://dune.com/queries/2036596 (WorkLock rewards)
    - https://dune.com/queries/1994732 (Active workers)

    


### Relevant articles/links

- https://github.com/nucypher/whitepaper/blob/master/whitepaper.pdf
- https://github.com/nucypher/mining-paper/blob/master/mining-paper.pdf
- https://github.com/nucypher/whitepaper/blob/master/economics/staking_protocol/NuCypher_Staking_Protocol_Economics.pdf
- https://gauntlet.network/reports/nucypher (simulations on WorkLock assessment and staking economics)
- https://blog.threshold.network/the-story-of-threshold/
