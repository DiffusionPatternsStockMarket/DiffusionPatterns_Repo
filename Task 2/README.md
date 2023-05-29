# TASK 2

The second task consists in classifying a trajectory between the five models mentioned in task 1.


# TYPES OF MOVEMENTS

**CTRW** (Continuous time random walk); characterized by behavior on the walker (particle, DNA or protein chains, stock prices...) that consists in waiting times (that can be modeled as an stochastic process) between each walker movement in whatever dimension.
<img src="" title="CTRW" />

**FBM** (Fractional Brownian Motion), which is a Gaussian process with stationary increments. It is a non-ergodic variation of Brownian Motion and keeping the distance, has certain similarities with autoregressive time-series due to the fact that the non-overlapping increments of FBM are dependent. This means that the value of the process at one time point affects the value of the process at a later time point. This behavior turns out to be not easy to model, so a machine learning driven methodology might be suitable for learning these hidden patterns.
<img src="" title="FBM" />

**Lévy Walk**, which is a variant of the CTRW with the special distinctive feature that the displacement over a dimension IS correlated with flight times, what leads to that the shorter the wait times are, the greater displacements the tracer takes, what is correlated to bigger diffusion exponents. In the same way, the tracers who follow this motion explore a space only in the superdiffusive regime.
<img src="" title="LW" />

**ATTM** (Annealed transient time motion), this archetype of Brownian motion is probably the most difficult to model because it shows weak ergodicity breaking, which leads to a Brownian motion variant that closes up the difference gap between an interpretable anomalous diffusion and a random walk. More specifically, this model can be explained by attending to dynamic and waiting times in the sense that the short-term dynamics (short displacement time) are characterized by fast fluctuations in waiting times and step-lengths, while the long-term dynamics are characterized by slower trends and correlations
<img src="" title="ATTM" />

**SBM** (Scaled Brownian motion), which, as its name says, generates a high no-stationary trajectory based on Gaussian noise following a power law dependence. This motion introduces long-range correlations and the ‘scaling’ property addresses thefactthattheamplitudeoftheBrownianMotionismodifiedbyapower-lawfunction of time.
<img src="" title="SBM" />

