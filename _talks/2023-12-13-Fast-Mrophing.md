---
title: "CDC2023: Fast Estimation of Morphing Wing Flight Dynamics Using Neural Networks and Cubature Rules"
collection: talks
type: "Talk"
permalink: /talks/cdc-2023
venue: "Marina Bay Sands , Singapore"
date: 2023-12-13
location: "Singapore"
---
[Full talk here:](https://www.youtube.com/watch?v=fRSAbjC4t6U)

Fluidic locomotion of flapping Micro Aerial Vehicles (MAVs) can be very complex, particularly when the rules from insect flight dynamics (fast flapping dynamics and light wings) are not applicable. In these situations, widely used averaging techniques can fail quickly. The primary motivation is to find efficient models for complex forms of aerial locomotion where wings constitute a large part of body mass (i.e., dominant inertial effects) and deform in multiple directions (i.e., morphing wing). In these systems, high degrees of freedom yields complex inertial, Coriolis, and gravity terms. We use Algorithmic Differentiation (AD) and Bayesian filters computed with cubature rules conjointly to quickly estimate complex fluid-structure interactions. In general, Bayesian filters involve finding complex numerical integration (e.g., find posterior integrals). Using cubature rules to compute Gaussian-weighted integrals and AD, we show that the complex multi-degrees-of-freedom dynamics of morphing MAVs can be computed very efficiently and accurately. Therefore, our work facilitates closed-loop feedback control of these morphing MAVs.

