# DeFiHackathon
## Inspiration
DeFi lending protocols are used mostly by speculators. In order to make these products useful for the unbanked, we need to lower collateralization requirements via a decentralized reputation system that doesn't rely on KYC.

## What it does
We aim to aggregate the DeFi credit history of users and provide them with a reputation token (essentially a credit score) based on their past DeFi borrowing behavoir. This reputation token can then be used to bootstrap reputation for users without a DeFi credit history via social staking. Users that already have a history of using DeFi protocols will be given reputation tokens based on their historical DeFi transactions / borrowing behavior. These users will then be able to stake their reputation tokens on new users without prior DeFi credit history. If enough established users stake for a new user, that user can access credit at a lower collateral requirement, improving capital efficiency and onboarding new users into the DeFi ecosystem. When a loan is paid back, stakers will receive more reputation tokens as well a proportion of the monetary benefit resulting from better capital efficiency. However, if the borrower is liquidated, the stakers will be slashed, lowering their balance of reputation tokens (their credit score.) Our project is different from other reputation projects in that it aggregates borrowing behavoir across lending protocols, it does not require KYC, the credit history is based entirely on past DeFi transactions and / or social staking, and the goal is to lower over-collateralization requirements.

## How we built it
We used React, Javascript, and integrated with AAVE platform to aggregate data.

## Challenges we ran into
Smart contract integration.

## Accomplishments that we're proud of
3rd place for AAVE challenge during SFBW DeFi Hackathon 2019

## What we learned
Blockchain integration is hard. Proper incentive design takes a lot of time and thought.

## What's next for DefiningDeFi
Building the staking feature. Ultimately, a rlobust credit underwriting model based on DeFi credit history needs to be developed and we would need to further research what the appropriate score adjustment relative to staking would be.
