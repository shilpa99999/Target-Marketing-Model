# Target-Marketing-Model

The objective of this study is to address the following business challenges:

ACME plans to reduce email delivery costs by limiting email distribution to 25% of its subscriber base during Week 27. Based on the provided data, the key questions to solve are:

Subscriber Selection: Which subscribers should receive the email?
Campaign Allocation: Which campaign(s) should be delivered to them?
Response Prediction: What is the anticipated response rate?

In this analysis, data from 10,000 subscribers and their responses to 260,000 campaigns over 26 weeks were examined. The dataset is assumed to represent the original subscriber population.Derived variables were generated to enrich the analysis. Data from the first 23 weeks were utilized as a training dataset, while the final 3 weeks served as a testing dataset to evaluate model performance.

Models were developed, including Random Forest, LDA and QDA. The models were compared using varied metrics. This models were used to determine the answers to the above questions. 

Additionally, this study explored the impact of training sample size on model performance. Results showed that all models maintained satisfactory performance even when training data was reduced to the original size. This reduction in training data can minimize data collection costs and expedite campaign deployment.
