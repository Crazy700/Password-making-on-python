import random 

lowwer = "abcdefghijklmnopqrsuvwxyz"
upper = "ABCDEFGHIJKLMNOPQRSUVWXYZ"
NUMBER = "1234567890"           
symbol = "()/#_[]"

add = lowwer + upper + NUMBER + symbol     
length = 9         
password ="".join(random.sample(all,length))
   
print(The Password You Generated is :",password)
