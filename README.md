# ASD-identification-during-development-stage-of-humans
- Bid Data Analytics Capstone 
- CIS-627-161
- 4/25/2020

# Problem Statement: 

Which genetic markers can help in comprehending not just autism as a whole but also of the developmental stage, particular biology or behavioral needs of each person on the autism spectrum?

# Requirement:
The script is written in R, the required packages are as follows: `devtools` `RSQLS` `tidyverse` `h2o` `kernlab` `randomForest` `caret` `nnet` `rpart` `e1071` `caTools` `readxl` `ggthemes` .

# Summary: 
This analysis looks to predict the probability of autism by identifying the most impactful genomic symbols that make up the immune system to uncover trends of growth or deterioration of gene expressions while cross validating across six prediction models.

## Execution:
<a href="https://ibb.co/4JTgpK6"><img src="https://i.ibb.co/mSqF4bL/treemap2.png" alt="treemap2" border="0"></a>

The above image displays the top 20 impacted genes by the neuronal induction which were obtained by looking at the difference of the two raw datasets which can be found in the data folder of this repository, next a scrapper was used to identify the gene symbols with their corresponding names, synonyms and description. An exploratory data analysis was performed to prepare the data and gain a better understaind before delving into the model building.

# Result:
<a href="https://ibb.co/wQzy5gD"><img src="https://i.ibb.co/s1Vj8RL/single-iteration.png" alt="single-iteration" border="0"></a>


<a href="https://ibb.co/K6xSWrS"><img src="https://i.ibb.co/D4fTQRT/acc-barplot.png" alt="acc-barplot" border="0"></a>


In today’s data-driven world, employers, lenders, marketers, educators, and many others are able to obtain a bounty off of information about individuals. These parties may then use data to identify those with future risks and prospects, and make adverse decisions concerning them. The same could be said for the medical field and the enormous potential that underlies in research for predicating diseases. Efforts should be taken by the governing body of medical association to focus on such disorders, work on them for the betterment of the future.
	
	The most accurate model for prediction of ASD was obtained using SVM with an accuracy of 72% and it was backed by anova and tukey test to affirm its dominance.

 	To validate this preliminary study further a substantial greater number of patient-specific iPSC-derived neuron must be generated in future investigation of larger cohorts.

