## Study on the probability of payment of a credit requested by a client

**Table of Contents**


1.   [Installation](#Installation)
2.   [Project Motivation](#Project-Motivation)
3.   [Data](#File-Descriptions)
4.   [File Descriptions](#File-Descriptions)
5.   [Results](#Results) 
6.   [Licensing, Authors,and Acknowledgements](#Licensing-,-Authors-,-and-Acknowledgements)

## Installation

It is not necessary to include any additional libraries to those already installed in the Anaconda environment. Everything was developed with Python 3.


## Project Motivation

The main motivation for this project was to carry out a theoretical review of the main classification and regression models in machine learning. The algorithms studied were:

1. Logistic regression
2. Naive Bayes
3. Decision trees
4. Random Forest


**Business Context**. Online peer-to-peer lending has made the practice of borrowing and lending easy. In this form of lending, borrower can simply fill out an online form and get a loan approved. The information provided solely by a borrower is prone to exaggeration and distortion, especially when it comes to income. Every P2P lending company relies on a well-designed procedure that rejects borrowers with a high chance of not paying off their debts.

Rejecting anyone without a verified source of income is a relevant policy that lending platforms can roll out to help reduce the rate of bad loans.Therefore, it is proposed to determine which are the most relevant variables to help the company make the decision to give the loan to a certain client.



## Data

The data is downloaded from [LendingClub (LC) Statistics](https://www.lendingclub.com/info/download-data.action) and it contains all loans issued from 2007 - 2012 along with their current loan status (fully paid or charged off). There are ~50 variables that describe the borrowers and the loans; for the sake of reducing complexity, the company has already performed a pre-screening of these variables based on existing analyses from LendingClub to select nine relevant variables, such as annual income, LendingClub credit grade, home ownership, etc. *Note: We get the data from course materials of DS4A correlation*


## Licensing, Authors,and Acknowledgements

