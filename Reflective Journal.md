Elda's Entry:

I learned the model's overall accuracy does not tell the whole story. The overall accuracy was 84.61%, but got different results when I checked males and females separately. Seeing the difference helped me realize it is important to check how the model does for each group, not just the overall score. I also learned that this gap does not automatically mean the model is biased or that the difference is statistically significant. The most important thing is to look closely at the results before deciding whether the model is fair. 


Xinyu's Entry:

In this lab, we used the Adult dataset and ran the code for a simple Logistic Regression model to predict if individuals in the dataset had an income above $50K (or not). It achieved an overall accuracy of 84.61% but was more accurate for females (as high as 91.81% for females) than for males (81.20% for males). We looked at the error rates in terms of the False Positive Rate and the False Negative Rate. While males experienced a higher False Positive Rate (10.26%), females experienced a higher False Negative Rate (47.84%). This highlighted that different groups can experience different types of errors.

From this lab, I have learned that in order to evaluate the fairness of a model, using accuracy is not enough. It is also important to evaluate FPR and FNR for each demographic group in order to detect any possible bias in the model. Most of the existing machine learning models reflect existing bias or even produce new ones. The lab made me aware of these problems. 
