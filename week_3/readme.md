# DSC-DSU | Python Bootcamp 2020 | Week 1

Paste questions and brief writeup here

class_list = dict() 
data = input('Enter RollNumber , Age , Name , Marks sepreated by":" ') 
temp = data.split(':') 
class_list[temp[0]] = int(temp[4]) 
 
for key, value in class_list.items(): 
	print('RollNumber: {}, Age: {},Name: {},Marks: {},'.format(key, value)) 