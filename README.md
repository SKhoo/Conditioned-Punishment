Conditioned-Punishment
================

Operant Behaviour Programs for Med Associates Chambers to run conditioned punishment experiments.

This repository is for code used to operate Med Associates Operant Chambers.
It is written in 'Med State Notation', a language only used for Med Associates equipment.
*.MPC files must be translated and compiled using Med Associates' Trans IV program before they can be used.

The protocol begins with magazine training sessions (PJR0), during which time pellets are delivered at random intervals.

Single lever sessions follow (PJR1), where pellets are delivered on a variable interval based on the [Fleshler and Hoffman (1962)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1404199/)* constant probability distribution. In variable interval schedules, a lever press only results in pellet delivery after the interval has elapsed.

In later sessions a second lever is introduced (PJR2) and each lever is rewarded using its own variable interval. 

To equalise responding on both levers, the two levers are trained on a random interval that is recalculated after each response (PJR3). The lever with more responses will be rewarded less frequently and the lever with fewer responses will be rewarded more frequently.

Finally, conditioned punishment sessions are run (PJR4), which involve the pairing of cues with each lever on independent variable interval schedules. The randomly delivered cue may result in delivery of a footshock which coterminates with the cue.

These programs are also available on Figshare (doi:10.6084/m9.figshare.3145294)

*The Med-PC Programming manual describes the INITCONSTPROBARR function as following the "Hoffman-Fleschler" distribution.
