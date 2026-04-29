# CapstoneProject
Build predictive models in machine learning for business applications . 

### Project Title
Credit Card Fraud Detection Based on Transaction Behaviour using Data Analysis and Machine Learning 

#### Executive summary
In this digital era, monetary transactions are accelerating rapidly towards a cashless system along with which the risk of fraudulent transactions is also increasing.
Credit card fraud is the most common type of identity theft causing nightmare and distress to victims (customers) and businesses who have to compensate for the loss in addition to reputational loss for repeat offences.
Timely intervention on fraud alerts and customer reach is imperative for smooth running of business and retaining customer trust and loyalty to the financial institutions.
The model can serve as a real-world application of imbalanced classification and cost sensitive Machine Learning approaches.
In this exercice, we built and compared various Predictive machine learning models that can learn from preceding data and estimate high probabilities resulting infraudulent credit card transaction.
The real world implementaiton entails monitoring the activities of populations of users in order to estimate, perceive or avoid objectionable behaviour, which consist of fraud, intrusion, and defaulting.

#### Rationale
Timely intervention of credit card companies in alerting customers for suspicious transactions is imperative due to various reasons - 

1. It causes identity theft and distress to victims (customers) and unimaginable financial losses. 
2. Businesses who have to compensate for the loss endured by the customer(s).
3. Financial institutions trust gets eroded for repeat offences causing irrecoverable damage to their reputation, added with penalties from regulatory authorities for compromised systems (Financial Conduct Authority). 
4. Quick identification of frauds cases without causing pain to customers upholds customer loyalty .

#### Research Question
In all of the classification machine learning algorithms available to us, which one would best work in detecting close to 100% of fradulent credit card transactions in upholding customer trust and reputation of the financial institiution.Machine learning algorithms are boradly classified under Supervised(works off labeled data) and Unsupervised Learning (learn from patterns or behaviors). While most of the classifiers work off labeled data, are there any unsupervised techniques (Isolation Forest(s)?) that can find hidden patterns inside the transaction behaviors in detecting fraud outliers. Most importantly, are the solution developed with these algorihms future proof and scalable to the extent when fraudsters devise new strategies and channels to exploit vulnerable customers. 

#### Data Sources

The dataset is sourced from OpenML and contains historical financial transactions labeled for fraud detection. The target variable is Class, a binary indicator where 1 represents fraud and 0 represents non-fraud.
Features include:

1. **V1–V28** : Anonymized variables derived using Principal Component Analysis to protect sensitive information

2. **Time**: Seconds elapsed since the first transaction (can be converted into time-of-day format)

3. **Amount**: Transaction value

Due to privacy constraints, original features (e.g., location, device type) are not available. While this limits interpretability and exploratory analysis, it does not impact the application of machine learning models, evaluation metrics, or predictive performance.

Note: The dataset is in .arff format and can be loaded using scipy.io.arff, then converted to CSV for easier processing.

#### Methodology
What methods are you using to answer the question?

#### Results
What did your research find?

#### Next steps
What suggestions do you have for next steps?

#### Outline of project
https://github.com/Subroy1/CapstoneProject/blob/main/CreditCardFraudCapstone.ipynb

##### Contact and Further Information

### Author
Subhojit Roy


