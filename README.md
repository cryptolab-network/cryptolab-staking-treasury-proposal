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

團隊完整性直接影響一個專案的品質，我們相當清楚目前 CryptoLab website 的不足之處，因此為了提供更好的使用者體驗與服務，我們從一開始的兩人團隊擴充為四人，增加一名UI/UX Designer (Kin Lau)與一名fullstack資深工程師 (Jack)。團隊成員都有豐富的研發經驗，且都了解區塊鏈領域，這讓我們有十足的信心完成此專案。

(以下大家寫一些區塊鏈、技術相關經驗、作品也很好)
* Yao-hsin Chen 從2016年就開始研究區塊鏈技術，是Taipei Ethereum Meetup Organizer之一。於2018年共同創辦SOLA Technology公司，並擔任CEO至2020年底，致力於將區塊鏈技術推廣至新能源領域。從2021年開始專心投入營運Polkadot/Kusama validator，並籌組 CryptoLab 團隊。
* Yu-kai Tseng, who has 9-year experience on developing Industrial Ethernet Network Management System, is now freelancer. He is expert in distributed network service design and development and began to work on the first version of CryptoLab in 2021.
* Kin
* Jack

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


2. polkastats (https://validatorsv2.kusama.polkastats.io/)

Polkastats is another similar project, it is a validator resource center. The site uses VRC score, which is calculated from varieties of parameters. They help nominators by providing a dashboard of validators, displaying info such as commission, self stake, etc. so that nominators have a baseline to compare each other. Polkastats also has a nomination system, which focused on the decentralization of the network. It has a unique feature that nominators can import their validator sets to customize the next sets of validators. It support Kusama.

3. Staking tools in centralized exchanges / Auto staking service blockchains (e.g. https://stake.fish/en/)

Simple staking tools are offered by centralized exchanges, they are designed to make staking procedure as simple as a nominate button. There should be an auto staking management system behind these exchanges. The cons of using it are, first, the APY is worse because of service fee and second, it hurts decentralization. The pros and cons are similar when it comes to those blockchains which offers auto staking services.

However, we saw there are no complete *Portfolio Management* solutions for Polkadot/Kusama nominators to track their revenue from staking and validator status after nonimation. In our view, staking is not an one-time operation, it should be constantly monitored and adjusted to ensure profit. We saw no such solutions on the market now.

## Proposal Objective/solution/s to point 2:

(加一段說明 total solution 投前 投後)
我們將完整的Staking解決方案分成兩大部分，首先 Portfolio Benchmark 解決 validators 難以評估的問題，讓 Nominator 能夠順利完成提名。接著是 Portfolio Management，幫助 Nominator 持續追蹤validator表現狀況，並提供主動式通知的功能，以便隨時調整提名。後續將以我們重新設計的介面，逐一介紹目前規劃的每一個功能。

We provide *Portfolio Benchmark* to help nominators to choose which validators to nominate. *Portfolio Management* to help nominators to monitor validator status so they can make adjustment just in time.

We have already provided some tools on CryptoLab and also Telegram bots and have some regular users. It is the time to polish the website and to work on providing a total solution for staking.

There are four top-tier goals included in this propsal.

1. Current CryptoLab website maintanence
2. Telegram Bots for both Polkadot/Kusama validators maintanence
3. CryptoLab Staking Tool
4. Telegram Bots for both Polkadot/Kusama nominators

The first two goals are focused on making what we have done better. We plan to enhance the current CryptoLab by

* Re-design the UI/UX of CryptoLab, including RWD.
* Move the service to AWS to improve the performance.
* Maintain our own Polkadot/Kusama archived nodes to make the performance better.

For the Telegram Bots for validators, we plan to,

* (Maintanence and add more features to it)

The goal 3. and 4. are what we are planning to do. 

### Portfolio Benchmark

In Portfolio Benchmark, we would like to help DOT/KSM holders to stake in a single step. It has two modes, simple and advanced.

Nominators first need to allow CryptoLab in Polkadot Browser Extension. The website would detect the amount of KSM/DOT in each account.

In simple mode, our goal is to make a one-button staking feature.

![image](https://user-images.githubusercontent.com/5772463/121184696-ed319a80-c897-11eb-93e3-3285c705f6fa.png)

We offer several strategies to help users to select validators. The following table is the detailed description of these strategies.

| Strategy | Description |
| -------- | ----------- |
| Low risk | In this mode, we select validators with <br/> <ul><li> self stake >= 50 KSM or 1000 DOT </li><li>has a verified identity</li><li>unclaimed eras < 16</li><li>no slash</li><li>can be bound to a telemetry node</li></ul> |
| High APY | In this mode, we select validators with <br/> <ul><li>Highest average APY in recent 84 eras</li></ul> |
| Decentralization | In this mode, we select validators with <br/><ul><li>Highest average APY in recent 84 eras</li><li>has a verified identity</li><li>but if an identity contains multiple sub identities, only one among them would be selected</li></ul> |
| One Thousand Validator Program| In this mode, we select validators with <br/><ul><li>is active in either Polkadot/Kusama One Thousand Validator Program</li><li>we would also use the current strategy to choose from 1kv validators to maximize the chance that at least one of the node is active</li></ul> |

In the advanced mode, users may set their own threshold to filter validators. Then they can select up to 24 validators in Kusama and 16 validators in Polkadot to nominate.

The following are the conditions we would like to take into account when we select validators.

| Conditions | Description|
| ---------- | ---------- |
| Self Stake | Users may input the minimum self stake |
| Commision  | Users may input the maximum commission |
| Identity   | Users may filter only validators with an identity |
| Unclaimed eras | Users may input the maximum unclaimed eras |
| Previous slashes | Users may filter only validators with no slashing records |
| Is Sub identity| Users may filter only validators which are not a sub identity |
| Historical APY(%)| Users may input the minimum historical APY in previous 84 eras | 
| Inclusion | Users may input the minimum era inclusion rate in previous 84 eras |
| Telemetry | Users may filter only validators which can be bound to a telemetry |

![image](https://user-images.githubusercontent.com/5772463/121305770-93c97a00-c930-11eb-953f-9a8ef607aa12.png)

They then could input how much funds they want to stake and they are able to select their reward destinations, there are three possible options the same as on the Polkadot App.

Once the validator list is generated and the reward destination is selected, nominators can press the Nominate button, and the Polkadot Browser Extension would popup to ask them to sign the transaction.

### Portfolio Management

### Telegram Bots for nominators


For the Telegram Bots for nominators, we plan to provide the followings,

* Notify users when a validator commission is changed.
* Notify users when a validator is slashed.
* Notify users when all validators they selected are inactive.
* Regular revenue reports

so that nominators are able to make adjustment in time.

### Planned Service Architecture

![image](https://user-images.githubusercontent.com/5772463/121299862-97f19980-c928-11eb-9598-d7842ef30a9c.png)

The servers includes EC2 instances, one DB and one Redis instance, to operate CryptoLab backend servers. We would also run two EC2 instances for Polkadot/Kusama node.

### How does this proposal change the current logic in Kusama?

### Who does this solution help?

We want to make staking simple so that DOT/KSM holders could choose to stake directly on chain instead of using wrapped solutions such as from centralized exchanges. Also, by providing an easy-to-understand view of validators, we want to ease the situation that most funds are gathered on a few validators to make the network more decentralized. Last but not least, we want to increase the chance for independent validators to be nominated.

### Milestones and tasks to include:

The milestones include 3 phases, we would send each milestone in separate proposals. The designer and developer cost are estimated as 1500 USD/week (full time)

#### Milestone 1. (10-week)

| Description | Man-power | Duration | Price | Deliverables |
| ----------- | --------- | -------- | ----- | ------------ |
| Re-design the UI/UX of CryptoLab     | Designer: 1 | 3 weeks | 4,500 USD | Mockup UI in Adobe |
| Implement CryptoLab Portfolio Benchmark | Developers: 2 | 2 weeks | 6000 USD | Webpages for nominators to filter validators by different conditions so that they can nominate them. |
| Implement CryptoLab Portfolio Management | Developers: 2 | 4 weeks | 12000 USD | Webpages for nominators to monitor their revenue and validator status.  |
| Implement CryptoLab Staking Guide | Developers: 1 | 1 weeks | 1500 USD | Webpages to guide nominators to stake on CryptoLab. |

Total: 18000 USD

#### Milestone 2. (4.5-week)

| Description | Man-power | Duration | Price | Deliverables |
| ----------- | --------- | -------- | ----- | ------------ |
| RWD UI/UX of CryptoLab     | Designer: 1 | 1 weeks | 1,500 USD | Mockup UI in Adobe for Phone and Tablet  |
| Implement RWD UI/UX of CryptoLab | Developers: 2 | 2 weeks | 6000 USD | CryptoLab on Phone and Tablet |
| Telegram Bots for nominators     | Developer: 1 | 1.5 weeks | 2250 USD | Telegram Bots for nominators, included features described in Portfolio Management. |

Total: 9750 USD

### Milestone 3. (3-week)
 
 In this stage, we would like to apply the new UI/UX on current CryptoLab webpages, including *Kusama/Polkadot Validator/Nominator Status*, *Validator Dashboard* and *Kusama/Polkadot One Thousand Validator Monitor*.
 
| Description | Man-power | Duration | Price | Deliverables |
| ----------- | --------- | -------- | ----- | ------------ |
| Re-design UI/UX of CryptoLab    | Designer: 1 | 1 weeks | 1,500 USD | Mockup UI in Adobe |
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

https://kusama.polkassembly.io/treasury/82

https://kusama.polkassembly.io/treasury/90

## Payment conditions

Address: 

Total Payment: 47250 USD / 394.737 KSM = 119.7 KSM

* To calculate the price, we use Subscan's 30 avg tool at the day of submission:
Kusama: https://kusama.subscan.io/tools/charts?type=price (based on 6/9/2021)

* Treasury timeline related to milestones. We expect to have a report upon each milestone is done and online.

1st milestone: include development and 6-month operation cost. 

Operation cost to be paid once the proposal is approved (6000 USD / 394.747 KSM ~= 15.2 KSM)
Development cost To be paid to after the report is approved (24000 USD / 394.747 KSM ~= 60.8 KSM)

2nd milestone: to be paid to after the report is approved (9750 USD / 394.737 KSM ~= 24.7 KSM)

3rd milestone: to be paid to after the report is approved (7500 USD / 394.737 KSM ~= 19 KSM)

We would send proposals for each milestone once the previous milestone's final report is approved.

* Development work will start upon approval.

