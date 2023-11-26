## Reconstructing the Ancestral State Phylogeny of the Rattlesnake Rattle

Vince Weber, Eric Witte, Shinji Yamamoto

We are attempting to recreate a phylogenentic figure from *Beahvioral Plasticity and the Origins of Novelty: The Evolution of the Rattlesnake Rattle* (Allf, Durst, & Pfennig 2016). This figure demonstrates the uniqueness of the novel trait of a tail rattle, which only evolved in rattlesnakes. Following the methods described in the paper, we will have to prune the viperidae and colubridae trees from a larger squamata phylogeny using an R package---ape (Paradris et al. 2004). Next, we will use the data from the study on tail vibration duration (sec) and vibration frequency (hz) to reproduce figure 4 from the publication. Our results ideally will produce a similar or identical phylogeny depicting propensity for tail vibration and frequency with a color ramp as a means to visualize the data in a format easily interpreted by the human eye.

We started by trimming the phylogeny data from Pyron et al. (2013) to match the rattlesnake's tail vibration frequency and duration data from Allf et al. (2016). We soon realized that not all species in the vibration and duration data are in the phylogeny data. We speculate that this is because some names used in the phylogeny are now invalid. (We might discard these unmatching species since the paper does not mention what they did to link the two data.)



## Literature Cited

Allf, B. C., P. A. P. Durst, and D. W. Pfennig. 2016. Behavioral plasticity and the origins of novelty: the evolution of the rattlesnake rattle. The American Naturalist 188(4):476-483.

Paradis, E., J. Claude, and K. Strimmer. 2004. APE: analyses of phylogenetics and evolution in R language. Bioinformatics 20:289--290.
