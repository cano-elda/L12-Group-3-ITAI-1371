Elda's Entry:

I learned the model's overall accuracy does not tell the whole story. The overall accuracy was 84.61%, but got different results when I checked males and females separately. Seeing the difference helped me realize it is important to check how the model does for each group, not just the overall score. I also learned that this gap does not automatically mean the model is biased or that the difference is statistically significant. The most important thing is to look closely at the results before deciding whether the model is fair. 


Xinyu's Entry:

In this lab, we used the Adult dataset and ran the code for a simple Logistic Regression model to predict if individuals in the dataset had an income above $50K (or not). It achieved an overall accuracy of 84.61% but was more accurate for females (as high as 91.81% for females) than for males (81.20% for males). We looked at the error rates in terms of the False Positive Rate and the False Negative Rate. While males experienced a higher False Positive Rate (10.26%), females experienced a higher False Negative Rate (47.84%). This highlighted that different groups can experience different types of errors.

From this lab, I have learned that in order to evaluate the fairness of a model, using accuracy is not enough. It is also important to evaluate FPR and FNR for each demographic group in order to detect any possible bias in the model. Most of the existing machine learning models reflect existing bias or even produce new ones. The lab made me aware of these problems. 


Michelle's Entry:

This lab taught me that a model can look good overall and still be unfair to certain groups, so one overall score isn’t enough to trust it. I also learned that bias mostly comes from the data, not the algorithm and that simply removing a sensitive column like “sex” doesn’t fix it because other features can act as proxies. Fixing it takes deliberate steps and those can cost some accuracy. One question I still have is when different fairness definitions conflict with each other, how do you decide which one to prioritize for a real-world system?
