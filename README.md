# Bank Marketing Project

## Description of the project (Updated June 25, 2025)

![Photo of a piggy bank](https://github.com/thaianle/bank-marketing/blob/readme_update/illustration/piggy-bank-8691201_1280.png "Source: Pixabay")

_Source: [Pixabay](https://pixabay.com/illustrations/piggy-bank-saving-coin-bank-finance-8691201/)_

An ongoing data analysis project using Python, using the [Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing) from the UC Irvine Machine Learning Repository.

The dataset was taken from a telemarketing campaign of a Portuguese bank from May 2008 to November 2010. Based on various factors present in the dataset such as the client's data, how the client was contacted, performance from previous marketing campaigns, and other socio-economic indicators, classification models try to predict whether the client will subscribe to a term deposit or not.

The raw database, directly downloaded from the UCI Machine Learning Repository website in June 2025, is stored in the [data](https://github.com/thaianle/nysed-2024/tree/main/data) folder.

As stated in the website where the data is originally located, there are 4 datasets, each having different sets of features and records. I choose the largest dataset, [```bank-additional-full.csv```](https://github.com/thaianle/bank-marketing/blob/main/data/bank-additional/bank-additional-full.csv), with a volume "very close to the data analyzed" in the original research paper to perform the analysis and run classification models on. More information is available in the [```bank-additional-names.txt```](https://github.com/thaianle/bank-marketing/blob/main/data/bank-additional/bank-additional-names.txt) file.

I used popular Python libraries such as NumPy, Pandas, Matplotlib, and Seaborn to import, process, and analyze the data. For the predictions part, I used different classification models, including K-Nearest Neighbors, Logistic Regression, and Decision Tree. The analysis file can be found in the [bank-marketing.ipynb](https://github.com/thaianle/bank-marketing/blob/main/bank-marketing.ipynb) file.

_Reference:_

Moro, S., P. Rita, and P. Cortez. 2014. Bank Marketing. UCI Machine Learning Repository. https://doi.org/10.24432/C5K306.