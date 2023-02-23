# 3.0.2 (2023-02-21)

Refactored Order service
Improved performance

# 3.0.1 (2023-02-21)

Launched v3

# 2.5.4 (2022-11-04)

Multi-node sell/buy

Split buy/sell to separate dedicated nodes

Impletended Modded Geth Nodes

# 2.5.1 (2022-09-07)

Fixes for HP checker USD pairs

Fixed Sell token UI issue

Fixed Custom Router param missing

Improved connection pool logic

# 2.5.0 (2022-08-31)

Added Multi swap

Added Contract addon

Various fixes

Refactored GraphQL API for better scaling

Added DogeChain

Refactored Hp Checker contract from scratch to work on all chains/swaps

# 2.2.2 (2022-07-30)

Added profiles
# 2.2.1 (2022-07-28)

Improved Mempool max drop functionality (support for multicall in ETH)

# 2.2.0 (2022-07-27)

Added gas cost calculations in UI

Added Buy Delay

Presale sniper API

Trailing stop-loss is now absolute value (if you set 10% and your current max is 300%, it will sell at 290% intead of 10% of 300%)

BSC node improvements

Various Improvements


# 2.1.3 (2022-07-17)

Multiple misc fixes

# 2.1.0 (2022-07-12)

Added Referrals UI and claim logic

Revampled Orders listing and added filtering

Added Approve Function

Added Auto Gas Limit

Multiple misc fixes


# 2.0.13 (2022-06-29)

Added Charting API - Initial support

# 2.0.12 (2022-06-29)

Added Telegram Logout

Added title value % in order details

Misc fixes

# 2.0.11 (2022-06-28)

Added API support for Referrals

Added login with phone&code for TG buy

Added multi language support (en/ro)


# 2.0.10 (2022-06-26)

Added "share" snipe function

Initial support for Referrals

Fixed a bug where if buy tax was not integer stats were not updated

# 2.0.9 (2022-06-21)

Fix LP detection for USDT
Improved Token update function

# 2.0.8 (2022-06-19)

switch transport from TCP to Redis (min 10x boot-time improvement)

switch cache from MemoryLRU to Redis

fixed "f", "e" char in contract TG buy as word(five, four, eight) - AI stage 2

fixed apollo federation service detection logic & fault tolerance

mutiple other misc fixes

# 2.0.7 (2022-06-12)

Fixed multiple Sniper-UI auth issues

# 2.0.6 (2022-06-09)

fix tier logic

# 2.0.5 (2022-06-08)

Public Release

Multiple improvements

# 2.0.2a (2022-05-22)

TG buy

Fixes

# 2.0.0a (2022-04-20)

Initial Web based Sniper (Alpha/POC)

End support for CLI based Sniper

# 1.1.4 (2022-03-27)

added socketMode option in env

updates

added cronos

bulk mode

# 1.1.0 (2022-02-07)

added fantom

multiple fixes

fixed testnet socket

# 1.0.0 (2022-01-17)

refactored entire app structure

# 0.8.8 (2022-01-12)

fixes for shadow trade

multiple fixes

# 0.7.2 (2022-01-01)

added profiles support

fixed usd slippage, ignoring bad actor addLiq

multiple fixes

# 0.6.6 (2022-12-29)

contract based sniper

added polygon.

# 0.6.5 (2021-12-27)

DEX select option

avax fixes

fixes for eth HP checker

# 0.6.1 (2021-12-23)

avax initial build

fixes for usd

# 0.4.2 (2021-12-17)

auto gwei gas prices

added mempool resume

# 0.4.0 (2021-12-14)

implemented HP check in ETH

updated events

added opentrading blocks

# 0.3.0 (2021-12-08)

shadow trade

autosell mempool drop

# 0.2.2 (2021-12-06)

autosell improvements

rewrote triggers

mempoolExcludeMode

fixes

# 0.2.0 (2021-12-04)

split sniper to mempool and liq sniper

fixes telegram update

# 0.1.0 (2021-11-23)

Added support for windows CLI builds

# 0.0.2 (2021-11-11)

Initial CLI release
