# 🛡️ Security Audits Portfolio

## 🔓 Public Audits

| Project | From | To |  Platform | Vulns |
|:--------|:------:|:------:|:--------:|:-----------------|
| [BadgerDAO](https://cantina.xyz/competitions/f57ffb47-0ded-4f04-bcec-ecd7d47fad58) | 5 Mar 2025  | 12 Mar 2025 | [Cantina](https://cantina.xyz) | <ul><li>[H-1 Incorrect Decimal Handling in EbtcBSM Leads to Severe Exchange Rate Discrepancies](https://cantina.xyz/code/f57ffb47-0ded-4f04-bcec-ecd7d47fad58/findings/385)</li></ul> |
---

| Project | From | To | Platform | Vulns |
|:--------|:------:|:------:|:--------:|:-----------------|
| [Nudge](https://code4rena.com/audits/2025-03-nudgexyz) | 17 Mar 2025 | 24 Mar 2025 | [Code4rena](https://code4rena.com/) | <ul><li>[M-1 Lack of UUID Uniqueness Enforcement Leading to Campaign Spoofing & Data Corruption](https://code4rena.com/audits/2025-03-nudgexyz/submissions/S-737)</li></ul> |
---

## 🔒 Private Audits

| Project | From | To | Company | Vulns | Report |
|:--------|:------:|:------:|:--------:|:-----------------|:-----------------:|
| [Uniform Bidding Market](https://github.com/dindonero/UniformBiddingMarket) | 24 Mar 2025 | 4 Apr 2025 | [Nova IMS](https://www.novaims.unl.pt/) | <ul><li>[C-1 The _clearMarket function is subject to denial of service due to an unbounded number of bids and asks](https://github.com/dindonero/UniformBiddingMarket/issues/8)</li><li>[C-2 The _clearMarket function does not check for canceled bids causing them to be matched anyway](https://github.com/dindonero/UniformBiddingMarket/issues/4)</li><li>[C-3 Incorrect sorting in sortBids leads to a flawed clearing price and erroneous settlement between bids and asks](https://github.com/dindonero/UniformBiddingMarket/issues/3)</li> <br /> <li>[H-1 Bids that weren't supposed to be matched are matched in the _clearMarket function, causing bidders to lose their funds](https://github.com/dindonero/UniformBiddingMarket/issues/5)</li><li>[H-2 Using transfer for native ETH withdrawals can prevent users from recouping their funds](https://github.com/dindonero/UniformBiddingMarket/issues/10)</li> <br /> <li>[L-1 Missing _disableInitializers in EnergyBiddingMarket's constructor](https://github.com/dindonero/UniformBiddingMarket/issues/6) </li><li>[L-2 There is no way to undo the whitelisting of a seller](https://github.com/dindonero/UniformBiddingMarket/issues/7) </li><li>[L-3 Truncation in placeBid function is retained by the contract](https://github.com/dindonero/UniformBiddingMarket/issues/11)</li><li>[L-4 Bulk Bid Residuals in Multi-Hour Bidding](https://github.com/dindonero/UniformBiddingMarket/issues/12)</li><li>[L-5 Array-Based Bulk Bid Residuals](https://github.com/dindonero/UniformBiddingMarket/issues/14)</li> <br /> <li>[I-1 Unused whitelistedSeller modifier](https://github.com/dindonero/UniformBiddingMarket/issues/9)</li><li>[I-2 Unnecessary repeated calls to assertExactHour modifier when placing bids](https://github.com/dindonero/UniformBiddingMarket/issues/13)</li><li>[I-3 Unnecessary getClearingPrice function](https://github.com/dindonero/UniformBiddingMarket/issues/15)</li><li>[I-4 Lack of address(0) sanity check in whitelistSeller function](https://github.com/dindonero/UniformBiddingMarket/issues/16)</li><li>[I-5 Lack of event emission for state change in whitelistSeller function](https://github.com/dindonero/UniformBiddingMarket/issues/17)</li><li>[I-6 Unnecessary balanceOf function](https://github.com/dindonero/UniformBiddingMarket/issues/18)</li><li>[I-7 Missing bid existence checks in cancellation functions](https://github.com/dindonero/UniformBiddingMarket/issues/19)</li></ul> | [report-UniformBiddingMarket.pdf](Reports/report-UniformBiddingMarket.pdf)

---
