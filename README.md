# 0D's proof-of-work

<img width="941" alt="Screen Shot 2022-02-14 at 3 34 45 PM" src="https://user-images.githubusercontent.com/1364012/153942165-dbfb6cc9-1316-4d55-bc85-42c2ca9d048a.png">

# About:

I've contributed to 0L since June 2019, through different DAOs and Companies. None of these have investors. All work was volunteer based and uncompensated.

# Disclosures:
I have received donations from other validators for my pre-genesis work. https://github.com/0o-de-lally/tip-jar

I operate nodes for other less technical collaborators, for institutions, and for DAOs:
- (46A - genesis) My node
- (D17) A global non-profit
- (ECA - genesis) The Early 2019 0L contributors *
- (355) An early non-technical 0L contributor
- (7EC - genesis) Diaspora: A DAO for former employees of companies sponsoring 0L/libra/diem. *
- (69A) An early non-technical 0L contributor

`*` I will have a stake in those nodes, but the share is yet undefined by DAO governance.

# Work Contributed Since Genesis

Work from June 2019 - Oct 2021, pre-genesis is not counted here

## Genesis
Release v5 - Genesis Tools and Infrastructure

## Move bugfixes

- Move: TowerState init issue (release 5.1)
- Move: Onboarding Edge Cases Hot upgrade (release 5.2)
- Move: Onboarding Rate limit issues (release 5.2)
- Move: Community wallet transaction script (release 5.4)
- Move: Carpe Underpayment Bugfix (release 5.5)
- Move: Epochs Validator Compliant  Bugfix (release 5.5)

## Mempool

- Mempool: Prevent transactions from remaining in pool (release 5.6)
- Mempool: Harden mempool from over-submission of txs (release 5.7)

## Onboarding Tooling

- Assorted PRs related to onboarding (see below)
- Tooling: Producing correct default settings for node (release 5.8)

## Network configuration (VFN)

- Tooling: Producing VFN files and correct onboarding configs  (release 5.9)

## Network Hot Upgrade refactor (MoveVM cache)

- VM Executor: Move functions for upgrade refactor  (release 5.10)
- VM Executor: Stdlib upgrade refactor and caching issues  (release 5.11)

## Delegation
- Teams architecture
- Move implementation of protocol https://github.com/OLSF/libra/pull/861
- Carpe bindings

## Carpe App
- Create app v0 POC
- Led alpha release Release app v0.1
- Led beta release Release app v0.2

## Incident Response
- December Incident Debugging and response: https://hackmd.io/KY7VklgAR72Bg7ETTQZAxA

## Engineering Management
- ENG working group coordingator.

## System Documentation
- Assorted PRs see below

## Operating Rex Testnet
- Operating a testnet of 3 nodes

# Lead Contributor on Releases:

- Release v5.0.1 https://github.com/OLSF/libra/blob/main/ol/changelog/5_0_1.md
- Release v5.0.2 https://github.com/OLSF/libra/blob/main/ol/changelog/5_0_2.md
- Release v5.0.3 https://github.com/OLSF/libra/blob/main/ol/changelog/5_0_3.md
- Release v5.0.4 https://github.com/OLSF/libra/blob/main/ol/changelog/5_0_4.md
- Release v5.0.5 https://github.com/OLSF/libra/blob/main/ol/changelog/5_0_5.md
- Release v5.0.6 https://github.com/OLSF/libra/blob/main/ol/changelog/5_0_6.md
- Release v5.0.7 https://github.com/OLSF/libra/blob/main/ol/changelog/5_0_7.md
- Release v5.0.8 https://github.com/OLSF/libra/blob/main/ol/changelog/5_0_8.md
- Release v5.0.9 https://github.com/OLSF/libra/blob/main/ol/changelog/5_0_9.md
- Release v5.0.10 https://github.com/OLSF/libra/blob/main/ol/changelog/5_0_10.md
- Release v5.0.11 https://github.com/OLSF/libra/blob/main/ol/changelog/5_0_11.md

## Pull Requests contributed:

