### Filecoin data collected so far

Folder csvs:
* fielcoin_data_rewards: 
    - rewards data (output from df_supply_month of filecoin_rewards notebook)
    - $-price via coingecko
    - used total maximum supply of 2B FIL for relative token rewards
    - breakdown of simple vs baseline minting amount via calculation of simple-minting, using parameters: : b0 (initial baseline) = =2.8888888 ExBi, g_a (annual growth factor) = 1, g= 0.0000006593865873, MB_inf = 330,000,000, MS_inf = 770,000,000 , epochsPerDay = 2880 (1 epoch = 30s), lambda = 0.0000001098977645

Data sources:
- https://docs.spacescope.io/ (Overview of API endpoints)
- https://dashboard.starboard.ventures/ (Dashboard where most of API data can be downloaded as csv)
- https://stats.filecoin.io/ (Dashboard with network metriwcs)
- https://observablehq.com/@starboard/sproi (Profit calculator also providing parameters of simple-/baseline minting formula)
- https://github.com/protocol/filecoin-mecha-twin/blob/main/mechafil/minting.py (Pyhton package to run simulations but also pulls historical data via spacescope (notebook backtest), has parameters of simple-/baseline minting formula as well)


### Relevant articles/links

- https://docs.filecoin.io/basics/what-is-filecoin/overview/
- https://spec.filecoin.io/#section-algorithms.pos
- https://spec.filecoin.io/#section-systems.filecoin_token.block_reward_minting.simple-minting
- https://spec.filecoin.io/#section-systems.filecoin_token.block_reward_minting.baseline-minting
- https://medium.com/block-science/sustainability-goal-achieved-filecoin-network-crosses-baseline-target-cec13a3ed8f
- https://www.starboard.ventures/post/an-analysis-of-filecoin-storage-providers-storage-power-and-wealth-distribution
- https://www.starboard.ventures/post/economics-of-providing-web3-storage-on-filecoin
- https://medium.com/cryptoeconlab/unpacking-filecoins-gas-usage-ecaec1f021f4
- https://www.starboard.ventures/post/gas-burning-in-filecoin-a-protocol-bidding-mechanism-to-advance-the-network-s-health




