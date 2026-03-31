Analyzing the Relationship Between Physical Activity and Mental Health in Adults
By Ryan Shea & Dawson Ullrich

This project investigates whether physical activity has a measurable effect on mental health in adults, drawing on both existing academic literature and large-scale survey data.

Literature Review
The authors reviewed three peer-reviewed papers. Paluska and Schwenk found that exercise can benefit adult mental health similarly to meditation or relaxation, though excessive exercise can have negative effects. Saxena et al. found physical activity helpful in treating common mental health disorders. Tyson et al. found that students who exercised more reported better mental health. Across all three studies, however, the evidence pointed to a marginal rather than large effect.

Data
The analysis used the 2023 Behavioral Risk Factor Surveillance System (BRFSS), the world's largest continuously conducted health survey, administered by the CDC. It covers over 400,000 adults across 78 states and territories. The two primary variables were EXEROFT1 (frequency of physical activity per week) and MENTHLTH (number of days in the past 30 with poor mental health). After cleaning, the working dataset contained 57,122 observations.

Statistical Analysis
A simple linear regression initially returned a p-value of 0.061, falling just short of statistical significance. The QQ plot revealed violations of the normality assumption, prompting variable transformations — log for EXEROFT1 and inverse for MENTHLTH — guided by the Box-Cox method.
Three control variables were then added: average drinks per day (AVEDRNK3), number of children in the household (CHILDREN), and employment status (EMPLOY1). The resulting multiple regression model found log(EXEROFT1) statistically significant at p=0.02, with a positive coefficient indicating that more exercise is associated with fewer bad mental health days. However, the model's R² of 0.07 indicates it explains only about 7% of the variation in mental health outcomes.
An Instrumental Variable (IV) model using height as the instrument was attempted to test for reverse causality. The IV model returned a p-value of 0.375, meaning it could not confirm a statistically significant causal relationship, and the weak F-statistic suggested height was not a strong instrument.

Conclusion
The findings suggest exercise has a modest, positive association with mental health, but the evidence is weak and the causal direction remains uncertain. These results align with prior literature showing only a marginal beneficial effect of physical activity on mental health.
