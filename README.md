# Polindrom.py

# Polindrom Program


string=input("Enter the string :")
reversed=string[::-1]                   # Slicing the string
if string==reversed:
    print("It is Polindrom")
else:
    print("It is not Polindrom")
