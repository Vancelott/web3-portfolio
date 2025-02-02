# Summary

This is a simple summary of the bugs that I've found as a Web3 security researcher in public audit contests.

| Contest                                                                                                 | Platform  | Findings    | Date    | Finding/s                                                                       |
| :------------------------------------------------------------------------------------------------------ | :-------- | :---------- | ------- | :----------------------------------------------------------------------------- |
| [Panoptic](https://code4rena.com/audits/2024-04-panoptic)                                               | Code4rena | 1 Medium    | 04.2024 | [slot0 is used in two function which could easily be manipulated](https://github.com/code-423n4/2024-04-panoptic-findings/issues/30)      |
| [Noya](https://code4rena.com/audits/2024-04-noya) | Code4rena | 1 Medium | 04.2024 | [Missing updates to the accounting of the registry in addColl](https://github.com/code-423n4/2024-04-noya-findings/issues/1196)
| [xKeeper](https://audits.sherlock.xyz/contests/248) | Sherlock | 1 Low* | 04.2024 | [Function values imported from EnumerableSet will cause out of gas issues](https://github.com/sherlock-audit/2024-04-xkeeper-judging/issues/144)
| [Predy](https://code4rena.com/audits/2024-05-predy)** | Code4rena | 1 High, 1 Medium | 05.2024 | - [Spot price is used for in-range liquidity reallocation, resulting in liquidity manipulation](https://github.com/code-423n4/2024-05-predy-validation/issues/660) <br> - [Liquidity manipulation is possible when trading](https://github.com/code-423n4/2024-05-predy-findings/issues/157)
| [MagicSea](https://audits.sherlock.xyz/contests/437) | Sherlock | 1 Medium, 1 Low* | 07.2024 | - [Optional function decimals can cause deployment issues in MlumStaking](https://github.com/sherlock-audit/2024-06-magicsea-judging/issues/148) <br> - [Incorrect calculation for PRECISION_FACTOR](https://github.com/sherlock-audit/2024-06-magicsea-judging/issues/144)
| [Traitforge](https://code4rena.com/audits/2024-07-traitforge)** | Code4rena | 2 Medium | 07.2024 | - [User can mint the "Golden God” NFT without any difficulty](https://github.com/code-423n4/2024-07-traitforge-findings/issues/401) <br> - [Functions Pause and Unpause aren't implemented in any contract](https://github.com/code-423n4/2024-07-traitforge-findings/issues/546)

\* Sherlock does not consider low severity issues as valid issues for a payout, but I've decided to include my findings that were downgraded from a H/M <br>
\** I particpiated in this audit as a [team](https://code4rena.com/@yunaci) with @[cholakovv](https://github.com/cholakovvv) 🤝
