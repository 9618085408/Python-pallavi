def calculate_bill(units):
  TARIFF_RATE_FIRST_100 = 3.50
  TARIFF_RATE_NEXT_100 = 4.00
  TARIFF_RATE_AFTER_200 = 5.20
  
  if units <= 100:
    bill = units * TARIFF_RATE_FIRST_100
  elif units <= 200:
    bill = 100 * TARIFF_RATE_FIRST_100 + (units - 100) * TARIFF_RATE_NEXT_100
  else:
    bill = 100 * TARIFF_RATE_FIRST_100 + 100 * TARIFF_RATE_NEXT_100 + (units - 200) * TARIFF_RATE_AFTER_200
  
  return bill

units = 250
bill = calculate_bill(units)
print(f"Electricity bill for {units} units is {bill} rupees.")
