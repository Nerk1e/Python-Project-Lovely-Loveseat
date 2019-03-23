# Python-Project-Lovely-Loveseat
Python Programming Project from CodeAcademy: Processing and creation of receipts for your customers


```markdown

#Creating item descriptions

lovely_loveseat_description = "Lovely Loveseat. Tufted polyester blend on wood. 32 inches high x 40 inches wide x 30 inches deep. Red or white."

#Creating price for item
lovely_loveseat_price = 254.00

#Making another item description
stylish_settee_description = "Stylish Settee. Faux leather on birch. 29.50 inches high x 54.75 inches wide x 28 inches deep. Black."

#Adding price
stylish_settee_price = 180.50

#Making another item description
luxurious_lamp_description = "Luxurious Lamp. Glass and iron. 36 inches tall. Brown with cream shade."

#Adding Price
luxurious_lamp_price = 52.15

#Variable with sales tax
sales_tax = .088

#Setting Customer's total to zero for a starting total amount
customer_one_total = 0

#Making Itemization as a filler and quotation to help Print
customer_one_itemization = ""

#Customer is buying the lovely loveseat
customer_one_total = lovely_loveseat_price

#Adding the description of Loveseat to match purchase
customer_one_itemization = lovely_loveseat_description

#Adding another item, this time it is a lamp to the final price
customer_one_total += luxurious_lamp_price

#Adding the itemization of the lamp to the other itemization of the loveseat
customer_one_itemization += luxurious_lamp_description

#Making a variable for customer total with sales tax
customer_one_tax = customer_one_total * sales_tax

#Adding variable to the customer total
customer_one_total += customer_one_tax

print("Customer One Items:")
print(customer_one_itemization)

print("Customer One Total:")
print(customer_one_total)



```
