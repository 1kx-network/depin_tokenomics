### Livepeer data collected so far

Folder csvs:
* livepeer_data_rewards: 
    - rewards data (output from df_orch_month of livepeer_rewards notebook)
    - $ -price via coingecko (assumed 3$ before data available)
    - used total maximum supply estimate 74,000,000 (extending supply (per EoY'24) with annual inflation of 7% for 10 years) for relative token rewards

Data sources:
* https://dune.com/stronk/livepeer-arbitrum (based below query on those shared in various dune dashboards/queries, like this one...)
* https://dune.com/messari/Messari:-Livepeer-Macro-Financial-Statements (...or this one)
* https://dune.com/queries/1398261 (one query to get all orchestrator data (stake, rewards, fees, age etc.) per day (and chain))   
* https://dune.com/queries/3798334/6386063
* https://stronk.rocks/ (to check query outputs, e.g. https://grafana.stronk.tech/d/71b6OZ0Gz/orchestrator-overview?orgId=1&refresh=30s)



### Relevant articles/links

- https://livepeer.org/primer
- https://github.com/livepeer/wiki/blob/master/WHITEPAPER.md (or in general https://github.com/livepeer/wiki)
- https://docs.livepeer.org/guides/orchestrating/get-started
- https://www.livepool.io/#getstarted
- https://forum.livepeer.org/t/transcoding-verification-improvements-fast-full-verification/1499
- https://medium.com/livepeer-blog/a-primer-on-livepeers-probabilistic-micropayments-e16788b29331
- Case study on costs: https://mirror.xyz/0x91e2E2D26076C8A1EaDb69273605c16ef01928ce/-hPkroyM7PWIlXWQ8UhNhcFECfP1VsfE5-lY6Afp45s
