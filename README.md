# Python-Programs
#https://www.facebook.com/permalink.php?story_fbid=176900637335830&id=100050476833546
# subscribed by Sutanu Panda
Add any python programs here num = int(input("Enter a number: ")

sum = 0 

temp = num while temp > 0: 
   digit = temp % 10 
   sum += digit ** 3 
   temp //= 10 
if num == sum: 
print(num,"is an Armstrong number") 
else:
print(num,"is not an Armstrong number")
