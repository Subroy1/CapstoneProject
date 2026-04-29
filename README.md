# CapstoneProject
Build predictive models in machine learning for business applications . 

### Project Title
Credit Card Fraud Detection Based on Transaction Behaviour using Data Analysis and Machine Learning 

#### Executive summary


#### Rationale
Why should anyone care about this question?

#### Research Question
In all of the classification machine learning algorithms available to us, which one would best work in detecting close to 100% of fradulent credit card transactions in upholding customer trust and reputation of the financial institiution.Machine learning algorithms are boradly classified under Supervised(works off labeled data) and Unsupervised Learning (learn from patterns or behaviors). While most of the classifiers work off labeled data, are there any unsupervised techniques (Isolation Forest(s)?) that can find hidden patterns inside the transaction behaviors in detecting fraud outliers. Most importantly, are the solution developed with these algorihms future proof and scalable to the extent when fraudsters devise new strategies and channels to exploit vulnerable customers. 

#### Data Sources

The dataset is sourced from OpenML and contains historical financial transactions labeled for fraud detection. The target variable is Class, a binary indicator where 1 represents fraud and 0 represents non-fraud.
Features include:

**V1–V28** : Anonymized variables derived using Principal Component Analysis to protect sensitive information

**Time**: Seconds elapsed since the first transaction (can be converted into time-of-day format)

**Amount**: Transaction value

Due to privacy constraints, original features (e.g., location, device type) are not available. While this limits interpretability and exploratory analysis, it does not impact the application of machine learning models, evaluation metrics, or predictive performance.

Note: The dataset is in .arff format and can be loaded using scipy.io.arff, then converted to CSV for easier processing.

#### Methodology
What methods are you using to answer the question?

#### Results
What did your research find?

#### Next steps
What suggestions do you have for next steps?

#### Outline of project

- [Link to notebook 1]()
- [Link to notebook 2]()
- [Link to notebook 3]()

##### Contact and Further Information

### Author
Subhojit Roy


