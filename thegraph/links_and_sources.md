### The Graph data collected so far

Folder csvs:
* thegraph_data_rewards: 
    - rewards data (output from df_rewards_monthly of thegraph_rewards notebook)
    - $-price via coingecko
    - used total maximum supply estimate 12,189,944,200 (extending current supply with (est.) annual net inflation of 2% for 10 years) for relative token rewards

Data sources:
* https://dune.com/abarmat/The-Graph-Overview (based below queries on those shared in that dashboard)
* See also thegraph_rewards notebook for query description
    - https://dune.com/queries/1844721 (GRT and dates of rewards paid to indexers)
    - https://dune.com/queries/1853711 (map epochs and dates for calculations on above)
    - https://dune.com/queries/1857084 (GRT and dates of indexers restaking GRT)
    - https://dune.com/queries/1838336 (date and GRT of query and curation fees per indexer)
    - https://dune.com/queries/1763641 (date and GRT of stake and delegate data per indexer)
    
* https://graphscan.io/ (to check query outputs)
* https://thegraph.stake-machine.com/



### Relevant articles/links

- https://thegraph.com/blog/the-graph-network-in-depth-part-1/
- https://thegraph.com/blog/the-graph-network-in-depth-part-2/
- https://ryabina.medium.com/graph-network-fee-cut-and-rewards-cut-hot-it-works-625fded9c827
- https://thegraph.com/docs/en/network/indexing/
- https://thegraph.academy/glossary/