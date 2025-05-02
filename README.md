# Investigating-wellness-using-principal-components-analysis


## Table of Contents
* [About the project](#About-the-project)
* [Executive summary of insights](#Executive-summary-of-insights)
* [Technical details and detailed insights](#Technical-Details-and-detailed-insights)
  *   [Data collection](#data-collection)
  *   [Tools](#Tools)
  *   [Data analysis](#Data-analysis)
  *   [Findings](#Findings)
  *   [Takeaways](#Takeaways)

The following project is based on my master's [thesis](https://academicworks.cuny.edu/cc_etds_theses/536/).

## About-the-project

Wellness is a hot topic these days. People are invested in improving their wellness. However, there isn't a clear and agreed-upon way to define or measure wellness. People and organizations have their own idea of what being "well" means, and the tools they use to check someone's wellness often look at different things. This study addressed this conceptual ambiguity and lack of a psychometrically rigorous tool in existing definitions and measurements of wellness. 

## Executive-summary-of-insights
1. I validated some of the traditional dimensions of wellness found in existing models of wellness in the literature and used by organizations. 
2. I uncovered and highlighted new nuanced markers of wellness like the importance of having community resources, opportunities to express and provide emotional support not previously measured or discussed in the literature. 
3. The study resulted in a psychometrically rigorous survey that can be used by individuals and organizations to measure and improve peoples’ wellness. 

## Technical-Details-and-detailed-insights)

## data-collection

I created a 157-question survey, informed by a nationally recognized multidimensional model of wellness (SAMHSA: Substance abuse and mental health administration) as well as a thorough literature review of the wellness space. 
Then I administered the survey to more than 500 participants. Participants answered a series of questions that aimed to assess wellness as a construct and comprised of the following 8 dimensions: (1) Social (2)
Emotional (3) Spiritual (4) Financial (5) Occupational (6) Environmental (7)Physical and (8) Intellectual

## Tools-and-libraries
I used SPSS for all analyses.

## Data-analysis
My analysis consisted of 3 steps:
1. Reliability Assessment: Internal consistency of the survey items was evaluated using Cronbach's Alpha.
2. Dimensionality Reduction: Principal Components Analysis (PCA) was employed to identify the underlying factor structure of wellness.
3. Factor Structure Exploration: Principal Axis Factoring (PAF) was utilized to further examine the latent factors and their interrelationships.

## Findings
![image](https://github.com/user-attachments/assets/d5379985-98d0-4eab-ad86-76d1dc791973)
The image above shows the results of reliability analysis to assess the internal consistency of the items within each dimension. I also used this analysis to elimintate questons that lowered the consistency within each of the dimensions. Items with an item-to-total correlation of less than .4 were discarded from final analysis. Final analyses were conducted on 105 questions. 


![image](https://github.com/user-attachments/assets/552c64fc-e7d4-4da4-af96-fd1976003603)

The image above shows the top 5 factor loadings, based on the prinical axis factoring solution (PAF). (See takeaways section below to learn more about the differences between PCA and PAF results). 
The best fitting factor solution (8 dimensional model) extracted a completely new dimension that I named Community Resources. This dimension explained the largest single percentage of variance (28.23%). This dimension reflects that the availability and accessibility of social support, resources, and opportunities within an individual's community contributes to wellness. Other significant factor loadings included Emotional Expression, Giving Emotional Support, Physical Fitness, Intellectual Stimulation, Emotional Regulation, Occupation Satisfaction, and Spirituality.

## Takeaways
The primary goal of the current study was to evaluate the dimensional makeup of wellness as proposed by SAMHSA. I achieved this in three steps:

1) The principal components analysis (PCA) of the data revealed that a nine dimensional solution best explained the most variance among wellness items, as opposed to SAMHSA's eight dimensions. The analysis revealed a refined view of wellness, such that some of the original dimensions found in the literature might actually represent multiple dimensions. For example, although SAMHSA’s occupational, intellectual, and spiritual dimensions were retained, the environmental and financial dimensions were not. The emotional dimension was divided into three distinct categories: Emotional Expression, Giving Emotional Support, and Emotional Regulation. Similarly, instead of a single Social dimension, the PCA results bifurcated into one dimension pertaining to Relationship Satisfaction and another to Social Interaction. Overall, I found that the dimensions of Spirituality, Intellectual Stimulation, Physical Health and Occupational Satisfaction were closest to SAMHSA’s original proposal.

2) I also performed a principal axis factoring (PAF) analysis. Here, the bestfitting factor solution (9 dimensional) extracted a dimension that I named Community Resources as the primary component of wellness, explaining the largest single percentage of variance (28.23%). The items that were part of Community Resources dimension were most closely related to the Environmental and Social dimensions in SAMHSA’s original model. Interestingly, the dimensions of Social Interactions and Relationship Satisfaction, which were found to be influential in the PCA solution, were absent from the PAF solution.

3) Finally, a reliability analysis using Cronbach’s Alpha revealed high internal consistency of items within each dimension, suggesting that the items created from the literature search were correlated with each other and with a particular dimension. 

The PCA and PAF led to slightly different factor structures. Specifically, unlike the PCA, the PFA introduced Community Resources as a significant indicator of one’s wellness, while removing Relationship Satisfaction and Social Interaction as central components of wellness. **I endorse the eight-factor PAF solution over the solution generated by the nine-factor PCA for two reasons**. First, 
PAF is a more suitable analytic procedure for uncovering latent variables from a set of measured variables, as it separates the common (covariance) variance in the data from the unique (uncorrelated) variance. By
contrast, PCA does not differentiate between common and unique variance and extracts factors whose linear combination retains as much information from the original data set of measured variables as possible. Thus, PCA is inappropriate for isolating latent variable, which was the main purpose of the current study. PCA is deemed more appropriate for data reduction than for a rigorous representation of the relationships among measured variables.

Although, the survey resulting from this project should be futher assessed in clinical and non-clinical populations, the procedures I undertook in the current study is the first crucial step towards validating SAMHSA's wellness model and developing a valid and reliable survey. 
