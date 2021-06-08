# cryptolab-staking-treasury-proposal

# Proposal

## Title

CryptoLab

## Short description:

The CryptoLab (https://www.cryptolab.network/tools) aims to help non-technical nominators build stable and risk-controlled cash flows via well-designed and financial tools. The core idea is that we want to make staking the same as investment. We help nominators to build good portfolios and to manage their portfolios to control risk and revenue. Portfolio management is challenging in Polkadot/Kusama system because they are NPoS consensus.

We design the CryptoLab website to help users to do their crypto currency financial management. From basic wordings to data representation, we would like to make "normal" people comprehensive. (對於那些族群comprehensive?) In the first stage, We plan to provide the following features,

* Portfolio Benchmark
* Portfolio Management

Portfolio Benchmark helps nominators to evaluate which validators should they stake on. They can simply choose and nominate from our pre-built strategies or set their own conditions on different criteria to get a list of validators. And it is just the first step.

The real difference that makes CryptoLab outstanding is the Portfolio Management. We would like to help nominators to track their revenue and to suggest new sets of validators accoring to the criteria they set. We also would like to help nominators to make adjustment in time to prevent from lose their profit, by notify them such as when a validator increased commission or when a validator is slashed.

Decentralization is the key to make long term Polkadot/Kusama ecosystem healthy. Our topmost goal is to help nominators to get stable income while keep the system dencentralized.

## Context of the proposal: 

We first acted as Kusama validators to cut in to the ecosystem. We found that the entry barrier was quite high. For example, to lower the risk, as a validator, we would like to estimate how much funds we need, and what is the revenue after we start operating. However, we can't find any tool to help us, there were indeed some APY estimation tools on the web but they were just static not useful at all. The only choice was the Polkadot App but it was complicated and still lacks of necessary information such as long-term APY. Another problem is that personal operators were nearly impossible to get enough backup to be consistently active. Operators are hard to be nominated if they were not in the active set, and they can't be in the active set because they are hard to be nominated.

As a result, we developed tools for ourselves in our free time and shared the tools to the community. We have already developed some useful tools such as Polkadot/Kusama validator dashboards, Staking Rewards Reports and Telegram Bots to notify validators about staking status and telemetry status. We received three tippings from both councils and got positive feedbacks from the community as well which encouraged us to keep going on.

We believe that it is time for us to make a big step, to provide a total solution for Polkadot/Kusama staking.

### The Team

團隊完整性直接影響一個專案的品質，我們相當清楚目前 CryptoLab website 的不足之處，因此為了提供更好的使用者體驗與服務，我們從一開始的兩人團隊擴充為四人，增加一名UI/UX Designer (Kin Lau)與一名fullstack資深工程師 (Jack)。團隊成員都有豐富的研發經驗，且都了解區塊鏈領域，這讓我們有十足的信心完成此專案。

(以下大家寫一些區塊鏈、技術相關經驗、作品也很好)
* Yao-hsin Chen 從2016年就開始研究區塊鏈技術，是Taipei Ethereum Meetup Organizer之一。於2018年共同創辦SOLA Technology公司，並擔任CEO至2020年底，致力於將區塊鏈技術推廣至新能源領域。從2021年開始專心投入營運Polkadot/Kusama validator，並籌組 CryptoLab 團隊。
* Yu-kai Tseng
* Kin
* Jack

### 使用者數據分析

CryptoLab上線日期為2021/3/13，目前只有在官方element上宣傳，累積使用人數為629人，平均停留時間為3分鐘，使用者來自United States, China, Italy, Germany, Taiwan, Spain, United Kingdom等地區。最近一個月的使用者人數為212人，其中新使用者人數為178人，回訪人數有76人。每日訪問人數介於8~38人次。有59.7%透過桌面版瀏覽器訪問，而行動裝置佔比則為40.3%。以上數據顯示CryptoLab取得不錯的回訪率成績42.6%，這表示接近一半的使用者覺得CryptoLab為他們提供了價值。另外明顯可以改善的地方為支援RWD顯示，因為有4成的使用者是透過行動裝置來瀏覽。以下為Google Analytics截圖。

<img src="https://user-images.githubusercontent.com/3665658/121117953-930ae800-c84b-11eb-87aa-8d5ce83463f2.png" width="350">
<img src="https://user-images.githubusercontent.com/3665658/121118013-b03fb680-c84b-11eb-9d17-6fe10066ee5a.png" width="350">
<img src="https://user-images.githubusercontent.com/3665658/121118081-d2393900-c84b-11eb-8c74-1848a049493c.png" width="350">
<img src="https://user-images.githubusercontent.com/3665658/121118168-f9900600-c84b-11eb-9cde-01d371df5fcc.png" width="350">

我們分別於2021/4/6及2021/5/22推出 Telegram Kusama Bot及 Polkadot Bot 來協助validator取得即時提名訊息及節點運行狀況，目前Kusama Bot使用者人數為48人，總共監控104個validator與38個telemetry狀態。Polkadot Bot使用者人數為14人，總共監控25個validator與9個telemetry狀態。此成績算是差強人意，但是根據我們收到的回饋，可以肯定此服務的確讓 validator 更了解節點維運狀況。

### 社群鼓勵及回饋

我們非常感謝社群同伴的鼓勵及回饋，讓 CryptoLab 更加茁壯。以下節錄一些私人的反饋，因為這些對我們而言更加有價值。

![image](https://user-images.githubusercontent.com/3665658/121129877-2b12cc80-c860-11eb-97a1-69f96d332d78.png)
![image](https://user-images.githubusercontent.com/3665658/121129904-3534cb00-c860-11eb-86e0-b4a80f154418.png)
![image](https://user-images.githubusercontent.com/3665658/121129949-4251ba00-c860-11eb-9237-31c09d0f5ac2.png)
![image](https://user-images.githubusercontent.com/3665658/121129991-53023000-c860-11eb-8275-5f1c7c34c446.png)
![image](https://user-images.githubusercontent.com/3665658/121130010-5b5a6b00-c860-11eb-9241-2658e7ed2296.png)
![image](https://user-images.githubusercontent.com/3665658/121130062-6c0ae100-c860-11eb-94d2-8c1a73533465.png)


## Problem statement: 

As Polkadot/Kusama are NPoS consensus based chains, nominators are able to nominate more than one validator, which makes staking on them complicated. When users stake on most blockchains, they just need to choose one validator and delegate their funds to them. When staking on Polkadot/Kusama, they can (and mostly have to) choose up to 24 validators. It is hard for nominators to analyse so many validators to see which ones are trustworthy and are able to earn most revenue from them.

From our observation, nominators tends to

* nominate in centralized exchanges, which hurts decentralization.
* nominate top validators on the Target page on Polkadot App, which still hurt decentralization because by doing it, funds tend to be delegated to those already have enough backups.

There are developers from the community trying to resolve the problem by providing validator ranking system and simple (改成 user friendly?) staking tools.

1. yieldscan (補充yieldscan在做什麼)
他的目標就如同 slogan 一樣， built to maximize staking yield and designed to minimize effort，以幫助 nominator 最大化staking為主要目標。其主要的特色是提出一個 risk level 的公式，計算每個 validator 的risk值，並歸類成 Low、Medium、High三大類。Nominator可以簡單輸入 amount, risk level, time peroid之後，系統會自動選取前16個滿足條件的validator，估算其年化報酬率(APY)，並讓使用者可以完成提名。另外也整理Validators、Nominators、Governance的基本資料以供查詢。Yieldscan支援 Polkadot/Kusama network.

2. polkastats (補充polkastats做了什麼)
Polkastats - Validator Resource Center，提出VRC score，考慮更多參數，並提供nominator客製化參數的功能。感覺上他們更重視 decentralization 程度，。主頁首先是統計全網資訊如 Average commission、 average self stake、average performance等等，讓nominator有個比較validator優劣的基準。Ranking頁面上方建議使用者提名 Featured waiting validator，讓使用者不僅僅考慮APY而已，也對網路去中心化做出貢獻。另外值得一提的是他們準備提供 Import 功能，讓已經提名的nominator匯入現有的validator set，然後再來進行調整。

However, no complete *Portfolio Management* tools for Polkadot/Kusama nominators to track their staking revenue and validator status after nonimation. 整個 staking 過程不是一次性的動作，而是一種需要不斷調整的流程，才能達到預期目標。現階段市面上並不存在完整Solution。

## Proposal Objective/solution/s to point 2:

We have already provided some tools on CryptoLab and also Telegram bots and have some regular users. It is time to polish the site and to work on providing a total solution on staking.

There are four top-tier goals included in this propsal.

1. Current CryptoLab website maintanence
2. Telegram Bots for both Polkadot/Kusama validators maintanence
3. CryptoLab Staking Tool
4. Telegram Bots for both Polkadot/Kusama nominators

The first two goals are focused on making what we have done better. We plan to enhance the current CryptoLab by

* Re-design the UI/UX of CryptoLab (加入RWD)
* Move the service to AWS to improve the performance
* Maintain our Polkadot/Kusama archived node

For the Telegram Bots for validators, we plan to,

* (Maintanence and add more features to it)

The goal 3. and 4. are what we are planning to do. 

For the CryptoLab Staking Tool, we plan to,

* Design and develop Portfolio Benchmark web page to provide simple and advanced staking tools.
* Design and develop Portfolio Management web page for nominators to track (things) such as revenue, validator status and more.

For the Telegram Bots for nominators, we plan to provide the followings,

* Notify users when a validator commission is changed.
* Notify users when a validator is slashed.
* Notify users when all validators they selected are inactive.
* Regular revenue reports

so that nominators are able to make adjustment in time.

### How does this proposal change the current logic in Kusama?

### Who does this solution help?

### Milestones and tasks to include:


The milestones include (x) phases,

#### Milestone 1.

* Re-design the UI/UX of CryptoLab
    * Designer: 1, Developers: 1
    * Duration: y weeks
    * Price: x USD * y = z USD
* Implement CryptoLab Portfolio Benchmark
    * Developers: 3
    * Duration: y weeks
    * Price: x USD * y = z USD
* Implement CryptoLab Portfolio Management
    * Developers: 3
    * Duration: y weeks
    * Price: x USD * y = z USD
* Implement CryptoLab Staking Guide
    * Developers: 1
    * Duration: y weeks
    * Price: x USD * y = z USD

#### Milestone 2.

* Telegram Bots for nominators
    * Developers: 1
    * Duration: y weeks
    * Price: x USD * y = z USD

### Milestone 3.
 
* Apply the redeigned UI/UX to existing features
    * Developers: 1
    * Duration: y weeks
    * Price: x USD * y = z USD
    
Except from the milestones above, the server fee is another necessary expense for us to operate CryptoLab. 

The server fee includes EC2 instances, DB and Redis instances, to run CryptoLab backend servers. We would also run two EC2 instances for Polkadot/Kusama node.

*We can provide the detailed estimation from AWS calculator if the commitee needs it*

The operation costs later than 6 months would be applied in future proposals if this one is being pproved.

* Duration: 6 months
* Price: 1000 USD/month



### Include any extra links completing the proposal here

## Why Kusama? 

## If you have seen similar proposals before: why is yours different?

https://kusama.polkassembly.io/treasury/82

https://kusama.polkassembly.io/treasury/90

## Payment conditions
