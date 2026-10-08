# Advances in STV Margin Computation

A talk presented on 8 October 2026 by [Damjan Vukcevic][damjan] at the
[11th International Joint Conference on Electronic Voting][evoteid2026]
(E-Vote-ID 2026).

[damjan]: http://damjan.vukcevic.net/
[evoteid2026]: https://e-vote-id.org/programme-2026/

Authors: Michelle Blom, Alexander Ek, Peter J. Stuckey, Vanessa Teague,
Damjan Vukcevic.


## Abstract

*Single transferable vote* (STV) is a multi-winner preferential
proportional electoral system. The margin is the smallest number of ballots
that need to be manipulated to alter the set of winners. If we can
compute the margin of an STV election, or a reasonable lower bound on
the margin, we can use recent advances in auditing research to conduct
a risk-limiting audit of the election’s winners. Knowledge of the margin
also provides insight into whether uncovered mistakes, or a known
error rate in ballot interpretation, could have influenced the outcome.
This paper presents substantial improvements on an existing algorithm
for computing lower bounds on the margin of an STV election. These
improvements allow us to compute higher lower bounds for real STV
elections, making mismatch-based risk-limiting audits more practical.


## Licence

[![Creative Commons License][cc-img]][cc]  
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License][cc].

[cc]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-img]: https://i.creativecommons.org/l/by-sa/4.0/88x31.png