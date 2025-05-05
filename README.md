# pythonlearning
This is  for  the learning the python for data science
<br> This is basic HTML which is used to Change the line
<br> Author- Aditya
<br> lets make the pyton easy 

#BODMAS and operator precedence rule first multiplication then addition
#arthmetic operators( +,-,*,/,//,**,%))
#// is used for the floor division 
#and ** is used for the power
#% is used for the modulus
#floor division is used for the division of two numbers and the result is the floor of the division
#onyl the inetger part is considered
#7//2=3, 49//7=7, 50//7=7
#** power operator is used for the power of a number
#2**10=1024, 3**3=27, 4**2=16
#% modulus operator is used for the remainder of the division
#5%4=1, 10%3=1, 10%2=0


#comparison operators( ==,!=,>,<,>=,<=)

# == is used for the equality gives true or false
# if 5==5 then true, if 5==6 then false
# != is used for the inequality gives true or false
# if 5!=5 then false, if 5!=6 then true
# > is used for the greater than gives true or false
# if 5>5 then false, if 5>6 then false, if 5>4 then true
# < is used for the less than
# >= is used for the greater than or equal to
# <= is used for the less than or equal to


# assignment operators( =,+=,-=,*=,/=,//=,%=,**=)
# = is used for the assignment of a value to a variable
# += is used for the addition of a value to a variable
# Eg a=5, a+=5, a=a+5, a=10
# -= is used for the subtraction of a value from a variable
# Eg a=5, a-=10
#a=5
#a-=19
#my  guess is a=a-19, a=-14



#Logical operators (and,or,not)
#print(5>3 and 5>2) true
#print(5>3 or 5>2) true
#print(not(5>3)) false


#Strings operators   
# + is used for the concatenation of two strings
# * is used for the repetition of a string
# [] is used for the indexing of a string
# [:] is used for the slicing of a string
# in is used for the membership of a string
# not in is used for the non membership of a string
# r"" is used for the raw string
# """ is used for the multi line string
# '' is used for the single line string
# "" is used for the single line string
# % is used for the formatting of a string
# .format() is used for the formatting of a string
#what 
# .join() is used for the joining of a string
# .split() is used for the splitting of a string
# .replace() is used for the replacing of a string
# .upper() is used for the upper case of a string
# .lower() is used for the lower case of a string
#  .capitalize() is used for the capitalization of a string
# .title() is used for the title case of a string
# .swapcase() is used for the swap case of a string
# .strip() is used for the stripping of a string
# .lstrip() is used for the left stripping of a string
# .rstrip() is used for the right stripping of a string
# .count() is used for the counting of a string
# .find() is used for the finding of a string
# .index() is used for the indexing of a string
# .startswith() is used for the starting of a string



#import random
#print(random.randint(1,100))

from typing import Counter


x='india'
print('teple'> 'tpa')# no of the characters is compared each character is compared:( OUtput:false) 
print('aand'> 'aande'): output: False
# no of the characters is compared each character is compared
y='python'
print(y[0]) output=p
print (y[-1])# this starts from the end of the string
#negative indexing output:n
print (y[-2])  output:o
print (y[-3])  output: h
print(len(y))  length:=6

#week 2
#variable needs to be declared with the purpose of storing the data. this will help the use of the data in the program.
#variable is a container for storing data.
#variable needs to be self explanatory and use of the comment is neccsary.
#variable is a name given to a memory location.
#this is  include the comment . it is good programming practice.

DYNAMIC TYPING
#we are trying to understand the dynamic typing in python.
#a=10
#b=5
#c=a/b# as soon as the number is divided the result is float

# RULES FOR VARIABLE NAMES
#you  cant  use keyword as a variable name. eg if,else,for,while,break,continue,return,def,class,import,from,as,pass,del,global,nonlocal,assert,try,except,finally,raise,with,yield,lambda,async
# only the underscore is allowed in the variable name. eg a_,_a,a_1,_1a
# variable name should not start with a number. eg 1a,1_a
# case sensitive. eg a,A,a1,A1


#MULTIPLE ASSISGNMENT of variables
#x,y,z,a,b,c=1,2,3,4,5,6 in this case the number of variables and the number of values should be same.
#print(x,y,z,a,b,c)  output=1 2 3 4 5 6
#swap can be done by using the multiple assignment
#x,y=1,2
#x,y=y,x
# the output will be x=2,y=1


#how to delete a variable
#x1=9
#print(x1) output=9
#del x1
#print(x1), this will give an error because the variable is deleted

#shorthand operator
#x=10
#x+=10 this is same as x=x+10, this helps to reduce the number of lines of code
#we can use the same for the other operators like -,*,/,//,**,%
#count*=10
#use the artimetic before the assignment operator
#this is same as count=count*10

#find 
#print('apha'.find('a'))# this will give the index of the first occurance of the character .. output=0
#print('apha'.find('a',1))# this will give the index of the first occurance of the character after the index 1..output=3
#print('apha' in 'apha')# this will give true
#print('apha' not in 'apha')# this will give false
