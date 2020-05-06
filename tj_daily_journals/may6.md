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

Paper to go deeper into macroscopic traffic flow models.
