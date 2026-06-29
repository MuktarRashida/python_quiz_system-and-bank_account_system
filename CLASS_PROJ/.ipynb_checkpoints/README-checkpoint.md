PROJECT NAME:  General bank account and savings account

HOW IT WORKS:
created an account with name and balance
user deposited an amount
user withdrawed an amount
the user account information displayed
savings account, with interest added to balance

CHALLENGES:
created the attributes self.name = name and self.balance = balance in __init__method.
initially in created create account() method, i created a dictionary that stores the attributes to name and balance
in deposit() method, was able to access the value self.balance, amount was added
in withdrawal() method, wasnt able to access the value self.balance, after analyzing the problem and printing out the value of the dict self.balance, i saw the amount was not updated instead the attribute self.balance was updated. updating the balance only the attribute self.balance changed.

SOLUTION:
what i wanted was create a variable that holds the information that i can update self.balance in. since it did'nt work, i thought the class object already holds it, the dictionary was unnecessary. i removed the dictionary and the create account method() and used self.balance as the only source for account balance.

PROJECT NAME: Quiz_question

CHALLENGES:
I set my self.s which is score to 20, my scoring system added 10 points for each correct answer and subtracted 5 points for incorrect answer. Because my score already started at 20, the final percentage score was incorrect. for three questions, if all are incorrect got 96 which is higher than expected.

SOLUTION:
To solve this issue i set self.s to 0 and appended all answer to 1, so if all question is incorrect, final score will be 1. This ensured the final score reflected user users performance.

CHALLENGES:
Another was displaying incorrect users answer in my method result tracker(), wanted all correct and incorrects answer side by side in a list.
i appended the user answer/ inputed answer to self.qu in class method listed(). When answers are accessed in result_tracker() method, only correct answers were returned.

SOLUTION:
To solved this i traced self.qu in listed() method, saw that i appended user answer only if condition that checked for correct answers then i appended it in else condition also. this ensured user correct or incorrect answers were stored and displayed.







