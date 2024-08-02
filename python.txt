#today we have learned about some basics of python--> single line comment

'''
 this is a multi line
 comment
'''

#declaring a variable

a=3
b=5.5
c='ramesh'
d="mohit"

#print function

print("hello world")
print(a)
print(type(a))

#for input

e=input("Enter your name")#-->takes value as string
f=int(input("Enter the value of f")) #--> takes value as integer
g=eval(input("Enter the value of g"))#--> takes the value as integer or float

#to add two numbers

h=int(input("Enter the value of h"))
i=int(input("Enter the value of i"))
sum=h+i
print(sum)

#to add two strings

first_name=input("Enter your first name")
last_name=input("Enter last name")
space=" "
name=first_name+space+last_name
print(name)