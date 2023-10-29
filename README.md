# Exploratory-Data-Analysis-of-Kenya-s-Mobile-Money-Payments-Data
An EDA Project related to Kenya's Mobile Money Payments Data executed in Python. 

![Mobile Payments Mpesa](https://github.com/Ogombo-collins/Exploratory-Data-Analysis-of-Kenya-s-Mobile-Money-Payments-Data/blob/main/EDA%20of%20Mobile%20Money%20Payments%20in%20Kenya/Mobile%20Payments%20Mpesa.jpg)

## Mobile Money Payments in Kenya

In Kenya, mobile money payments is ubiquitous as beer(_**cold Tusker**_) is to an Kenyan football fanatic. The cradle of mobile payments can be traced to Kenya, when Safaricom (Kenya's leading telecommunications network) gave birth to M-Pesa in 2007. 

Back then, the goal of the newborn was facilitate sending of money to friends and family residing in rural areas. The newborn's growth, 15 years later has resulted to:

- More than 604,000 active agents operating across the Democratic Republic of Congo (DRC), Egypt, Ghana, Kenya, Lesotho, Mozambique and Tanzania
- More [than 51 million customers](https://www.vodafone.com/about-vodafone/what-we-do/consumer-products-and-services/m-pesa) across seven countries in Africa 
- Over $314 billion in transactions per year


**Mobile Money Providers in Kenya**

According to the Central Bank of Kenya (CBK), there are 3 major mobile money providers in Kenya: 
- M-PESA 
- Airtel Money 
- T-cash 


**Features of Mobile Money Payments in Kenya**
 
Some of the features of mobile money payments in Kenya are:

- **Interoperability**: Mobile money customers can send and receive money across diferent networks in real time, thanks to the full [interoperability of mobile money services]( https://www.centralbank.go.ke/wp-content/uploads/2023/02/Kenyas-Payments-Journey.pdf) that was announced by the Central Bank of Kenya in September 2022.
- **International remittances**: Mobile money customers can also send and receive money from abroad through various international remittance partners, such as WorldRemit, Western Union, MoneyGram, and PayPal.
- **Financial inclusion**: Mobile money has enabled millions of Kenyans who do not have bank accounts or have limited access to banking services to access financial services such as savings, loans, insurance, and investments through their mobile phones.
- **Government payments**: Mobile money has also facilitated the payment of taxes, fees, fines, and other government services by citizens and businesses [through platforms such as KRA iTax](https://www.nelito.com/blog/everything-you-need-to-know-about-mobile-money-in-kenya.html.), eCitizen, and Huduma Number.
- **Innovation and growth**: Mobile money has driven innovation and growth in various sectors of the economy, such as agriculture, health, education, and e-commerce, by providing a safe, secure, and affordable way of paying for goods and services.


# Exploratory Data Analysis

Exploratory data analysis involves investigating and summarizing key insights and main characteristics linked to the data. The process provides answers to significant questions that arise when processing(cleaning) the data.



**Goals of Exploratory Data Analysis**

Key goals looking to be achieved by implementing EDA include:

- Discovering the underlying structure of the dataset
- Extract patterns, anomalies and trends in the dataset
- Test hypotheses and validate assumptions about the data
- Forecast what problems could be solved by insights extracted from the data

**Benefits of Exploratory Data Analysis**

Conducting EDA helps data scientists,machine learning engineers and data analysts in various ways. The advantages of EDA include:

1. Aquiring insights into [underlying trends and patterns](https://www.knowledgehut.com/blog/data-science/eda-data-science)
2. Increase understanding of data features and how they relate to each other
3. Optimize data-driven decsions by improving data understanding
4. Deriving better questions that are relvenat to our data and business challenge.

The key elements that will be discussed in our EDA of Kenyan Mobile Payments dataset include:

- Dataset Profile
- Types of Exploratory Data Analysis
- Exploratory Data Analysis Process


## Dataset Profile

**Dataset content**: The dataset shows  monthly data on the number of active agents, registered mobile money accounts, and agent cash in and out transactions in Kenya from January 2007 to August 2023.

**Source of Data**: Data is published by Central Bank of Kenya (CBK), the regulatory authority for mobile payments in Kenya. You can access the data by clicking [here](https://www.centralbank.go.ke/national-payments-system/mobile-payments/). Once you click the link,the data can be exported to Excel or CSV files, copied or converted to PDF files.

**Data Accuracy**: It is collected and published by CBK.

**Data Format**: For this task, the data is in CSV file format.

**Data features**: Columns present in the dataset are year, month, active agents, total registered mobile money accounts, total agent cash in cash out volume and total agent cash in cash out value.

**Data Features Meaning:**

1. Year: Annual fiscal year mobile money transactions occur in Kenya
2. Month: Monthly data for mobile money transactions
3. Total registered mobile money accounts: Number of users who have registered mobile money accounts 
4. Total agent cash in cash out volume: Quantity of mobile money transctions  as per records of mobile money agents. **Mobile money agents** are small mobile phone stores or retail locations—which allow users to deposit and withdraw in-person. Cash in represent deposits and cash out represent cash withdrawals
5. Total cash in cash out value: Monetary value of all mobile money transactions that occured in Kenya from January 2007 to August 2023


## Types of Exploratory Data Analysis

Types of Exploratory data analysis can be cetgorized into two major categories:

- Graphical EDA versus Non-graphical EDA
- Core Types of EDA based on Graphical and Non-garphical EDA


### Graphical EDA versus Non-graphical EDA

Exploratory data analysis can be done [graphically or non-graphically](https://www.ibm.com/topics/exploratory-data-analysis#:~:text=Exploratory%20data%20analysis%20(EDA)%20is,often%20employing%20data%20visualization%20methods.). One paints a picture behind the numbers while the other does not lie. 

a) **Graphical exploratory data analysis:**

Graphical EDA  entails use of graphs to visualize the data and identify patterns that may not be discernible from the raw data.  It helps in displaying the data, describing the distribution of data and relationships between variables present in the dataset.

Some of the common charts/visualizations used in graphical EDA include:
1. Histograms
2. Line graphs 
3. Box plots 
4. Heatmaps 
5. Scatterplots 
6. Pie charts 
7. Bar graphs
8. Contingency tables

Developing exploratory visualizations is the cornerstone of graphical EDA.

b) **Non-graphical exploratory data analysis:**

Non-graphical EDA involves [use of statistical techniques ](https://analyticsindiamag.com/exploratory-data-analysis-functions-types-tools/) to explore the data. It involves computing summary statistics such as measures of central tendency (mean, median, mode), measures of dispersion (variance, standard deviation), and correlation coefficients between variables present in a raw dataset.

Patterns and insights that cannot be easily deduced from graphical EDA can be obtained via non-graphical EDA.


## Exploratory Data Analysis Process

The key steps executed in our Exploratory Data Analysis Process include:

1. Data Collection: Sourcing the data from different sources, verifying accuracy and storing it in the approriate structure
2. Importing Python libraries
3. Reading Dataset: Loading dataset into the notebook as a Pandas DataFrame
4. Data Understanding:  Inspecting the structure of the dataset with the aim of undertsanding the shape of our dataset, features(variables),data types, missing values and duplicated values
5. Data Pre-processing: Depending on results of understanding the dataset, we can clean and wrangle our dataset
6. Univariate Analysis: Graphically and non-graphically
7. Multivariate Analysis: Graphically and non-graphically
8. Answering Key Questions linked to the dataset


 Analysis was done on Jupyter notebook. You can access it [here](https://github.com/Ogombo-collins/Exploratory-Data-Analysis-of-Kenya-s-Mobile-Money-Payments-Data/blob/main/EDA%20of%20Mobile%20Money%20Payments%20in%20Kenya/notebook.ipynb)


## Conclusion

Exploratory Data Analysis process is the cornerstone for any data analysis project. It facilitates understanding of the data structure, identification of trends, patterns and outliers. EDA can be performed using graphical or non-graphical techniques.

**Growth of Mobile Payments in Kenya**

Based on the EDA performed on mobile payments data, several insights regarding the growth of mobile payments in Kenya were obtained. 

They include:

_Note: The growth of mobile money payments timeline is 17 years(January 2007 to August 2023)_



1.  The number of active agents in Kenya increased by **334,419**. This represents a percentage increase of **108,931.30%**.
2.  The number of registered mobile money accounts in Kenya increased by **77.53 Million**. This represents a percentage increase of **369,326.40%**.
3. The volume of mobile money transactions in Kenya increased by **208.59 million**. This represents percentage increase **96,016.60%**.
4. The monetary value of mobile money transactions in Kenya increased by **KES 722.46 billion**. This represents a percentage increase of **1.12 Million%**.


 
