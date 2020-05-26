# Epicenter: a knowledge-based system for mathematical modeling of infectious disease

Building mathematical models of infectious disease is an incredibly challenging task because of the huge amount of uncertainty involved. From a reductionist perspective, epidemic models are relatively simple: they can be formulated in terms of 2 main concepts:

1. Infection: how does an individual agent (human or otherwise) respond to the presence of a disease/condition?
2. Transmission: how does 'contact' between an infected and a susceptible agent result in transmission?
3. Agent Behavior: how much contact does an individual have and how does this change over time

However, each of these concepts are ladden with huge amounts of uncertainty and variability when it comes to each individual and each transmission. 

Within individuals this variation comes from factors including:
  - Species (or potential non-biological agents)
  - Risk factors (and negative determinants)
  - Pathogen dosing
  - Immunity
  - Drugs / Treatment
  
When it comes to transmission variation can come from factors including:
  - Different transmission vectors (airborne, droplet, fecal-oral, sexual, direct contact, vertical, vector-borne, iatrogenic, social)
  - Differing levels of infectiousness
  - Differing levels of restivity / partial immunity
  - Duration of contact / time delays,
  
When it becomes to agent behavior, variation can come from factors including:
  - Hygeine / Physiology
  - Psychology / Social Contagion
  - Response to interventions
  - Social network structure
  
Many of these properties are related, and can be considered as properties of the agent rather than of the transmission event. 

Modeling all of these variations is intractable and impractical, so different models make different simplifying assumptions. As opposed to capturing each individual's behavior perfectly, often these qualities are drawn from some probability distribution (potentially disregarding conditional dependence / covariance). Many models go further specify, with parameterization that is in terms of some latent variable. The conditional distributions of these latent variables are often specified as simple joint distributions or non-random variables. These assumptions largely employ some variant of mean-field theory. This may apply in the macroscopic limit, but these approximations may not capture the behavior of specific subpopulations, and likely do not capture the dynamism of the behavior in the early stages of the epidemic. 

When estimates of these variables (both fundamental and observed) are obtained from observational data, it is very difficult to reason about how the models generalize to other populations; the mean-field limits most likely do not apply. 

Under this formulation, everything from agent-based models to purely statistical models exist in some spectrum of model relaxations that depend on the level and type of knowledge and assumptions encoded in the model.