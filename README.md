# Hello-World-Project-2
def calculate_change(amount):
#Defining each value of a coin and dollar (change caluculator) into cents using Python
dollar_value = 100
quarter_value = 25
dime_value = 10
nickel_value = 5
penny_value = 1

# Calculate the value/number of each coin

dollars = amount // dollar_value
amount% = dollar_value
quarters = amount // quarter_value
amount% = quarter_value
dimes = amount // dime_value
amount% = dime_value
nickels = amount // nickel_value
amount% = nickel_value
pennies = amount // penny_value

# The dictionary of the result is the return of the amounts
return{
  'dollars': dollars,
  'quarters': quarters,
  'dimes': dimes,
  'pennies': pennies
  }
  






