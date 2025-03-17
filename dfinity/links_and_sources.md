### Dfinity/ICP data collected so far

Folder csvs:
* dfinity_rewards_data: 
    - contains the reward emission based on dashboard data (see data sources)
    - deducted 80 node machine rewards from total node count to account for system subnets (proprietary blockchain)
    - used total maximum supply of 850M ICP for relative token rewards

Data sources:
* Node provider rewards: https://dashboard.internetcomputer.org/circulation
* Subnets: https://dashboard.internetcomputer.org/subnets?s=100
* Dashboard API: https://ic-api.internetcomputer.org/api/v3/swagger

### Relevant articles/links

- Inflation discussion: https://forum.dfinity.org/t/solution-for-preventing-node-provider-rewards-inflationary-death-spiral/23045/3
-  Intro article: https://medium.com/dfinity/understanding-the-internet-computers-network-nervous-system-neurons-and-icp-utility-tokens-730dab65cae8
- ICP node provider rewards: https://wiki.internetcomputer.org/wiki/Node_Provider_Remuneration
- Costs: https://icp.guide/costs-on-the-internet-computer/#Data_Transfer
