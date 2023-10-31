### NYM data collected so far

Folder csvs:
* nym_data_rewards: 
    - rewards data (output from df_reward_history of nym_rewards notebook)
    - data pre 12/2022 (no API data) extrapolated from grafana dashboard (see 2nd bullet below)
    - $-price via coingecko
    - used total maximum supply of 1,000,000,000 for relative token rewards

Data sources:
* See nym_rewards notebook for details on APIs
    - https://mixnet.api.explorers.guru/api/ (mainly used in notebook)
    - https://validator.nymtech.net/api/v1/mixnodes/
    - https://explorer.nymtech.net/api/v1/mix-node/1 (has additional location data)
* https://status.notrustverify.ch/grafana/d/ l71MWkX7k/ntv-mixnode?orgId=1
* https://nym.explorers.guru/
* https://explorer.nymtech.net/
    


### Relevant articles/links

- https://nymtech.net/nym-whitepaper.pdf
- https://nymtech.net/docs/architecture/network-overview.html
- https://blog.nymtech.net/staking-in-nym-introducing-mainnet-mixmining-f9bb1cbc7c36
- https://cryptoeconomicsystems.pubpub.org/pub/diaz-reward-sharing-mixnets/release/2
- https://github.com/nymtech/rewardsharing-simulator
