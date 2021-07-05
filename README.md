# cryptolab-staking-treasury-proposal

# Proposal

## Title

CryptoLab

## Short description:

The CryptoLab (https://www.cryptolab.network/tools) aims to help non-technical nominators build stable and risk-controlled cash flows via well-designed and financial tools. The core idea is that we want to make staking the same as an investment. We help nominators to build good portfolios and to manage their portfolios to control risk and revenue. Portfolio management is challenging in Polkadot/Kusama system because they are NPoS consensus.

We design the CryptoLab website to help users to do their cryptocurrency financial management. From basic wordings to data representation, our goal is to make staking comprehensive to people who may not yet familiar with blockchain. We plan to provide the following features in this stage,

* Portfolio Benchmark
* Portfolio Management

Portfolio Benchmark helps nominators to evaluate which validators should they stake on. They can simply choose and nominate from our pre-built strategies or set their own conditions on different criteria to get a list of validators. And it is just the first step.

The real difference that makes CryptoLab outstanding is the Portfolio Management. We would like to help nominators track their revenue and suggest new sets of validators according to the criteria they set. We also would like to help nominators to make adjustments in time to prevent profit loss, by notifying them when a validator increased its commission or when a validator is being slashed.

## Context of the proposal: 

We first join Polkadot Ecosystem as Kusama validators and we found that the barrier to entry was quite high. To lower the risk as a validator we had to estimate funds required, operation costs, and estimate revenue after we start operating. However, we couldn't find any tool that would help us, there were indeed some APY estimation tools on the web but they were just static not very useful. The only choice was the Polkadot App but it was complicated to understand for a regular user and still lacks necessary information such as long-term APY. Another problem was that as a small operator it was very hard to get enough backing to get into the active set. 

As a result, we developed tools in our free time and shared the tools with the community. We have already developed some useful tools such as Polkadot/Kusama validator dashboards, Staking Rewards Reports, and Telegram Bots to notify validators about staking status and telemetry status. We received three tippings from both councils and got positive feedback from the community as well which encouraged us to keep going on.

We believe that it is time for us to make a big step, to provide a total solution for Polkadot/Kusama staking.

### The Team

* Yao-hsin Chen, who began to study blockchain in 2016, is one of the organizers of the Taipei Ethereum Meetup. He co-founded SOLA Technology and was the CEO until the end of 2020, in which he applied blockchain to solar monitoring and management. He forms the CryptoLab Team this year and is now a Polkadot/Kusama node operator.

* Yu-kai Tseng, who has 9-year experience in developing Industrial Ethernet Network Management System, is now a freelancer. He is an expert in distributed network service design and development and began to work on the first version of CryptoLab in 2021.

* Kin, who has 15-year experience on UI/UX. He is an expert in user experience and website design guidelines. He worked for language learning, gaming, government and tourism industry.

* Jack, who began to work in blockchain technology in 2017. He joined SOLA Technology in 2018, in which he is a full-stack developer. He developed applications that combined blockchain with solar monitoring and management.

### Current works

All of our work is open-sourced and resides in this GitHub organization

https://github.com/cryptolab-network

### Current usage analysis of CryptoLab

CryptoLab was online on 3/13/2021, we advertised the website mostly on public Element channels. From the reports of Google Analytics, until today, there were more than 600 new and returning users from varied countries. There were about 200 users in recent 4 weeks, about 1/3 of them were returning users. On average 10-20 users each day. Desktop and mobile user ratios are approximately 1:1. We think it is good because more than 30% of people returned to the website. 

We also released the Kusama and Polkadot bots for validators several weeks later to help them to be notified about the nomination and whether their node was online. There are about 50 Kusama Bot users and more than 10 Polkadot Bot users. We actually received positive feedback from both website and bot users.

### Feedbacks from the Community

We appreciate the feedback from the community, which encouraged us to make it better.

<img src="https://user-images.githubusercontent.com/3665658/121636575-abcd0500-caba-11eb-9c97-1c0068beef24.png" width="500">
<img src="https://user-images.githubusercontent.com/3665658/121636603-b4bdd680-caba-11eb-861e-6fea3f323ffa.png" width="500">
<img src="https://user-images.githubusercontent.com/3665658/121637358-d8355100-cabb-11eb-9213-cb3cfaab8e3a.png" width="650">
<img src="https://user-images.githubusercontent.com/3665658/121762175-dd9ba580-cb66-11eb-8e6e-b2c36d829893.png" width="600">
<img src="https://user-images.githubusercontent.com/3665658/121762190-f99f4700-cb66-11eb-9851-ee9b8be9ee80.png" width="650">

## Problem statement: 

As Polkadot and Kusama are NPoS consensus-based blockchains, nominators are able to nominate more than one validator, which makes staking procedire complicated. When users stake on other blockchains, they just need to choose one validator and delegate their funds to them. When staking on Polkadot or Kusama, they could choose more then 1 but up to 24 validators. It is hard for nominators to analyse so many validators to see which ones are trustworthy and are able to earn most revenue from them.

From our observation, nominators tends to

* nominate in centralized exchanges, which hurts decentralization.
* nominate top validators on the Target page on Polkadot App, which still hurts decentralization because by doing it, funds tend to be delegated to those who already have enough backups.
* nominate only active validators, which also make funds gathered to those already have enough backups.

There are developers from the community trying to resolve the problem by providing a validator ranking system and user-friendly staking tools.

1. Yieldscan (https://yieldscan.app/)

The goal of Yieldscan is just as their slogan "built to maximize staking yield and designed to minimize effort". It helps nominators to maximize their profit from staking. They used a risk level system, in which users can simply input staking amount, risk level, and duration. The system chooses 16 validators that fulfill the conditions users set, estimates the APY, and helps users to nominate them. Yieldscan also has dashboards of both validators and nominators. It supports both Polkadot and Kusama.


2. Polkastats - Validator Resource Center (https://validatorsv2.kusama.polkastats.io/)

Polkastats is another similar project, it is a validator resource center. The site uses VRC score, which is calculated from varieties of parameters. They help nominators by providing a dashboard of validators, displaying info such as commission, self stake, etc. so that nominators have a baseline to compare each other. Polkastats also has a nomination system, which focused on the decentralization of the network. It has a unique feature that nominators can import their validator sets to customize the next sets of validators. It supports Kusama.

3. Staking tools in centralized exchanges / Auto staking service blockchains (e.g. https://stake.fish/en/)

Simple staking tools are offered by centralized exchanges, they are designed to make the staking procedure as simple as a nominate button. There should be an auto staking management system behind these exchanges. The cons of using it are, first, the APY is worse because of the service fee's and second, it hurts decentralization. The pros and cons are similar when it comes to those blockchains which offers auto staking services.

However, we saw there are no complete *Portfolio Management* solutions for Polkadot/Kusama nominators to track their revenue from staking and validator status after nomination. In our view, staking is not a one-time operation, it should be constantly monitored and adjusted to ensure profit. We saw no such solutions on the market now.

## Proposal Objective/solution/s to point 2:

We provide *Portfolio Benchmark* to help nominators choose which validators to nominate. *Portfolio Management* to help nominators to monitor validator status so they can make adjustments just in time.

We have already provided some tools on CryptoLab and also Telegram bots and have some regular users. It is time to polish the website and to work on providing a total solution for staking.

There are three top-tier goals included in this proposal.

1. Current CryptoLab website maintenance
2. CryptoLab Staking Tool
3. Telegram Bots for both Polkadot/Kusama nominators

The first two goals are focused on making what we have done better. We plan to enhance the current CryptoLab by

* Re-design the UI/UX of CryptoLab, including RWD.
* Move the service to AWS to improve the performance.
* Maintain our own Polkadot/Kusama archived nodes to improve the performance.

The goals 2 and 3 are what we are planning to do. 

### Portfolio Benchmark

In Portfolio Benchmark, we would like to help DOT/KSM holders to stake in a single step. It has two modes, simple and advanced.

Nominators first need to allow CryptoLab in Polkadot Browser Extension. The website would detect the amount of KSM/DOT in each account.

In simple mode, our goal is to make a one-button staking feature.

![image](https://user-images.githubusercontent.com/3665658/121618019-a494ff80-ca98-11eb-960e-5289fc15ce1a.png)

We offer several strategies to help users to select validators. The following table is a detailed description of these strategies.

| Strategy | Description |
| -------- | ----------- |
| Low risk | In this mode, we select validators with <br/> <ul><li> self stake >= 50 KSM or 1000 DOT </li><li>has a verified identity</li><li>unclaimed eras < 16</li><li>no slash</li><li>can be bound to a telemetry node</li></ul> |
| High APY | In this mode, we select validators with <br/> <ul><li>Highest average APY in recent 84 eras</li></ul> |
| Decentralization | In this mode, we select validators with <br/><ul><li>Highest average APY in recent 84 eras</li><li>has a verified identity</li><li>but if an identity contains multiple sub identities, only one among them would be selected</li></ul> |
| One Thousand Validator Program| In this mode, we select validators with <br/><ul><li>is active in either Polkadot/Kusama One Thousand Validator Program</li><li>we would also use the current strategy, which is already being implemented in CryptoLab to choose from 1kv validators to maximize the chance that at least one of the node is active</li></ul> |

In the advanced mode, users may set their own threshold to filter validators. Then they can select up to 24 validators in Kusama and 16 validators in Polkadot to nominate.

The following are the conditions we would like to take into account when we select validators.

| Conditions | Description|
| ---------- | ---------- |
| Self Stake | Users may input the minimum self stake |
| Commission  | Users may input the maximum commission |
| Identity   | Users may filter only validators with a verified identity |
| Unclaimed eras | Users may input the maximum unclaimed eras |
| Previous slashes | Users may filter only validators with no slashing records |
| Is Sub identity| Users may filter only validators which are not a sub-identity |
| Historical APY(%)| Users may input the minimum historical APY in the previous 84 eras | 
| Inclusion | Users may input the minimum era inclusion rate in the previous 84 eras |
| Telemetry | Users may filter only validators which can be bound to a telemetry |

![image](https://user-images.githubusercontent.com/3665658/121617856-5da70a00-ca98-11eb-8c85-b8111761be2a.png)

They then could input how much funds they want to stake and they are able to select their reward destinations, there are three possible options the same as on the Polkadot App.

Once the validator list is generated and the reward destination is selected, nominators can press the Nominate button, and the Polkadot Browser Extension would popup to ask them to sign the transaction.

### Portfolio Management

In Portfolio Management, the CryptoLab would cover aspects such as revenue report, validator status notification, and re-nomination. The goal is to help nominators constantly monitor and ensure their profit via staking. 

There would have several pages in Portfolio Management, the first one is *Performance*.

![image](https://user-images.githubusercontent.com/5772463/121611370-abb51100-ca8a-11eb-8f0b-ceaba91b5850.png)

The Performance page, users are able to see

* a summary of their earnings from all accounts in their wallets. 
* a chart that shows their profit trend, users may choose different timespan to see the sum of their profit. 
* a detailed report of how much they earn through all eras, similar to the Staking Rewards Collector.
* re-nominate validators

CryptoLab would create a list of suggested validators according to the strategy they choose while including several inactive nodes at the same time. Our theory is to **gradually change the staking behavior**. 

Take the following example, assume there are 6 validators, three of them are active and the others are inactive. Each nominator can nominate up to three validators. In general, nominators tend to choose those who have a high inclusion rate and APY (Set 1. in the table below). However, because Polkadot/Kusama uses the result of the sequential Phragmén method, the revenue would be similar regardless nominators choose Set 1. or Set 2. Our goal is to make nominators rest assured to choose Set 2. (or any sets that contain inactive nodes) to make funds more decentralized.

| Validators | A (active), APY: 17%, Inclusion: 100% | B (active), APY: 16%, Inclusion: 100% | C (active), APY: 15%, Inclusion: 50% | D (inactive), APY: -, Inclusion: 25% | E (inactive), APY: -, Inclusion: 10% | F (inactive), APY: -, Inclusion: 0% |
| ---------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| Nomination Set 1 | V | V |  V |  V  |   |   | 
| Nomination Set 2 | V | V |   |    | V  |  V  | 

The second one is unique, the Notification page

![image](https://user-images.githubusercontent.com/3665658/121618476-66e4a680-ca99-11eb-894b-3b6946a0a4d5.png)

In this page, users are able to see,

* historical events, up to 84 eras.
* setup CryptoBots on Telegram or on email.

These events would be recorded, and users can be notified on Telegram and email.

| event | description |
| ----- | ----------- |
| commission change | CryptoLab would create an event when the validator commission is changed. |
| slash | CryptoLab would create an event when a validator is slashed. |
| all inactive | CryptoLab would create an event when all nominated validators are inactive in an era. |
| oversubscribed | CetproLab would create an event when a validator is oversubscribed. |

Revenue reports would also be sent to them regularly.

### Telegram Bots for nominators


For the Telegram Bots for nominators, we plan to provide the followings,

* Notify users when a validator commission is changed.
* Notify users when a validator is slashed.
* Notify users when a validator is oversubscribed.
* Notify users when all validators they selected are inactive.
* Regular revenue reports

so that nominators are able to make adjustments in time.

### Planned Service Architecture

Current CryptoLab is running on a single VPS, and retrieves data on-chain through either Parity or onFinality. There is still room for improvement. Retrieving validator's  and nominators' data while listening to Payout events and saving them to a DB could be longer than 30 minutes. We plan to separate the processes into different instances and use the resource on AWS to improve the performance.

![image](https://user-images.githubusercontent.com/3665658/121618770-fbe79f80-ca99-11eb-8043-4e880de570e8.png)

The servers is consist of two EC2 instances, one DB and one Redis instance, to operate the CryptoLab backend servers. We would also run two EC2 instances for Polkadot/Kusama node so that on-chain data could be retrieved faster.

### Who does this solution help?

We want to make staking simple so that DOT/KSM holders could choose to stake directly on-chain instead of using wrapped solutions such as from centralized exchanges. Also, by providing an easy-to-understand view of validators, we want to ease the situation that most funds are gathered on a few validators to make the network more decentralized. Last but not least, we want to increase the chance for independent validators to be nominated.

### Milestones and tasks to include:

The milestones include 3 phases, we would send each milestone in separate proposals. The designer and developer cost is estimated as 1500 USD/week (full time)

#### Milestone 1. (9.5-week)

Milestone 1. will be submitted to Kusama Treasury. The duration and cost would only cover the Kusama part.

| Description | Man-power | Duration | Price | Deliverables |
| ----------- | --------- | -------- | ----- | ------------ |
| Re-design the UI/UX of CryptoLab     | Designer: 1 | 3 weeks | 4,500 USD | Mockup UI in Adobe Creative Cloud |
| Implement CryptoLab Portfolio Benchmark | Developers: 2 | 1.5 weeks | 4,500 USD | Webpages for nominators to filter validators by different conditions so that they can nominate them. |
| Implement CryptoLab Portfolio Management | Developers: 2 | 3 weeks | 9,000 USD | Web pages for nominators to monitor their revenue and validator status.  |
| Implement CryptoLab Staking Guide | Developers: 1 | 1 week | 1,500 USD | Webpages to guide nominators to stake on CryptoLab. |
| Telegram Bots for nominators     | Developer: 1 | 1 weeks | 1,500 USD | Telegram Bots for nominators included features described in Portfolio Management. |

Total: 21000 USD

#### Milestone 2. (7.5-week)

Milestone 2. will be submitted to Polkadot Treasury.

| Description | Man-power | Duration | Price | Deliverables |
| ----------- | --------- | -------- | ----- | ------------ |
| Implement the Polkadot part | Developers:  | 3.5 weeks | 5,250 USD | Polkadot part of Milestone 1. |
| RWD UI/UX of CryptoLab     | Designer: 1 | 1 week | 1,500 USD | Mockup UI in Adobe Creative Cloud for Phone and Tablet  |
| Implement RWD UI/UX of CryptoLab | Developers: 2 | 2 weeks | 6,000 USD | CryptoLab on Phone and Tablet |
| DevOps for maintenance | Developers: 1 | 1 week | 1,500 USD | Internal dashboard to display service status such as chain data last updated time, online/offline, bandwidth usage, etc. |

Total: 14250 USD

### Milestone 3. (3-week)
 
 In this stage, we would like to apply the new UI/UX on current CryptoLab webpages, including *Kusama/Polkadot Validator/Nominator Status*, *Validator Dashboard*, and *Kusama/Polkadot One Thousand Validator Monitor*.
 
| Description | Man-power | Duration | Price | Deliverables |
| ----------- | --------- | -------- | ----- | ------------ |
| Re-design UI/UX of CryptoLab    | Designer: 1 | 1 week | 1,500 USD | Mockup UI in Adobe Creative Cloud |
| Implement Re-designed UI/UX of CryptoLab | Developers: 2 | 2 weeks | 6,000 USD | Reworked webpages |

Total: 7500 USD

Except from the milestones above, the operation cost is another necessary expense for us to operate CryptoLab. 

The operation cost includes EC2 instances, DB, and Redis instances, to run CryptoLab backend servers. We would also run two EC2 instances for Polkadot/Kusama node.

*We can provide the detailed estimation from the AWS calculator if the committee needs it*

The operation costs later than 6 months would be applied in future proposals if this one is being approved.

| Description | Duration | Price | Total | 
| ----------- | --------- | -------- | ----- |
| Operation cost for CryptoLab     | 6 months | 250 USD | 1,500 USD |
| Operation cost for runnig Polkadot Node | 6 months | 375 USD | 2,250 USD |
| Operation cost for runnig Kusama Node | 6 months | 375 USD | 2,250 USD |

The operation cost would be split evenly to submit to both network.

Total: 6000 USD

### Include any extra links completing the proposal here

[CryptoLab](https://www.cryptolab.network)

## Why Kusama? 

Kusama ecosystem is friendly when it comes to staking. As the lowest staking amount is about 4500 KSM to be an active validator, and the number of validators is much larger than Polkadot, we chose Kusama to be the first place to verify our solution. Besides, the Kusama community is active. We can get feedbacks more easily from it.

## If you have seen similar proposals before: why is yours different?

[Validator Resource Center and Ranking Website for Kusama (Phase 2) - Report](https://kusama.polkassembly.io/treasury/82)

[Validator Resource Center and Ranking Website for Kusama (Phase 2 - Milestones 6, 7, 8, 9, 10)](https://kusama.polkassembly.io/treasury/90)

The Polkastats is a similar project, both of us are aimed to improve the staking procedure. The differences are

* We support Polkadot/Kusama
* We proposed a total solution. Not only staking but also allows users to monitor and manage their stakes after it.
* We support Telegram Bots to notify users just in time.

Teaching users is a challenging and high-cost task, let alone we would like to change user behavior so that they are willing to support trustworthy validators, not just choose those who have higher APY. We hope that by doing it, we can make Polkadot/Kusama ecosystem much more stable and decentralized. Take the event on 5/24/2021, [Polkadot nodes failed with an out of memory (OOM) error on block 5,202,216.](https://polkadot.network/a-polkadot-postmortem-24-05-2021/). The network recovered soon because community node operators, especially those who joined the 1KV, took quick responses. Thus we also provide a strategy to allow users to support 1KV operators.

## Payment conditions

*Payment conditions would further be adjusted according to the 30-day avg. price when submitted on-chain in order to correspond to the price fluctuations recently.

Address: DBBFZxZqGPb2LSQSA4WHugerXGwm2ivywqdPxVnsJA9oyV3

Total Payment: 48750 USD. It would be split to apply to both treasury because the CryptoLab would support both networks.
The applied support would be,

* Kusama: 24000 USD / 269.42 KSM = 89.08 KSM
* Polkadot: 24750 USD / 18.798 DOT = 1316.63 DOT

* To calculate the price, we use Subscan's 30 avg tool on the day of submission:
Kusama: https://kusama.subscan.io/tools/charts?type=price (based on 7/5/2021)

* Treasury timeline is related to milestones. We expect to have a report upon each milestone is done and online.

* 1st milestone: include development and 6-month operation cost. 

 Operation cost to be paid once the proposal is approved (3000 USD / 269.42 KSM ~= 11.13 KSM)

 Development cost to be paid after the report is approved (21000 USD / 269.42 KSM ~= 77.95 KSM)

* 2nd milestone: to be paid after the report is approved (14250 USD / 18.798 DOT ~= 758.06 DOT)

 Operation cost to be paid once the proposal is approved (3000 USD / 18.798 DOT ~= 159.59 DOT)

* 3rd milestone: to be paid after the report is approved (7500 USD / 18.798 DOT ~= 398.98 DOT)

* Development work will start upon approval.

