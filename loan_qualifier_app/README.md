# Loan Qualifier Application

Asks the users for their personal financial data. Once entered, the program will return how many, and which banks will qualify this user for a loan. The data the user needs to provide is credit score, amount of monthly debt, total monthly income, desired loan amount, and home value. 

---

## Technologies

This project leverages python 3.7 with the following packages:

**[fire](https://github.com/google/python-fire)** - For the command line interface, help page, and entry-point.

**[questionary](https://github.com/tmbo/questionary)** - For interactive user prompts and dialogs

---

## Installation Guide

Before running the application first install the following dependencies:

```python
pip install fire
pip install questionary
```

---

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```

You will be prompted to enter the file path to the data sheet you'd like to work with:

![Which path to open?](images/which_path.png)

Type the name of the csv file (daily_rate_sheet.csv) you would like to work with:

![csv file we'd like to open](images/data_sheet.png)

---

You will then be prompted to enter your credit score:

![What's your credit score?](images/credit_score.png)

Enter a credit score of 700, like this:

![Credit Score of 700](images/score_700.png)

---

Next, you will be prompted to enter your monthly debt:

![Monthly Debt Promp](images/user_debt.png)

Enter a monthly debt amount of $2,500:

![Enter Debt of $2500](images/debt_2500.png)

---

After that, you will be asked to enter a monthly income amount for the user:

![Monthly Income Prompt](images/user_income.png)

Enter a monthly income amount of $5,000:

![Enter Income of $5000](images/income_5000.png)

---

You will then be prompted to enter the amount of the desired loan:

![Desired Loan Amount Prompt](images/loan_amount.png)

Enter a desired loan amount of $20,000:

![Desired Loan Amount of $20,000](images/loan_amount_20000.png)

---

Finally, you will be prompted to enter the value of your home:

![Value of User's Home](images/home_value.png)

Enter a home value of $250,000:

![Home Value of $250,000](images/home_value_250000.png)

---

The application will inform you of the user's monthly debt-to-income ratio, the loan-to-value ratio, and **most importantly**, how many loans the user qualifies for:

![How the result of the program should look](images/final_results.png)

Once the program runs and the number of qualifying loans is displayed, the program ends.

---

## Contributors

**Created by:** Tony Landero<br>
**Email Adress:** mr.landero@gmail.com

---

## License

MIT