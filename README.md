# cryptolab-staking-treasury-proposal

# Proposal

## Title

CryptoLab

## Short description:

The CryptoLab aims to help non-technical nominators build stable and risk-controlled cash flows via well-designed and financial tools. The core idea is that staking behavior is the same as investment behavior. Therefore nominators must first build good portfolios and then manage their portfolios to control risk and profit. Portfolio management is a challenging task, especially in the complicated Kusama system using NPoS consensus. 

CryptoLab website 是圍繞於財務管理的視角來設計，從基本的用詞簡字，到數據呈現皆力求平易近人，簡單明暸。我們提供三個主要的服務：1. Portfolio Benchmark, 2. Portfolio Management, 3. Nofitication Bot. 首先，Portfolio Benchmark 是一種validator評估工具，Nominators可以使用預先建制的幾種選擇策略，如：High APY, Low Risk, 1KV, Decentrailization, etc.,來建立Portfolio. 然而這僅僅是踏出第一步而已，更重要的是持續調整 Portfolio的能力。 所以我們提出市場上少見的 Protfolio Management 讓使用者得以快速且精確的了解現金流狀況，再搭配 Notification Bot 事件通知功能，即時掌握驗證者狀況，並作出調整，以降低風險。

最後，Decentralization絕對是Kusama生態系一個至關重要的議題。我們相信 CryptoLab Website 可以協助 Nominators 獲得穩定收益的同時兼顧Decentralization，打破現在 validator 過度集中的現象。

## Context of the proposal: 

CryptoLab最初是以作為 validator 來切入 Kusama 生態系，過程中我們一邊驚訝於進入門檻太高，ㄧ邊苦於幾乎沒有金融相關工具可使用。舉例來說，作為一個 validator 而言，投入前必須事先評估未來金流的長相，才能營運降低風險，然而卻找不到相關工具及資訊。不僅如此，對於 Nominator 而言，市面上的APY評估工具，僅僅是先確定好公式及參數的靜態工具，幾乎沒有參考價值，而 Polkadot Portal App又太過於複雜，不容易使用。我們注意到另一個更嚴重的問題是 validator 過度集中化，非機構 validator 幾乎沒辦法取得足夠的提名，進入active set。這是一個幾乎無解的現況，因為無法進入active set就吸引不到提名，吸引不到提名就進不了active set。

因此，我們利用空閑時間開始替自己打造相關工具，並分享給社群使用，如：Validator/Nominator Status、Staking Rewards、1kv validator monitor，可以更容易地評估staking收益與提名狀況。我們也推出 staking tool，其特色是簡單操作的提名流程，並包含隨機的1kv validator節點，期待減緩集中化的問題。身為 validator 營運者，我們必須時時注意提名狀況來調整commission，因此推出 telegram bot 即時收到提名事件，這大幅將低validator的工作量。 在這期間，我們總共取得三個 tips(感謝 Raul 的推薦)，也收到多個社群夥伴的鼓勵與回饋，非常開心。基於上述的經驗與鼓舞，我們有信心可以做出更好用的服務，是時候向前跨出一大步了。

(介紹團隊)

(社群鼓勵與回饋)

we aim to have as much context as possible to understand how a proposal came to the proponent's mind, Please include here:

 * any points discussed in advance in any channel related to the proposal and background research for your project. 
 * background of the proponent, team credentials. 
 * their motivation (including any conflict of interests or association to any governing bodies)
 * any known backups already behind the solution (known token holders, organizations or collectives building on Kusama Network or participating in its governance mechanism in any way).

## Problem statement: 

As Polkadot/Kusama are NPoS consensus based chains, nominators are able to nominate more than one validator, which makes staking on them complicated. When users stake on most blockchains, they just need to choose one validator and delegate their funds to them. When staking on Polkadot/Kusama, they can (and mostly have to) choose up to 24 validators. It is hard for nominators to analyse so many validators to see which ones are trustworthy and are able to earn most revenue from them.

From our observation, nominators tends to

* nominate on centralized exchanges, which hurts decentralization.
* nominate top validators on the Target page on Polkadot App, which still hurt decentralization because by doing it, funds tend to be delegated to those already have enough backups.

There are developers from the community trying to resolve the problem by providing validator ranking system and simple staking tools.

1. yieldscan (補充yieldscan在做什麼)
2. polkastats (補充polkastats做了什麼)

However, no *Portfolio Management* tools for Polkadot/Kusama nominators to track their staking revenue and validator status after nonimation.

## Proposal Objective/solution/s to point 2:

CryptoLab aims to provide a total solution for staking on Polkadot/Kusama.

We have already provided some tools on CryptoLab and also Telegram bots and have some regular users. It is time to polish the site and to work on providing a total solution on staking.

There are four top-tier goals included in this propsal.

1. Current CryptoLab website maintanence
2. Telegram Bots for both Polkadot/Kusama validators maintanence
3. CryptoLab Staking Tool
4. Telegram Bots for both Polkadot/Kusama nominators

The first two goals are focused on making what we have done better. We plan to enhance the current CryptoLab by

* Re-design the UI/UX of CryptoLab
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
    
Except from the milestones above, server fee is another necessary expense for us to operate CryptoLab. 

The server fee includes EC2 instances, DB and Redis instances, to run CryptoLab backend servers. We would also run two EC2 instances for Polkadot/Kusama node.

*We can provide the detailed estimation from AWS calculator if the commitee need it*

* Duration: 6 months
* Price: 1000 USD/month



### Include any extra links completing the proposal here

## Why Kusama? 

## If you have seen similar proposals before: why is yours different?

https://kusama.polkassembly.io/treasury/82

https://kusama.polkassembly.io/treasury/90

## Payment conditions
