A Google Colab notebook containing multiple Python functions that can automatically build systems of replicator equations based on the input of a game pay-off matrix (2- and 3-strategy games only). I also include a function that takes the created replicator equations as input and simulates the replicator dynamics over N iterations.

I provide separate functions for replicator systems assuming either one or two infinite populations playing the game. The difference is demonstrated using the Hawk-Dove Game. 

I also implement the analysis framework by Schaffer (1988) that generalises the classical Smith and Price (1973) ESS solution concept, taking *finite* populations and variable contest size into account. In small populations players can maximise their evolutionary fitness by maximising their pay-offs *relative* to others, leading, for example, to increased aggression/”Hawkishness” in the Hawk-Dove Game. 

Next to the Hawk-Dove Game, I build replicator systems and provide a visual simulations for the following games:

Attacker-Defender Contest (De Dreu & Gross, 2018)

Rock-Paper-Scissors

Battle of the Sexes

References:

De Dreu, C. K. W., & Gross, J. (2018). Revisiting the form and function of conflict: Neurobiological, psychological, and cultural mechanisms for attack and defense within and between groups. The Behavioral and Brain Sciences, 42, e116. https://doi.org/10.1017/S0140525X18002170

Schaffer, M. E. (1988). Evolutionarily stable strategies for a finite population and a variable contest size. Journal of Theoretical Biology, 132(4), 469–478. https://doi.org/10.1016/s0022-5193(88)80085-7
 
Smith, J. M., & Price, G. R. (1973). The Logic of Animal Conflict. Nature, 246(5427), 15–18. https://doi.org/10.1038/246015a0
