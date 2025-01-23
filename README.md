# cips
Global Synchronizer CIPs

| Number                         | Layer | Title                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Author        | Type    | Status |
|--------------------------------|-------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|---------|--------|
| [cip-0000](cip-0000.md)        |       | CIP Process                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Wayne Collier | Process | Draft  |
| [cip-0001](cip-0001-0002-0003) |       | Replace the SV tranche time delays with a weighted reward                                                                                                                                                                                                                                                                                                                                                                                                        |               |         | Active |
| [cip-0002](cip-0001-0002-0003) |       | Minor adjustments to the Tokenomics variables to fine tune BME tokenomics                                                                                                                                                                                                                                                                                                                                                                                        |               |         | Active |
| [cip-0003](cip-0001-0002-0003) |       | 1. Distribute Canton Coin rewards to any Validator on the Network which is live and can claim its rewards quickly. 2. Any rewards not claimed in a timely manner demonstrate a non-responsive Validator, and these unclaimed (more precisely, "allowed but unminted") rewards are added to a pool controlled by the Global Synchronizer Foundation ("the Foundation"). 3. During Mainnet Launch, participation will be invite only and limited to 200 Validators |               |         | Active |
| [cip-0006](cip-0006-0007)      |       | 1. Define the process of distributing the 200 Validator rights available at the start of the Network. 2. Define the process of approving apps to join the MainNet Launch phase                                                                                                                                                                                                                                                                                   |               |         | Active |
| [cip-0007](cip-0006-0007)      |       | 1. SVs can earn extra SV reward weight when bringing Validators or apps to the Canton Network. 2. Allocate some Validator rights                                                                                                                                                                                                                                                                                                                                 |               |         | Active |
| [cip-0008](cip-0008)           |       | This proposal doubles the amount of free traffic (the burst amount) available in a given free traffic window (the burst window), to allow application developers to continue development work on DevNet.                                                                                                                                                                                                                                                         |               |         | Active |
| [cip-0009](cip-0009-0010-0011) |       | Add Broadridge as a T1 (weight 10) Super Validator                                                                                                                                                                                                                                                                                                                                                                                                               |               |         | Active |
| [cip-0010](cip-0009-0010-0011) |       | Increase LCV reward weight from 3 to 10                                                                                                                                                                                                                                                                                                                                                                                                                          |               |         | Active |
| [cip-0011](cip-0009-0010-0011) |       | Decrease Foundation weight by 1 (IntellectEU forgoes Super Validator minting rights, which decrease the Foundation's weight by 1)                                                                                                                                                                                                                                                                                                                                |               |         | Active |
| [cip-0012](cip-0012)           |       | Minor adjustments to Canton Coin processing, and Operational configuration, on the Global Synchronizer                                                                                                                                                                                                                                                                                                                                                           |               |         | Active |
| [cip-0013](cip-0013)           |       | Correct an error in the Daml models controlling the re-onboarding process for Super Validators who have been removed from the quorum. The error allowed Super Validators to mint Canton Coin greater than their agreed share after being removed and returned to the quorum.                                                                                                                                                                                     |               |         | Active |
| [cip-0014](cip-0014)           |       | 1. Complete additional enhancements to the Scan API to facilitate tax accounting. 2. For this time only, shorten the preparation time for the final MainNet build. Shorten to two (2) days on DevNet, and to five (5) days on TestNet. 3. Vote to initiate the nine (9) - day final launch process on June 18th, 2024, leading to a launch of MainNet beginning June 25th, 2024 and completing June 27th, 2024. 4. Announce go-live on July 2nd, 2024            |               |         | Active |
| [cip-0015](cip-0015-0016-0017) |       | Add Copper as a T3 (weight 1) Super Validator                                                                                                                                                                                                                                                                                                                                                                                                                    |               |         | Active |
| [cip-0016](cip-0015-0016-0017) |       | Add Dfns as a T3 (weight 1) Super Validator                                                                                                                                                                                                                                                                                                                                                                                                                      |               |         | Active |
| [cip-0017](cip-0015-0016-0017) |       | Add MPCH as a T3 (weight 1) Super Validator                                                                                                                                                                                                                                                                                                                                                                                                                      |               |         | Active |
| [cip-0018](cip-0018)           |       | Add Tradeweb to the SV weight pool                                                                                                                                                                                                                                                                                                                                                                                                                               |               |         | Active |
| [cip-0019](cip-0019)           |       | Add 7RIDGE as a T1 (weight 10) Super Validator. 7RIDGE is used as a place holder to represent the NewCo until the entity name is finalized.                                                                                                                                                                                                                                                                                                                      |               |         | Active |
| [cip-0020](cip-0020)           |       | This proposal reduces the read cost scaling factor from 200 basis points to 4 basis points                                                                                                                                                                                                                                                                                                                                                                       |               |         | Active |
| [cip-0021](cip-0021)           |       | Introduce Featured Application and Validator Committee (FAV-C)                                                                                                                                                                                                                                                                                                                                                                                                   |               |         | Active |
| [cip-0022](cip-0022)           |       | Affirm June 25th, 2024 (2024-06-25) as the go-live date for Global Synchronizer MainNet Round 0                                                                                                                                                                                                                                                                                                                                                                  |               |         | Active |
| [cip-0024](cip-0024-0025)      |       | 1. SVs and Validators can earn SV reward weight when bringing Validators or apps to the Canton Network. 2. Referral rewards are skewed to encourage early participation. 3. Referral rewards are capped at a total increase to the pool of 20. 4. Referral rewards are time bound to 18 months after MainNet Launch begins.                                                                                                                                      |               |         | Active |
| [cip-0025](cip-0024-0025)      |       | The Featured Applications and Validators Committee (FAV-C) moves into a Working Group of the GSF                                                                                                                                                                                                                                                                                                                                                                 |               |         | Active |
| [cip-0032](cip-0032-0033-0034-0036-0038-0039-0040/cip-0032-0033-0034-0036-0038-0039-0040.pdf)                 |       | Add Lukka as a Tier3 SV (Weight 1)                                                                                                                                                                                                                                                                                                                                                                                               |               |         | Active |
| [cip-0033](cip-0032-0033-0034-0036-0038-0039-0040/cip-0032-0033-0034-0036-0038-0039-0040.pdf)                   |       | Add Strange Pixels as a Tier4 SV (Weight 0.5)                                                                                                                                                                                                                                                                                                                                                    |               |         | Rejected |
| [cip-0034](cip-0032-0033-0034-0036-0038-0039-0040/cip-0032-0033-0034-0036-0038-0039-0040.pdf)                   |       | Add Proof Group as a Tier3 SV (Weight 1)                                                                                                                                                                                                                                                                                                                                                                                           |               |         | Active |
| [cip-0036](cip-0032-0033-0034-0036-0038-0039-0040/cip-0032-0033-0034-0036-0038-0039-0040.pdf)                    |       | Add Kiln as a Tier3 SV (Weight 1)                                                                                                                                                                                                                                                                                                                                                                                   |               |         | Active |
| [cip-0038](cip-0032-0033-0034-0036-0038-0039-0040/cip-0032-0033-0034-0036-0038-0039-0040.pdf)                    |       | Add Hexagate as a Tier3 SV (Weight 1)                                                                                                                                                                                                                                                                                                                                                                                   |               |         | Active |
| [cip-0039](cip-0032-0033-0034-0036-0038-0039-0040/cip-0032-0033-0034-0036-0038-0039-0040.pdf)                    |       | Add Copper Clearloop as a Tier3 SV (Weight 1)                                                                                                                                                                                                                                                                                                           |               |         | Active |
| [cip-0040](cip-0032-0033-0034-0036-0038-0039-0040/cip-0032-0033-0034-0036-0038-0039-0040.pdf)                    |       | Add Deribit as a Tier3 SV (Weight 1)                                                                                                                                                                                                                                                                                                                                                                                      |               |         | Proposed |
| [cip-0042](cip-0042)                    |       | Stable Price per Canton Coin Transfer via Synchronizer Fees                                                                                                                                                                                                                                                                   |               |         | Active |

