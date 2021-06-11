# cryptolab-staking-treasury-proposal

# Proposal

## Title

CryptoLab

## Short description:

The CryptoLab (https://www.cryptolab.network/tools) aims to help non-technical nominators build stable and risk-controlled cash flows via well-designed and financial tools. The core idea is that we want to make staking the same as investment. We help nominators to build good portfolios and to manage their portfolios to control risk and revenue. Portfolio management is challenging in Polkadot/Kusama system because they are NPoS consensus.

We design the CryptoLab website to help users to do their crypto currency financial management. From basic wordings to data representation, our goal is to we make staking comprehensive to people who may not yet familiar with blockchain. We plan to provide the following features in this stage,

* Portfolio Benchmark
* Portfolio Management

Portfolio Benchmark helps nominators to evaluate which validators should they stake on. They can simply choose and nominate from our pre-built strategies or set their own conditions on different criteria to get a list of validators. And it is just the first step.

The real difference that makes CryptoLab outstanding is the Portfolio Management. We would like to help nominators to track their revenue and to suggest new sets of validators according to the criteria they set. We also would like to help nominators to make adjustment in time to prevent from profit loss, by notifying them when a validator increased its commission or when a validator is being slashed.

(我覺得這邊有點跳, 怎麼突然扯到decentralization)

Decentralization is the key to make long term Polkadot/Kusama ecosystem healthy. Our utmost goal is to help nominators to get stable income while keep the system dencentralized.

## Context of the proposal: 

We first acted as Kusama validators to cut in to the ecosystem. We found that the entry barrier was quite high. For example, to lower the risk, as a validator, we would like to estimate how much funds we need, and what is the revenue after we start operating. However, we can't find any tool to help us, there were indeed some APY estimation tools on the web but they were just static not useful at all. The only choice was the Polkadot App but it was complicated and still lacks of necessary information such as long-term APY. Another problem is that personal operators were nearly impossible to get enough backup to be consistently active. Operators are hard to be nominated if they were not in the active set, and they can't be in the active set because they are hard to be nominated.

As a result, we developed tools for ourselves in our free time and shared the tools to the community. We have already developed some useful tools such as Polkadot/Kusama validator dashboards, Staking Rewards Reports and Telegram Bots to notify validators about staking status and telemetry status. We received three tippings from both councils and got positive feedbacks from the community as well which encouraged us to keep going on.

We believe that it is time for us to make a big step, to provide a total solution for Polkadot/Kusama staking.

### The Team

* Yao-hsin Chen, who began to study blockchain from 2016, is one of the organizer of Taipei Ethereum Meetup. He co-founded the SOLA Technology and was the CEO until the end of 2020, in which he applied blockchain to solar monitoring and management. He forms the CryptoLab Team from this year, and is now a Polkadot/Kusama node operator.

* Yu-kai Tseng, who has 9-year experience on developing Industrial Ethernet Network Management System, is now freelancer. He is expert in distributed network service design and development and began to work on the first version of CryptoLab in 2021.

* Kin, who has 15-year experience on UI/UX. He is expert in user experience and website design guidelines. He worked for language learning, gaming, government and tourism industry.

* Jack, who began to work in blockchain technology from 2017. He joined SOLA Technology from 2018, in which he is a full-stack developer. He developed applications which combined blockchain with solar monitoring and management.

### Current works

All of our works are open-sourced and resides in this github organization

https://github.com/cryptolab-network

### Current usage analysis of CryptoLab

CryptoLab was online at 3/13/2021, we advertised the website mostly on public Element channels. From the reports of Google Analytics, until today, there were more than 600 new and returning users from varied countries. There were about 200 users in recent 4 weeks, about 1/3 of them were returning users. In average 10-20 users each day. Desktop and mobile user ratio is approximately 1:1. We think it is good because more than 30% of people returned to the website. 

We also released the Kusama and Polkadot bots for validators several weeks later to help them to be notified about nomination and whether their node were online. There are about 50 Kusama Bot users and more than 10 Polkadot Bot users. We actually received positive feedbacks from both website and bot users.

### Feedbacks from the Community

We appreciate the feedbacks from the community, which encouraged us to make it better.
(先詢問，同意後再放上去)


## Problem statement: 

As Polkadot/Kusama are NPoS consensus based chains, nominators are able to nominate more than one validator, which makes staking procedire complicated. When users stake on most blockchains, they just need to choose one validator and delegate their funds to them. When staking on Polkadot/Kusama, they can (and mostly have to) choose up to 24 validators. It is hard for nominators to analyse so many validators to see which ones are trustworthy and are able to earn most revenue from them.

From our observation, nominators tends to

* nominate in centralized exchanges, which hurts decentralization.
* nominate top validators on the Target page on Polkadot App, which still hurt decentralization because by doing it, funds tend to be delegated to those already have enough backups.
* nominate only active validators, which also make funds gathered to those already have enough backups.

There are developers from the community trying to resolve the problem by providing validator ranking system and user friendly staking tools.

1. Yieldscan (https://yieldscan.app/)

The goal of Yieldscan is just as their slogan "built to maximize staking yield and designed to minimize effort". It helps nominators to maximize their profit from staking. They used a risk level system, in which users can simply input staking amount, risk level, and duration. The system chooses 16 validators which fulfill the conditions users set, estimates the APY and help users to nominate them. Yieldscan also has dashboards of both validators and nominators. It supports both Polkadot and Kusama.


2. Polkastats - Validator Resource Center (https://validatorsv2.kusama.polkastats.io/)

Polkastats is another similar project, it is a validator resource center. The site uses VRC score, which is calculated from varieties of parameters. They help nominators by providing a dashboard of validators, displaying info such as commission, self stake, etc. so that nominators have a baseline to compare each other. Polkastats also has a nomination system, which focused on the decentralization of the network. It has a unique feature that nominators can import their validator sets to customize the next sets of validators. It supports Kusama.

3. Staking tools in centralized exchanges / Auto staking service blockchains (e.g. https://stake.fish/en/)

Simple staking tools are offered by centralized exchanges, they are designed to make staking procedure as simple as a nominate button. There should be an auto staking management system behind these exchanges. The cons of using it are, first, the APY is worse because of service fee and second, it hurts decentralization. The pros and cons are similar when it comes to those blockchains which offers auto staking services.

However, we saw there are no complete *Portfolio Management* solutions for Polkadot/Kusama nominators to track their revenue from staking and validator status after nonimation. In our view, staking is not an one-time operation, it should be constantly monitored and adjusted to ensure profit. We saw no such solutions on the market now.

## Proposal Objective/solution/s to point 2:

We provide *Portfolio Benchmark* to help nominators to choose which validators to nominate. *Portfolio Management* to help nominators to monitor validator status so they can make adjustment just in time.

We have already provided some tools on CryptoLab and also Telegram bots and have some regular users. It is the time to polish the website and to work on providing a total solution for staking.

There are three top-tier goals included in this propsal.

1. Current CryptoLab website maintanence
2. CryptoLab Staking Tool
3. Telegram Bots for both Polkadot/Kusama nominators

The first two goals are focused on making what we have done better. We plan to enhance the current CryptoLab by

* Re-design the UI/UX of CryptoLab, including RWD.
* Move the service to AWS to improve the performance.
* Maintain our own Polkadot/Kusama archived nodes to improve the performance.

The goal 2. and 3. are what we are planning to do. 

### Portfolio Benchmark

In Portfolio Benchmark, we would like to help DOT/KSM holders to stake in a single step. It has two modes, simple and advanced.

Nominators first need to allow CryptoLab in Polkadot Browser Extension. The website would detect the amount of KSM/DOT in each account.

In simple mode, our goal is to make a one-button staking feature.

![image](https://user-images.githubusercontent.com/3665658/121618019-a494ff80-ca98-11eb-960e-5289fc15ce1a.png)

We offer several strategies to help users to select validators. The following table is the detailed description of these strategies.

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
| Commision  | Users may input the maximum commission |
| Identity   | Users may filter only validators with a verified identity |
| Unclaimed eras | Users may input the maximum unclaimed eras |
| Previous slashes | Users may filter only validators with no slashing records |
| Is Sub identity| Users may filter only validators which are not a sub identity |
| Historical APY(%)| Users may input the minimum historical APY in previous 84 eras | 
| Inclusion | Users may input the minimum era inclusion rate in previous 84 eras |
| Telemetry | Users may filter only validators which can be bound to a telemetry |

![image](https://user-images.githubusercontent.com/3665658/121617856-5da70a00-ca98-11eb-8c85-b8111761be2a.png)

They then could input how much funds they want to stake and they are able to select their reward destinations, there are three possible options the same as on the Polkadot App.

Once the validator list is generated and the reward destination is selected, nominators can press the Nominate button, and the Polkadot Browser Extension would popup to ask them to sign the transaction.

### Portfolio Management

In Portfolio Management, the CryptoLab would cover aspects such as revenue report, validator status notification and re-nomination. The goal is to help nominators to constantly monitor and ensure their profit via staking. 

There would have several pages in Portfolio Management, the first one is *Performance*.

![image](https://user-images.githubusercontent.com/5772463/121611370-abb51100-ca8a-11eb-8f0b-ceaba91b5850.png)

In Performance page, users are able to see

* a summary of their earnings from all accounts in their wallets. 
* a chart that shows their profit trend, users may choose different timespan to see the sum of their profit. 
* a detailed report of how much they earn through all eras, similar to the Staking Rewards Collector.
* re-nominate validators

CryptoLab would create a list of suggested validators according to the strategy they choose.  

The second one is unique, the Notification page

![image](https://user-images.githubusercontent.com/3665658/121618476-66e4a680-ca99-11eb-894b-3b6946a0a4d5.png)

In this page, users are able to see,

* historical events, up to 84 eras.
* setup CryptoBots on Telegram or on email.

These events would be recorded, and users can be notified on Telegram and email.

| event | description |
| ----- | ----------- |
| commission change | CryptoLab would create an event when validator commission is changed. |
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

so that nominators are able to make adjustment in time.

### Planned Service Architecture

Current CryptoLab is running on a single VPS, and retrieve data on-chain through either Parity or onFinality. There is still room for improvement. Retrieving validators and nominators data while listening to Payout events and saving them to a DB could be longer than 30 minutes. We plan to separate the processes to different instances and use the resource on AWS to improve the performance.

![image](https://user-images.githubusercontent.com/3665658/121481654-ecffdf00-c9fe-11eb-8667-012544da1385.png)

The servers is consist of two EC2 instances, one DB and one Redis instance, to operate the CryptoLab backend servers. We would also run two EC2 instances for Polkadot/Kusama node so that on-chain data could be retrieved faster.

### Who does this solution help?

We want to make staking simple so that DOT/KSM holders could choose to stake directly on chain instead of using wrapped solutions such as from centralized exchanges. Also, by providing an easy-to-understand view of validators, we want to ease the situation that most funds are gathered on a few validators to make the network more decentralized. Last but not least, we want to increase the chance for independent validators to be nominated.

### Milestones and tasks to include:

The milestones include 3 phases, we would send each milestone in separate proposals. The designer and developer cost are estimated as 1500 USD/week (full time)

#### Milestone 1. (11.5-week)

| Description | Man-power | Duration | Price | Deliverables |
| ----------- | --------- | -------- | ----- | ------------ |
| Re-design the UI/UX of CryptoLab     | Designer: 1 | 3 weeks | 4,500 USD | Mockup UI in Adobe Creative Cloud |
| Implement CryptoLab Portfolio Benchmark | Developers: 2 | 2 weeks | 6000 USD | Webpages for nominators to filter validators by different conditions so that they can nominate them. |
| Implement CryptoLab Portfolio Management | Developers: 2 | 4 weeks | 12000 USD | Webpages for nominators to monitor their revenue and validator status.  |
| Implement CryptoLab Staking Guide | Developers: 1 | 1 weeks | 1500 USD | Webpages to guide nominators to stake on CryptoLab. |
| Telegram Bots for nominators     | Developer: 1 | 1.5 weeks | 2250 USD | Telegram Bots for nominators, included features described in Portfolio Management. |

Total: 26250 USD

#### Milestone 2. (4-week)

| Description | Man-power | Duration | Price | Deliverables |
| ----------- | --------- | -------- | ----- | ------------ |
| RWD UI/UX of CryptoLab     | Designer: 1 | 1 weeks | 1,500 USD | Mockup UI in Adobe Creative Cloud for Phone and Tablet  |
| Implement RWD UI/UX of CryptoLab | Developers: 2 | 2 weeks | 6000 USD | CryptoLab on Phone and Tablet |
| DevOps for maintenance | Developers: 1 | 1 weeks | 1500 USD | Internal dashboard to display service status such as chain data last updated time, online/offline, bandwidth usage, etc. |

Total: 9000 USD

### Milestone 3. (3-week)
 
 In this stage, we would like to apply the new UI/UX on current CryptoLab webpages, including *Kusama/Polkadot Validator/Nominator Status*, *Validator Dashboard* and *Kusama/Polkadot One Thousand Validator Monitor*.
 
| Description | Man-power | Duration | Price | Deliverables |
| ----------- | --------- | -------- | ----- | ------------ |
| Re-design UI/UX of CryptoLab    | Designer: 1 | 1 weeks | 1,500 USD | Mockup UI in Adobe Creative Cloud |
| Implement Re-designed UI/UX of CryptoLab | Developers: 2 | 2 weeks | 6000 USD | Reworked webpages |

Total: 7500 USD

Except from the milestones above, the operation cost is another necessary expense for us to operate CryptoLab. 

The operation cost includes EC2 instances, DB and Redis instances, to run CryptoLab backend servers. We would also run two EC2 instances for Polkadot/Kusama node.

*We can provide the detailed estimation from AWS calculator if the commitee needs it*

The operation costs later than 6 months would be applied in future proposals if this one is being approved.


| Description | Duration | Price | Total | 
| ----------- | --------- | -------- | ----- |
| Operation cost for CryptoLab     | 6 months | 250 USD | 1500 USD |
| Operation cost for runnig Polkadot/Kusama Nodes | 6 months | 750 USD | 4500 USD |

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
* We proposed a total solution. Not only staking, but also allows users to monitor and manage their stakes after it.
* We support Telegram Bots to notify users just in time.

Teaching users is a challenging and high cost task, let alone we would like to change user behavior so that they are willing to support trustworthy validators, not just choose those who have higher APY. We hope that by doing it, we can make Polkadot/Kusama ecosystem much more stable and decentralized. Take the event in 5/24/2021, [Polkadot nodes failed with an out of memory (OOM) error on block 5,202,216.](https://polkadot.network/a-polkadot-postmortem-24-05-2021/). The network recovered soon because community node operators, especially those who joined the 1KV, took quick response. Thus we also provide a strategy to allow users to support 1kv operators.

## Payment conditions

Address: 

Total Payment: 48750 USD / 394.737 KSM = 123.5 KSM

* To calculate the price, we use Subscan's 30 avg tool at the day of submission:
Kusama: https://kusama.subscan.io/tools/charts?type=price (based on 6/9/2021)

* Treasury timeline related to milestones. We expect to have a report upon each milestone is done and online.

1st milestone: include development and 6-month operation cost. 

* Operation cost to be paid once the proposal is approved (6000 USD / 394.747 KSM ~= 15.2 KSM)

* Development cost To be paid to after the report is approved (26250 USD / 394.747 KSM ~= 66.5 KSM)

2nd milestone: to be paid to after the report is approved (9000 USD / 394.737 KSM ~= 22.8 KSM)

3rd milestone: to be paid to after the report is approved (7500 USD / 394.737 KSM ~= 19 KSM)

We would send proposals for each milestone once the previous milestone's final report is approved.

* Development work will start upon approval.

