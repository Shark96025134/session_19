#Error

#amt = 10

if (amt >20):
    print ("Eligible to purchase")


if (amt <20):
    print ("Not Eligible")

#---------------------------------------------------------------------------------#

#Exception

num = 100

result = 100/0


print("The result is:",result)

#---------------------------------------------------------------------------------#

a = [1,2,3]

try:
    
	print("Second element = %d"%(a[1]))
    
	print("Fourth element = %d"%(a[3]))


except:
    
	print("An Error Occoured")

#---------------------------------------------------------------------------------#    

#try with else clause

def fun(a,b):
   
   try:
        c=((a+b)/(a-b))
   
   except ZeroDivisionError:
        print("a/b is 0")
   
   else:
       print(c)


fun(2,3)

fun(3,3)

#---------------------------------------------------------------------------------#

#finally

try:
   
   k = 10/5
    k = 5/5

except ZeroDivisionError:
    print("Values cannot be divided by zero")
    
else:
    print("Else Block Executes")
    print(k)
    
finally:
    print("This Block Always executes")
    #---------------------------------------------------------------------------------#
