# Big-Data-Programming
Printing ODD Values:
for i in range(1,50):
    if i%2!=0:
        print('Odd Number: ',i)
        
 Printing List values with empty list:
newlist = []
for x in range(0,10):
    num=input('Enter values: ')
    newlist.append(num)
print(newlist)

Printing values greater than 10:
newlist = []
count=0
for x in range(0,10):
    num=input('Enter values: ')
    newlist.append(num)
    if int(num)>10:
        count=count+1
print('Values greater than 10 in list: ',count)

