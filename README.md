# Loan Qualifying

The goal of this challenge is to add a function allowing the user to save their qualifying loan data as a new cSV file.

## Technologies

- Python 3.7+
- Libraries: 'sys', 'fire', 'questionary',
- Operating syste: Was built on macOS - however, should work on Windows and Linux as well

## Installation Guide

Install the following dependencies in your terminal window

```python
pip install fire
pip install questionary
```

## Usage

1. Navigate to the directory where you cloned the github repository.
2. Run the following command in your terminal window.
```python
python app.py
```
3. When asked for a file path, enter `data/daily_rate_sheet.csv`
4. Input your respective answers to the questions.
5. Enter a file path where you want to save your new csv file. Also enter the name of the file. Example: `data/my_qualifying_loans.csv`
