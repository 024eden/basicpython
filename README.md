# basicpython
# This program adds two numbers

'''num1 = 1.5
num2 = 6.3

# Add two numbers
sum = num1 + num2

# Display the sum
print('The sum of {0} and {1} is {2}'.format(num1, num2, sum))'''
'''

name = "Thoudam Samananda Singh"
age = 21
x = 2 
y = 3

print("name",name,"Age",age,"Sum ",x+y)
percentage = 85.75  
print("Score: {:.2f}%".format(percentage)) 
a = 20 
b = 30 
if x > y:
  print("x is grater than y")
else:
  print("Y is greater than  or equal to x") 
# For the loop 
fruits =["Nice","banana","cherry"]
for x in fruits:
  print(x,end=" ")
#while loop 
i = 0
while i < 4 :
 print(i,end=" ")
 i +=1
#data structure in python
#lists 
#tuples
# sets 
#dictionaries
bucket =['tester ', 'nice ','good ']
print("bucket[1] ",bucket[1])
bucket.append('bad')
print("bucket=",bucket)
num_list=[1,2,3,4]
sum_nums=sum(num_list)
print("total ",sum_nums)'''

# Function to sum all even numbers in a given range
def sum_even_numbers_in_range(start, end):
    total_sum = 0
    
    for num in range(start, end + 1):
        # If the number is odd, skip to the next iteration
        if num % 2 != 0:
            continue
        
        # Add the even number to the total sum
        total_sum += num
        
        # Example break condition (can be modified as needed)
        # Break if the sum exceeds a certain limit (optional)
        if total_sum > 1000:
            break

    return total_sum

# Example usage
start = 1
end = 16
result = sum_even_numbers_in_range(start, end)
print(f"The sum of even numbers from {start} to {end} is: {result}")
