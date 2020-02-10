# Software
All codes were created and run using R statistical software (https://www.r-project.org/) version 3.5.3  <br />
and Rstudio version 1.1.383 (https://rstudio.com/).

# About SEI-SEIR_Arboviruses
This repository provides code to run climate-based mechanistic models of arboviral transmission. The models support of the manuscript "Climate explains geographic and temporal variation in mosquito-borne disease dynamics" by Caldwell et al (in prep). 

# models:
Temperature-, rainfall-, and humidity-dependent model: SEI-SEIR_model_THR.R <br />
Temperature-, rainfall-, and humidity-dependent model with trait variation: SEI-SEIR_model_with_trait_variation.R <br />
Intervention 1 - reduce contact rate between mosquitoes and people: SEI-SEIR_model_intervention_reduce_biteRate.R <br />
Intervention 2 - reduce immature mosquito habitat: SEI-SEIR_model_intervention_reduceK.R <br />
Intervention 3 - reduce mosquito abundance: SEI-SEIR_model_intervention_spray.R <br />
Code to set up simulations: SEI-SEIR_simulation_setup.R <br />

# data:
Initial conditions (proportion of population in each compartment): LHS_inputs.csv <br />
Posterior distribution of c, T0, Tmax for temperature-dependent traits: Random_sample_of_posterior_traits.csv 

# analyses 
Compare model output with observational data: correlation_sign_test_anova.R <br />
Classification and regression tree model with z-score scores and different climate metrics: CART_model.R 
