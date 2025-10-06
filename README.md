# Bank-GUI
This is a small application that simulates a bank. You are an administrator and the client at the same time. The administrator can add debit and/or credit card entries while the client can withdraw a certain amount from the balance. The usage guide is given below- 

  - You can add a client debit card entry after filling out client name, card ID, bank account, issuer bank, balance amount fields in customer details tab and pin number field in debit card tab.
  - You can add a client credit card entry after filling out client name, card ID, bank account, issuer bank, balance amount fields in customer details tab and CVC number and interest rate field in credit card tab.
  - You can withdraw a certain amount from the debit card tab. The remaining balance and date of withdrawal is shown after clicking the withdraw button.
  - You can set credit limit and grace period from the credit card tab. A message is shown after clicking the set limit button displaying new credit limit and new grace period.
  - You can cancel credit limit of a credit card after clicking the cancel button.

The features are given below-

  - You cannot add the same debit card or credit card twice.
  - You can switch from ligh to dark theme from the setting tab.
  - You can re-enter the values of card ID and pin number after which a message appears stating that the entered values were the correct ones as in they are the values which were entered before erasing the fields. After entering a valid withdrawal amount, you can press Enter, and a message will appear confirming that the values entered were correct, along with the displayed information.
  - A message box warning the user appears if the user has entered incorrect data or have just left certain fields empty.
  - You cannot withdraw without creating a debit card first.
  - You cannot withdraw more than what you have in your debit card.
  - You cannot set credit limit which is 2.5 times greater than your balance amount.

Run BankGUI.java to get started.
