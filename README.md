## My courses

### SQL

| Title                                              | Instructor   | Date       | Course duration | Evidence |
| ---------------------------------------------------| -------------|------------|-----------------|----------|
| SQL for beginners - PostgrateSql                   | Rafal Mobilo | 08/01/2021 | 6.5             | [Click](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/SQLBeginners01.21.png?raw=true)
| Introduction & installation 70-761 exam lvl.1      | Rafal Mobilo | 14/01/2021 | 3               | [Click](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/70-761SQL01.21.png?raw=true)
| Querying 70-761 exam lvl.2                         | Rafal Mobilo | 25/01/2021 | 5.5             | [Click](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/70-761_2SQL01.21.png?raw=true)
| Data modification & transactions 70-762 exam lvl.4 | Rafal Mobilo | 08/03/2022 | 5               | [Click](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/70-762SQL03.22.png?raw=true)



### Python
| Title                                              | Instructor       | Date       | Course duration | Evidence |
| ---------------------------------------------------| -----------------|------------|-----------------|----------|
| Python for beginners                               | Rafal Mobilo     | 26/04/2021 | 8               | [Click](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/PythonBeginners04.21.png?raw=true)
| Data Analysis in Python and PANDAS                 | Rafal Mobilo     | 18/05/2021 | 14.5            | [Click](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/DataScience05.2021.png?raw=true)
| ML - Perceptron & Linear Regression                | Rafal Mobilo     | 28/05/2021 | 7.5             | [Click](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/MachineLearning05.21.png?raw=true)
| Python for Time Series Data Analysis               | Jose Portilla    | 07/06/2021 | 15.5            | [Click](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/TimeSeriesSnalysis06.21.png?raw=true)
| Python for ML & DS Masterclass                     | Jose Portilla    | 22/12/2021 | 44              | [Click](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/MLDSMasterclass11.21.png?raw=true)
| PyTorch for Deep Learning with Python Bootcamp     | Jose Portilla    | 08/03/2022 | 17              | [Click](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/PyTorch03.22.png?raw=true)
| Django 4 and Python Developer Masterclass          | Jose Portilla    | 12/02/2022 | 17              | [Click](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/Django02.22.png?raw=true)
| Tensorflow 2 Keras DL Bootcamp                     | Jose Portilla    | 21/03/2022 | 19              | [Click](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/Tensorflow03.22.png?raw=true)
| Credit Risk Modeling in Python                     | 365 Careers      | 21/03/2022 | 7               | [Click](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/RiskModelingPython03.22.png?raw=true)
| Azure Databricks & Spark (Python/SQL)              | Ramesh Retnasamy | 31/03/2022 | 15              | [Click](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/AzureSpark03.22.png?raw=true)


### Certificates
| Title                                              | Reference number | Organization | Date          | Evidence         
| ---------------------------------------------------| -----------------|--------------|---------------|----------
| Certificate of Investment Analyst (CAI)            | 58               | ZMID         | 28.03.2021    | [Click](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/CAI2021.png?raw=true)
| Google Data Analytics                              | HRDXGSVV3RVB     | Google       | 20.04.2022    | [Click](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/googleAnalytics04.22.png?raw=true)

All of the courses I took included assignments to complete and texts to read. Therefore, the length of the courses is not a complete picture of the work I have done.

I spent a lot of time doing my own projects. As it happens in life not everything works out as we would like it to. 

I try to make my projects ambitious and useful. Not all projects were finished because of the time I had, but it doesn't mean I won't come back to them. 


## My projects


### [Project 1: Trader Vic Algorithm](https://github.com/maciej-mlynski/TraderVicProject.git)

Determining trend lines can be very subjective. A properly drawn trend line can make a trader's job much easier. The project presents a tool that automatically draws trend, support and resistance lines based on techniques contained in a book called Trader Vic.

![](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/TV.png?raw=true)

The image shows the trend lines and tunnel breaks automatically generated by the algorithm.
**Proces:**
1. Examines what occurred first. The local maximum or the minium. 
2. Draws long-term trend lines so that no point before the local peak is crossed
3. Draws a tunnel starting from the intersection of the trend line to the lowest point of the candle
4. Looks for intersection points of tunnels
5. The third breakthrough of the line indicates a possible change or continuation of the trend, as in the image above

**Notes:**
- The graph shows the period of discovery of the signals and what happened afterwards to test the effectiveness of the algorithm
- The way I drew the tunnels I presented earlier applies to the specific situation in the picture. There are definitely more possible conditions
- The algorithm also throws out relevant comments about the position trader should take

**The algorithm is not ready yet because it does not have all necessary conditions and does not have signals for closing the positions. In addition there is a capital management system which is not ready yet.**


### [Project 2: Login system & blog](https://github.com/maciej-mlynski/FinancialMill-Maciej.git)

I have created a login system so that users can access our premium tools such as an ebook and credit calculator. The webside is aveliable [here](https://financialmill.pl/premium/index.php)
![](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/LoginSys.png?raw=true)

**Description:**
1. Languages: PHP, HTML and CSS
2. Users can sign in only by email
3. User must pass reCaptcha verification
4. User must agree to the terms of service
5. User must verify email
6. After Login user gets a discount on the ebook and access to the calculator
7. User can delete account whenever he wants

**Notes:**
I decided to use PHP because I didn't know at the time that there was such a thing as Django, where I could write everything with the familiar python syntax


### [Project 3: Mortgage-Calculator](https://github.com/maciej-mlynski/Mortgage-Calculator.git)

The calculator is not an ordinary tool to analyze credit costs. It is more of an interactive presentation that allows the user to understand and consciously choose how to optimize the cost of their mortgage. To see click [here](https://kalkulator-financialmill.herokuapp.com/)

activation code: FinancialMill2022

![](https://github.com/maciej-mlynski/Maciej_Portfolio/blob/main/Images/Calculator.png?raw=true)

**Description:**
1. Evaluates the impact of WIBOR 3M on a mortgage loan
2. Counts the savings from the overpayment of the loan, taking into account the date the overpayments began and any indexation
3. Counts the same as I mentioned earlier in the variant of regular investment of funds in order to pay off the mortgage once
4. Calculates how much, for how long, and at what target percentage you should invest regularly so that the dividend value of your portfolio will cover your loan payment
5. The calculator contains links to articles I have written and icons which expand to describe basic terms to help you understand the topic

**Notes:**
I decided to use Streamlit, which is python freamwork, becouse it is easy to use. The problem is that whenever I wanted to do things my way, I usually encountered limitations and complications from Streamlit. I wanted to save some time thanks to Streamilt's automatic appearance creation, but at the end I waste more time by fixing the errors and deploying app.













### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
