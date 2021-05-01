
## conStruct (continuous Structure) ReadMe


This repo contains the code for the method **conStruct** - a statistical tool 
for modeling continuous and discrete population genetic structure.

The manuscript, data files, and analysis scripts associated with the publication 
"Inferring Continuous and Discrete Population Genetic Structure Across Space,"
have been moved, and can be accessed at the links below:

 * [paper](https://doi.org/10.1534/genetics.118.301333)
 * [manuscript repo](https://github.com/gbradburd/conStruct-paper)
 * [data dryad](https://doi.org/10.5061/dryad.5qj7h09)

This fork simply changes the thinning parameter passed to rstan::sampling to increase the amount of saved data 
(the original code saved 250 samples, which seemed low. Increased to 2500)
For more information go to the OG fork.
