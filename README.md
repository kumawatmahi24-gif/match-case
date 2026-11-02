# switch-case calculator in python.
num1=float(input("Enter the first number:"))
operator=input("Enter the operator (+, -, *, /)")
num2=float(input("Enter the second number:"))

match operator: # checks the value
  case="+": # matches a particular value
    print("result:",num1+num2)
  case="-":
    print("result:",num1-num2)
  case="*":
    print("result:",num1*num2)
  case="/":
    if num2!=0:
    print("result:",num1/num2)
else:
    print("cannot divide by zero")
case_: #default case if nothing matches
  print("Invalid operator")
    
