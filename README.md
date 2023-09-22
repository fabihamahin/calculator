# CALCULATOR WITH CHOICE OF OPERATION FROM USER.

def add(num1,num2):
  return(num1+num2)
def sub(num1,num2):
  return(num1-num2)
def mul(num1,num2):
  return(num1*num2)
def div(num1,num2):
  return(num1/num2)
def floor_div(num1,num2):
  return(num1//num2)


print("----------------------------")
print("SELECT AN OPERATION")
print("----------------------------")
print("""1.ADDITION
2.SUBTRACTION
3.MULTILPICATION
4.DIVISION
5.FLOOR DIVISION
""")

choice=int(input("enter your choice: "))
num1=int(input("enter your first number: "))
num2=int(input("enter your second number: "))

if choice==1:
  result= add(num1,num2)
  print(result,"is the addition")
elif choice==2:
  result= sub(num1,num2)
  print(result,"is the subtraction")
elif choice==3:
  result= mul(num1,num2)
  print(result,"is the multiplication")
elif choice==4:
  result= div(num1,num2)
  print(result,"is the division")
elif choice==5:
  result= floor_div(num1,num2)
  print(result,"is the floor division")
else:
  print("-----INVALID OPTION SELECTED-----")
