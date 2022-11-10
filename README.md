# Ethereum Fraud Analysis
**BT4012 Fraud Analytics Project**
<br> Group 12

**Importance of Solving Cryptocurrencies Fraud Problems**
<p align="justify">
The rise in popularity of blockchain technologies in recent years caused fraudulent activities in this space to increase at an alarming rate. The anonymous nature of cryptocurrency transactions also contributed to this increase in fraudulent activities. With serious consequences like high monetary loss, we saw a strong need to identify fraudulent activities in blockchain in order to reduce the number of scams in the future. Therefore, in this project, we decided to train a machine learning model and use it to detect if a crypto activity is fraudulent.
</p>

**Challenges Faced in Combating Cryptocurrencies Fraud**
<p align="justify"> Compliance with regulatory policies is a significant challenge when combating cryptocurrencies fraud. For example, Know-Your-Customer (KYC) is a regulatory policy where it is mandatory to collect customers' personal information before they are allowed to transact. This acts as a deterrent for fraudsters. However, KYC goes against the principle of decentralisation, which is what crypto was originally made to achieve (having a centralised authority store a user's personal data). KYC policies can lead to lengthy onboarding times and thus poor customer experience. Furthermore, it is challenging to keep track and ensure that customer data remains accurate and up-to-date, since it is hard to enforce that customers update their personal details. These reasons deterred exchanges from adopting these policies.
</p>

<p align="justify">
Our project attempts to overcome these challenges by using machine learning technology to combat cryptocurrencies fraud. Machine learning can uncover patterns that may not be noticed by humans. Machine learning can help fill in the information gaps created by cryptocurrency's pseudo-anonymity as certain models can extract information from a blockchain ledger and review the transaction histories between public addressed. The machine learning models we used train the dataset based on the fraudulent activities and its features and predict future unseen crypto activities, determining whether they are fraudulent or not.
</p>

**Basic Facts of Ethereum Dataset**
<p align="justify">
We found our data from a Kaggle dataset <a href="https://www.kaggle.com/datasets/vagifa/ethereum-frauddetection-dataset">(Ethereum Fraud Detection Dataset | Kaggle)</a>. The dataset was collected from Etherscan API and etherscamdb API using REST API and web scraping.
</p>

<p align="justify">
There are a total of 9841 observations (rows) and 50 variables (columns). The variables’ types include integer, float and string (object).
</p>

<img width="337" align="center" alt="image" src="https://user-images.githubusercontent.com/77267689/201003671-5af77586-cf25-4768-b39b-097707657639.png">

**Fraud Analytics Models Used**
<br>
Logistic Regression
<br>
XGBoost
<br>
Fully Connected Neural Network
