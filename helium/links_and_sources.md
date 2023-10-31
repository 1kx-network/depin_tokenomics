### Helium (LoRaWAN) data collected so far

Folder csvs:
* helium_data_rewards: 
    - rewards data (output from df_net_rewards of helium_rewards notebook  - see also data sources below how to get those easier)
    - dollar-price via coingecko (assumed 0.1$ before data available)
    - used total maximum supply of 223,000,000 HNT for relative token rewards
    - rewards for service nodes and their validation (not blockchain consensus) based on split of rewards presented in HIP 20 (see 5th item in relevant articles/links)
    - #hotspots as avg/month from https://etl.dewi.org/question/12-total-hotspots
* hnt-usd-max: price data from coingecko
* helium_rewards_etl_daily:
    - daily total rewards and number accounts receiving those from etl.dewi query (see in helium_rewards notebook)
    - was to check this vs. API data (and because of timeouts just until end of 2021)  - there are some small differences to the rewards shown in helium_data_rewards.csv

Data sources:
* https://api.helium.io/v1 (no longer supported since move to solana end of April 2023, see details: https://docs.helium.com/api/blockchain/hotspots/)
* https://etl.dewi.org/collection/root (has all the data pre Solana migration in easy accessible format)
* https://heliumanalytics.io/monthly-reward-distribution/ (great data/visualization of reward distribution across hotspots)
* https://docs.helium.com/oracles/oracle-data/ (presented as alternative to pull data after deprecation of helium api - haven't used it yet though)
* https://dune.com/helium-foundation/ (data after solana migration available in various dashboards)
* https://flipsidecrypto.xyz/anduril/helium-network-stats-v-1-b3PLLp (same is true for flipsidycrypto)



### Relevant articles/links

- http://whitepaper.helium.com/
- https://docs.helium.com/faq/helium-network/
- https://docs.helium.com/blockchain/proof-of-coverage
- https://github.com/helium/HIP/blob/main/0010-usage-based-data-transfer-rewards.md
- https://medium.com/helium-foundation/helium-community-approves-hip-20-127cf75303bf
- https://github.com/helium/HIP/blob/main/0020-hnt-max-supply.md#detailed-explanation (detailed split of rewards across functions over time)
- https://docs.helium.com/vote-escrow/voting-power/
- https://explorer.helium.com/
