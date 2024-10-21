# Event Classifiers Schemes

Collection of **matchers for actions** (like token transfer or deposit) for TON Blockchain indexer.
Used to recognize and classify transactions' types by TON Center's [event classifier](https://toncenter.com/api/v3/index.html#/events/api_v3_get_actions).

## Existing matchers:

#### Jettons:
- [x] Jetton Transfer
- [x] Jetton Mint
- [x] Jetton Burn

#### NFT:
- [x] NFT Mint
- [x] NFT Transfer

#### DeFi:
- [x] Stonfi V1 Swap
- [x] Stonfi V2 Swap
- [ ] Stonfi V2 Provide Liquidity
- [ ] Stonfi V2 Withdraw Liquidity
- [x] Dedust V2 Swap
- [x] Dedust V2 Provide Liquidity
- [ ] Dedust V2 Withdraw Liquidity

#### Extensions:
- [x] Subscribe
- [x] Unsubscribe

#### DNS/Telegram:
- [x] DNS Auction Bid
- [x] Telegram NFT Purchase
- [x] Change DNS Record

#### Elector:
- [x] Deposit Stake
- [x] Recover Stake

#### Tonstakers:
- [ ] [Deposit Request](schemes/tonstakers-deposit-request.json)
- [ ] [Withdraw Request](schemes/tonstakers-withdraw-request.json)
