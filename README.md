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

Figure 1: Tree map of top 20 impacted genes

The above image in figure 1 displays the top 20 impacted genes by the neuronal induction which were obtained by looking at the difference of the two raw datasets which can be found in the data folder of this repository, next a scrapper was used to identify the gene symbols with their corresponding names, synonyms and description. An exploratory data analysis was performed to prepare the data and gain a better understaind before delving into the model building. For the six models used in this study the accuracies obtained using a standard sample were reinforced by iterating through each single model 25 time with a different sample so that a clearer view on the accuracies can be achieved. Figure 1 and Figure 2 show the difference after the 25 different iterations. Finally the data was pushed to a local hosted SQL serves so that it can be drawed into PowerBi for interactive visualization.

# Result:
In today’s data-driven world, employers, lenders, marketers, educators, and many others are able to obtain a bounty off of information about individuals. These parties may then use data to identify those with future risks and prospects, and make adverse decisions concerning them. The same could be said for the medical field and the enormous potential that underlies in research for predicating diseases. 
	
The most accurate model for prediction of ASD was obtained using SVM with an accuracy of 72% and it was backed by anova and tukey test (p value less than level of significance) to affirm its dominance. The accuracy for SVM increased by 10% after iterating through different samples for 25 times.

To validate this preliminary study further a substantial greater number of patient-specific iPSC-derived neuron must be generated in future investigation of larger cohorts.



<a href="https://ibb.co/wQzy5gD"><img src="https://i.ibb.co/s1Vj8RL/single-iteration.png" alt="single-iteration" border="0"></a>

Figure 2 : Accuracy for Single Iteration

<a href="https://ibb.co/K6xSWrS"><img src="https://i.ibb.co/D4fTQRT/acc-barplot.png" alt="acc-barplot" border="0"></a>

Figure 3: Average Accuracies for 25 Iterations
