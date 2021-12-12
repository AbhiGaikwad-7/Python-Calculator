# Python-Calculator


a=int(input("Enter first no="));
b=int(input("Entet second no="));
choice=str(input("Enter your choice="));

if choice=='+':

  c=a+b;

  print("Addition="+str(c));
  
elif choice=='-':

	c=a-b;
	print("Subtraction="+str(c));
	
elif choice=='*':

	c=a*b;
	print("Multiplication="+str(c));
	
elif choice=='/':

	c=a/b;
	print("Division="+str(c));
	
elif choice=='%':

	c=a%b;
	print("Modulo="+str(c));
	
else:

      print("Incorrect choice!!")
