class BankAccount:

  def __init__(self, account_number, account_holder_name, initial_balance=0.0):
    self.__account_number = account_number
    self.__account_holder_name = account_holder_name
    self.__account_balance = initial_balance

  def deposit(self, amount):
    if amount > 0:
      self.__account_balance += amount
      print(f"Deposited ₹{amount}. New balance: ₹{self.__account_balance}")
    else:
      print("Invalid deposit amount. Please deposit a positive amount.")

  def withdraw(self, amount):
    if 0 < amount <= self.__account_balance:
      self.__account_balance -= amount
      print(f"Withdrew ₹{amount}. New balance: ₹{self.__account_balance}")
    else:
      print("Invalid withdrawal amount or insufficient balance.")

  def display_balance(self):
    print(f"Account Holder: {self.__account_holder_name}")
    print(f"Account Number: {self.__account_number}")
    print(f"Account Balance: ₹{self.__account_balance}")


# Example usage:
if __name__ == "__main__":
  # Create an instance of the BankAccount class
  my_account = BankAccount("10461976413", " Pandian", 200000)
  # Deposit money
  my_account.deposit(60000.0)

  # Withdraw money
  my_account.withdraw(10000.0)

  # Display the account balance
  my_account.display_balance()
