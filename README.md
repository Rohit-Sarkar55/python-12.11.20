# python-12.11.20
n=input("Enter a string\n")
x=n.split(" ")
a=len(x)
print("no of words:\n",a)
c=0
v=0
p=0
for i in n:
	if((i>='a' and i<='z') or (i>='A' and i<='Z')):
		if(i=='a' or i=='e' or i=='i' or i=='o' or i=='u' or i=='A' or i=='E' or i=='I' or i=='O' or i=='U'):
			v=v+1
		else:
			c=c+1
	else:
		p=p+1

print("\n no of vowels: \n",v)
print("\n no of consonants: \n",c)
print("\n punchuations: ",p)


C
x=input("Enter a number\n")
print(x*3)
If the given no is 25
Output will be as:252525
In python whenever we take input by default
It is taken as a string unless we cast it to 
another datatype.So here it is taking 25 as
a string and the expression 'x*3' is helping
the string variable 'x' 3 times.


D
Python allows us to implement a Switch Case in two notable ways.

. Switch case using a dictionary
The idea behind a dictionary is to store a key-value pair in the memory
Let’s take an example to better understand the process of creating switches ourselves.

Example
Suppose you wish to write a piece of code which returns the season corresponding to a certain input.
1.You will start off by creating separate functions for each case that you wish to handle.
[def spring():
  return "Spring"
def summer():
  return "Summer"
def autumn():
  return "Autumn"
def winter():
  return "Winter"]
2.The next step is to create the dictionary.
[switch_case = {
  1: spring,
  2: summer,
  3: autumn,
  4: winter
}]
3.The last step is to simply create a function which will take as input an integer and will automatically invoke the corresponding function after the dictionary lookup.
def switch(x):
  return switch_case.get(x, default)()
3.The last step is to simply create a function which will take as input an integer and will automatically invoke the corresponding function after the dictionary lookup.
def switch(x):
  [return switch_case.get(x, default)()]



B
a=0
b=1
c=0
n=input("Enter the upper range of the series:")	
	while(c<=n):
	c=a+b
	a=b
	b=c
	d=a+b
	x=c+1
	for x in range d:
		if(x<=n):
		print(x)
		else:
		break
