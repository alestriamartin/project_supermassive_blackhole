# Simulation of Galaxy Merging with Binary Blackholes
Princeton project 
## Introduction - Overview
In the Universe, almost every large galaxy has at its center a giant black hole, called a supermassive black hole. Scientists believe that these black holes and their host galaxies have grown together over time. This idea is known as coevolution. It comes from the observation that the size of a black hole seems to be related to the size of its galaxy. The two appear to share a common history, evolving side by side since the early stages of the Universe. 
Astrophysicians of Princeton university, created a simulation of a two galaxy merge, each of them containing a supremassive blackhole, the purpose is to study the coevolution between galaxies and supremassive blackholes.  

## What did I do ? 
The simulation created allowed me to obtain two database files containing numerical data illustrating the behavior of the two black holes in the galaxies that were merging. I was able to access these data using Python with the ‘pandas’ library, and I analyzed them with ‘matplotlib’, which enabled me to plot graphs in order to understand how these numerical values were related to each other and what connections could be made between them.

## Graphs
In order to understand what happens we chose to analyse these two datasets through graphical analysis that provides valuable insight into the coevolution of black holes and their host galaxies. 

![trajectory of the two blackholes](https://drive.google.com/uc?export=view&id=1Q1ehVG-l-D24MuOoFqCHwc7HruyYK_DC)

*Trajectory of the two Blackholes*


This graph illustrates the relative trajectories of two black holes during a galactic merger. The blue and red curves represent the motion of each black hole as they orbit around their common center of mass. Each curve shows alternating phases where the black hole reaches its pericenter — the point of closest approach between the two objects — and its apocenter, the point of maximum separation in their orbital path. As the system evolves, the orbits gradually shrink due to the loss of energy through gravitational interactions, leading the two trajectories to spiral inward. This behavior reflects the final stages of binary black hole coalescence, where the two objects eventually merge into a single, more massive black hole.

![relative distances](https://drive.google.com/uc?export=view&id=1p20UA8iYclDYWttgMMq9dco8-2OKYOGD)

*Relative distances*

This second graph is another point of view of what happens with the distance between the two blackholes. This represents the evolution of the relative distances that seperate the two blackholes. Indeed, during a galactic merger, two black holes do not collide directly but orbit around each other under their mutual gravity.
Their motion follows an elliptical trajectory with two key points: the pericenter and the apocenter. Thus, the black hole move away and come back periodically, following this orbital cycle. This explain why the curve drops sharply and then rise again. 

![mass over time](https://drive.google.com/uc?export=view&id=1yNwov1k5_nc1adFXSVAY4FQObYrGV6s9)

*Evolution of the blackhole mass over time*

![accretion rate](https://drive.google.com/uc?export=view&id=1aPMowLZMnB3kmwwh_NTogJOhfkw13HHh)

*The Accretion Rate*

The accretion rate shows how fast the black hole gains mass. When the accretion rate increases sharply (at the beginning and around 1 and 2 Gyr), the black hole absorbs a lot of matter in a short time. These peaks correspond to the sudden rises seen in the mass-over-time graph. Between these peaks, the accretion rate is very low, which explains the flat parts of the mass curve. In short, when the accretion rate is high, the black hole’s mass grows quickly, when it is low, the mass stays almost constant. 


![gaz density over time](https://drive.google.com/uc?export=view&id=1Zr1zbZcepTIGZf_YlOB04PzFb4hj8DKH)

*Evolution of the galaxy gas density over time*


This graph shows how the density of the blackhole surrounding changes over time. When the density is high, there is more gas available around the black hole, which leads to a higher accretion rate. These dense phases correspond to the accretion peaks observed earlier, where the black hole absorbs more material and its mass increases rapidly.
Conversely, when the density drops, there is less matter to accrete, so the accretion rate becomes low and the mass curve flattens. The variations in density therefore directly influence how quickly the black hole grows over time, higher density means faster growth, while lower density results in slower or nearly constant mass evolution.

![correlation](https://drive.google.com/uc?export=view&id=1xwAFOJ9yHHbBtgSK1Tu05lf1IyJVpc3F)

*Gas Density over the Accretion Rate - Correlation*

A high gas density leads to a high accretion rate, as the black hole has more material available to capture. The correlation between density and accretion rate reveals a proportional relationship as we can see with the linear function formed: Therefore, as density increases, accretion becomes more efficient, accelerating the black hole’s mass growth. Conversely, in low-density regions, the accretion rate drops significantly, slowing down the evolution. This direct link highlights the essential role of the surrounding environment in driving accretion processes and the long-term growth of black holes.

## Conclusion 
We found that the gas density is proportionnal to the blackhole mass, it is exactly what found the astrophysician Hermann Bondi in 1952 when he wrote his law named after him : the Bondi accretion. 

$$
\dot{M}_{\text{Bondi}} = 4 \pi G^2 M_{\text{BH}}^2 \frac{\rho}{c_s^3}
$$

- $\dot{M}_{\text{Bondi}}$ is the **accretion rate** (mass gained per unit time),
- $G$ is the **gravitational constant**,
- $M_{\text{BH}}$ is the **mass of the black hole**,
- $\rho$ is the **density of the surrounding gas**,
- $c_s$ is the **sound speed** in this gas (related to its temperature).

The mass does indeed depend on the gas density of the galaxy. However, other variables play a secondary role, that's why we don't have a well-defined constant straight line on the correlation graphic. 


## Sources 
