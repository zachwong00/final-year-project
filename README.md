# Final Year Project
An overview of my undergraduate thesis.

### Behind the Loot: Understanding the Influence of Motivation, Impulsivity, and Gambling Cognitions in Risky Loot Box Engagement in Malaysia

Risky and problematic behaviours within the realm of video gaming are increasing rapidly, where online gambling has surfaced in sectors of the Internet that traditionally had no association with gambling such as video games, social media and electronic sports (esports; Macey & Hamari, 2018). 

Hence, the exposure to gambling-like elements/mechanics within games could in ndirectly normalise gambling activities, fostering more permissive attitudes and beliefs towards gambling itself. Some researchers further argues that they can act as a potential “gateway” to problematic gambling or further aggravate gaming or gambling related harms such as addiction, risky engagement and financial loss (Delfabbro & King, 2020; Montiel et al., 2022).

## Research Project Aims
1. To investigate the predicting role of **specific motivation factors** on risky loot box engagement among Malaysian young adults.
2. To investigate the predicting role of **impulsivity** on risky loot box engagement among Malaysian young adults.
3. To investigate the predicting role of **gambling cognitions** on risky loot box engagement among Malaysian young adults.

Independent Variables: Motivation factors, Impulsivity, Gambling Cognitions
Dependent Variables: Risky Loot Box Engagement (RLB)

## Hypothesis Testing
The alternative hypotheses of this study are:
- H1: **Enhancement motive** is a significant positive predictor to predict risky loot box engagement among Malaysian young adults.
- H2: **Progression motive** is a significant positive predictor for risky loot box engagement among Malaysian young adults.
- H3: **Social pressure motive** is a significant positive predictor for risky loot box engagement among Malaysian young adults.
- H4: **Distraction/compulsion motive** is a significant positive predictor for risky loot box engagement among Malaysian young adults.
- H5: **Altruism motive** is a significant positive predictor for risky loot box engagement among Malaysian young adults.
- H6: **Fear of missing out motive** is a significant positive predictor for risky loot box engagement among Malaysian young adults.
- H7: **Resale motive** is a significant positive predictor for risky loot box engagement among Malaysian young adults.
- H8: **Impulsivity** is a significant positive predictor for risky loot box engagement among Malaysian young adults.
- H9: **Gambling cognitions** is a significant positive predictor for risky loot box engagement among Malaysian young adults.

## Research Methods
I conducted an online survey using Google Forms that employs a battery a five questionnaires that measures demographic information, independent factors (motivation, impulsivity and gambling cognitions) and risky loot box engagement. 

Data analysis is done with R Studio, by performing Multiple Linear Regression (MLR) after data is cleaned and validated (348 observations).

## Multiple Linear Regression Visualization
Independent variables and their effects are controlled 
![MLR plots](https://github.com/user-attachments/assets/b15b4aba-b9ca-400e-84a9-9a33dd59f84c)

## Results
### Descriptive Statistics
The characteristics of this study’s participants are mostly male gamers (n = 229, 66.2%) with a mean age of 23.53 and mode of 25, predominantly Malay (n = 173, 50%) and being a student (n = 148, 42.8%). Moreover, participants mostly had an average two to four gaming hours per day (n = 124, 35.8%), followed by one to two hours per day (n = 110, 31.8%). Surprisingly, 71.6% of the current sample had spent some amount of money in video games, with the monthly spending range between RM 1 to RM 100 being the highest (n = 178, 51.4%).

### MLR Analysis
Residuals:
    Min      1Q  Median      3Q     Max 
-8.0876 -2.7779  0.1912  2.7354  8.4041 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  0.18332    1.42472   0.129 0.897695    
M1           0.06752    0.06541   1.032 0.302660    
M2           0.33823    0.09429   3.587 0.000384 ***
M3          -0.02770    0.15142  -0.183 0.854978    
M4           0.24842    0.07741   3.209 0.001458 ** 
M5          -0.11223    0.11211  -1.001 0.317510    
M6           0.31032    0.10736   2.891 0.004094 ** 
M7          -0.21346    0.12365  -1.726 0.085214 .  
IP           0.13897    0.03521   3.947 9.65e-05 ***
GC           0.13152    0.01690   7.782 8.77e-14 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 3.538 on 338 degrees of freedom
Multiple R-squared:  0.4226,	Adjusted R-squared:  0.4072 
F-statistic: 27.49 on 9 and 338 DF,  p-value: < 2.2e-16


The model shows a 42.2% significant effect on RLB, Gambling cognitions factor was found to be the strongest, significant predictor (β = .37, p < .001) for risky loot box engagement among Malaysian young adults. 

Other significant factors followed are Impuslvitiy, Progression motive, Distraction/compulsion motives and Fear of missing out motives in decreasing beta coefficients order. 
