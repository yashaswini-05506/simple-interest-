# simple-interest-
calculating simple interest
# Simple Interest Calculator

# Input values
principal = float(input("Enter the principal amount (P): "))
rate = float(input("Enter the annual interest rate (R) in %: "))
time = float(input("Enter the time period (T) in years: "))

# Calculate simple interest
simple_interest = (principal * rate * time) / 100

# Display result
print(f"\nSimple Interest = ₹{simple_interest:.2f}")
