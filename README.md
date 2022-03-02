# orderInIf
This is an example of the importance of how certain statements are listed based on order.


# It is important how the statements are listed in an if statement.
# When Python finds a statement that fits, it will ignore the rest of the statement and move on.

def printCategory(age):
    if age < 18:
        print("Child")
    elif age > 65:
        print("Senior")
    else:
        print("Adult")

printCategory(56)

# Try other numbers, and change the Child and Adult categories around.
