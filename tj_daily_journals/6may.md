# May 6th

## Traffic Flow Optimization: Erwin Walraven

Not entirely relevant, but chapter 2 on traffic flow looks like it could be helpful!

### Chapter 2, Traffic Flow

+ Provides theoretical background of traffic flow modeling.
+ **METANET:** macroscopic model used in this thesis

#### Traffic flow models

Two categories of traffic flow models:
1. Microscopic: define behavior for individual vehicles in terms of speed, position, and characteristics of vehicle itself. High computational cost; infeasible to use
2. Macroscopic: model traffic flow using average speed, flow and density of highway sections. **Bingo! this is what we've been looking for!**

#### Maroscopic simulation with METANET

They used **METANET**, proposed by Messner and Papageorgiou. Defines highway traffic in terms of flow, speed, and density.
Flow is number of vehicles that pass per time unit.
Speed is an average of the speed of the vehicles that pass a specific point of the highway.
Density is the number of vehicles per unit length. Value can be approximated usingflow, average speed, and number of lanes of a highway section.

... They get into some wack math here, I would advice going over it in detail.

The micro simulator was known as SUMO. I don't know if going micro is the right decision for us, but it might be something to look into.


## Macroscopic traffic flow models chapter 9

Paper to go deeper into macroscopic traffic flow models. Models are applicable for the following reasons:
1. They describe the most important properties of traffic flows, such as the formation and dissipation of queues, shock waves, etc.
2. Macroscopic models are computationally less demanding. Moreover, the computational demand does not increase with increasing traffic densities.
3. They enable determination of average travel times, the mean fuel consumption and emissions in relation to traffic flow operations.
4. These models can be written in closed-form and are generally deterministic and less sensitive to small disturbances in the input.

### General traffic flow modelling issues

The description of observed phenomena in traffic flow is not self-evident. The following approaches exist:
1. Purely deductive approaches where physical laws are applied.
2. Purely inductive approaches where input/output data from real systems are used to fit generic mathematical structures (we have data!) (ARIMA models, polynomial approximations, neural networks).
3. Intermediate approaches, where basic math models are developed first, then model is fitted using real data.

Important to note traffic flow theory will probably never reach the descriptive accuracy of other domains of science.

### Kinematic wave model and applications

The most important equation in any macroscopic traffic flow model is the conservation of vehicle equation is the conservation of vehicle equation. (see paper)

The *kinematic wave model* assumes that the traffic volume can be determined from the fundament relation between the density and the traffic volume/speed.

The paper kind of goes off the deep end in math equations here....
 