- 27c125594 Txsparam refactor (#973)
- d85062274 Update validator_onboarding_hard_mode.md (#972)
- 2c115ae7b fix link to cli cheatsheet, update trouble shooting for onboarding (#971)
- e142a7f2a patch unused template file error for onboarding. (#968)
- 787061359 [tools] refactor how upstream nodes are selected for by `txs` (#952)
- 2854a8f4e Release v5.0.11 (#951)
- de35536e0 [core] Diem node upgrade restart (#946)
- 2ae2e7691 Update 5_0_10.md (#948)
- e68acaf21 [upgrade] Upgrade::upgrade_reconfig needs to increment epoch (#945)
- 34b436e98 [upgrade]  MoveVM cache issue around upgrades, trigger reconfig (#942)
- e5a78cabd Release v5.0.9 (#940)
- 5f61e5e83 [tools] Transaction to update Val configs on chain (#938)
- 441dab5a1 VFN network configurations (#799)
- b51ce2c41 Raise the log level for peer disconnection from (#925)
- 2d67388c9 change defaults on node.yaml configs: increase ping failtures tolerated, shut off json-rpc on validators (regression), increase minimum prune window. (#924)
- 26e868483 changelog for 5.0.7 (#923)
- e9602335a Harden the mempool against a flood of new txs by discarding them earlier in validation (#922)
- b41e07039 Update 5_0_6.md (#908)
- f76673da8 [tower] Use diem-logger instead of println (#911)
- 75f52da26 [mempool] Add logging when rejecting a commit (#921)
- 14737a408 v5.0.6 (#907)
- 6782f5b10 [mempool] Ensure mempool resends all txns after disconnect (#905)
- a2af10c4d one line change to prevent too new sequence numbers from being kept in mempool (#906)
- 54c95733c Correct command in validator hard mode guide (#897)
- f332a03f0 Update 5_0_5.md (#896)
- ba3c7d64e Release 5.0.5 (#895)
- 9d34378bd [move] change data structure for tracking miner proofs used in Carpe payments (#890)
- 0b2f29016 Epochs validating and mining metrics fix (#880)
- a8f772ee6 Run npm update then rebuild (#892)
- e64a186c5 Updates documentation for cli_cheetsheet (#882)
- 9e6aa0ccf Fix hard mode guide link in easy mode guide and remove dead link from (#879)
- d3c474a87 Patch bug in end-user transfer (#887)
- 1de14ceb7 Update README.md (#883)
- 18542c701 remove operator balance as a check on Audit.move (#886)
- d3383a257 restoring from backup was not inserting the waypoint to the correct namespace (#876)
- e96166ef3 Fix "ol serve --update", using reqwest instead of curl and tar instead of unzip. Issue #542 (#881)
- 54b0eb6fb Update docs autopay (#877)
- 6d7d7d12b Community wallet transfer transaction script (#859)
- d0945ac98 update schedules (#860)
- b4ad0d34c fixing bug where tokens can be transferred on account creation + test (#849)
- beb8f938c Fix web-monitor "can create account" field info (#853)
- 8203dac9c Minor edits on rulebook (#850)
- 1a44012f2 update epochs until account creation to be a < comparator rather than <= (#858)
- 8e9954f04 Add doc to fetch web server files
- 9b4f277ef Fix web-monitor filename in update_web
- 9c3e13308 change description (#832)
- 632da3ff6 troubleshooting on account creation.
- 22c34172e Main readme (#828)
- 59f30f8b6 add links to Carpe and delay towers documentation
- bf80298cd readme formatting
- c5069bf9a readme (#827)
- 0699a28ab Release v5.0.3 (#822)
- 3862cd7c4 Check the user onboarding the new validator is actually in the validator set (#819)
- 442b6d2dc minor documentation patches (#820)
- c9f01ee4e patch easy mode install script (#821)
- 7fd760967 TowerState check difficulty on initialize (#818)
- 39af78bc2 Onboard namespace issue (#817)
- 882144d58 Merge pull request #814 from OLSF/patch-rate-limit
- 066d34113 fixed integration submit test
- d712cf459 VDF proofs for normal user accounts - fix in code and documentation
- bb7033463 Onboarding patches (#804)


