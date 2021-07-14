## 1. What is the difference between = and ==?  
  

## 2. Can I leave out the colon in an if, while, or for statement? Yes/No  

 

## 3. Should I use tab characters to indent my code? Yes/No  



## 4. Compose a program that takes three integer command-line arguments and writes 'equal' if all three are equal, and 'not equal' otherwise.  


## 5. What is the value of j after each of the following code fragments is executed?  

a.	j = 0  
	for i in range (0, 10) :  
	j += i  



b.	j = 1  
	for i in range (0, 10) :  
	j += j  



c.	for j in range (0, 10) :  
	j += j  

  

## 6. What are m and n after the following code is executed?  

n = 123456789  
m = 0  
while n != 0:  
	m = (10 * m) + (n % 10)  
	n //= 10  
	print (m)  
	print (n)  



## 7 What does this code do?
f = 0  
g = 1  
for i in range (0, 10):  
	f = f + g  
	g = f - g  
	print (f)  



## Bonus: Is there an example for when the following for and while loops are not equivalent?  
for variable in range(start, stop):
				statement1
				statement2
				...



variable = start
while variable < stop:
		statement1
		statement2
		...
		variable +=1


