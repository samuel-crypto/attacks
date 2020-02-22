# Sarah2 Known Plaintext Attack
## Summary / Overview
*Sarah2* is a powerful pen-on-paper cipher construction designed to be easy to execute on paper, while also being difficult to break.

I present here a known-plaintext attack on *Sarah2* as well as round count recommendations for avoiding this attack.

Following are statistics on time & data complexity, as well as the percentage of the S-box recovered and an 
estimate for what % of an unknown message could be decrypted with the amount of entries recovered.

| Message Length | Time complexity | Data complexity | Percentage of S-box recovered | Percentage of unknown message decryptable |
| -- | -- | -- | -- | -- |
| 14 | 2^16 | 2^30 | 50% | 15% |
