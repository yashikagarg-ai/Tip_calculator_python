# Tip_calculator_python
bill = float(input("What was the total bill? : ₹"))
tip_percentage = int ( input ("How much tip would you like to give? 10 , 12 , 15 ?" ))
people = int(input ( " How many people to split the bill?"))
tip_as_decimal = tip_percentage / 100
total_tip_amount = bill * tip_as_decimal
total_bill = bill + total_tip_amount
amount_per_person = total_bill / people
final_amount = round(amount_per_person,2)
print(f"Each person should pay : ₹{final_amount}")
