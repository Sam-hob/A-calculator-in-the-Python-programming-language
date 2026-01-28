numberOne=eval(input("Enter number one :"))
numbertwo=eval(input("Enter number two :"))
operation =input("Enter operation :")
if (operation == '+') :
      print (numberOne+numbertwo)
elif (operation == '-') :
    print (numberOne-numbertwo)
    
elif(operation == '*'):
    print (numberOne*numbertwo)
    
elif(operation == '/'):
    print (numberOne/numbertwo)

else:
    print ("The operation does not exist")
