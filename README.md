# Week3
Python Zybook Week3 - Type



#################################### 3.11 ###########################################

base_char = input()
head_char = input()

row1 = '      ' + head_char
row2 = base_char + base_char + base_char + base_char + base_char + base_char + head_char + head_char
row3 = base_char + base_char + base_char + base_char + base_char + base_char + head_char + head_char + head_char



print(row1)
print(row2)
print(row3)
print(row2)
print(row1)

#################################### 3.12 ###########################################

phone_number = int(input())

phone_tem = phone_number
phone_tem1 = int(phone_tem/10000000) #get800
phone_tem2 = int((phone_tem%10000000)//10000) #8005551212 > 5551212 > get555
phone_tem3 = phone_number %10000 #1212


print(f'({phone_tem1}) {phone_tem2}-{phone_tem3}') 


#################################### 3.13 ###########################################


caffeine_mg = float(input())


#caffeine_mg1 = caffeine_mg / 2
#caffeine_mg2 = caffeine_mg / 4
#caffeine_mg3 = caffeine_mg / 16


print(f'After 6 hours: {caffeine_mg/2:.2f} mg\nAfter 12 hours: {caffeine_mg/4:.2f} mg\nAfter 24 hours: {caffeine_mg/16:.2f} mg')


#################################### 3.14 ###########################################

current_price = int(input())
last_months_price = int(input())

change_price = current_price - last_months_price
monthy_mort = (current_price * 0.051) / 12.
''' Type your code here. '''
  
print(f'This house is ${current_price}. The change is ${change_price} since last month.\nThe estimated monthly mortgage is ${monthy_mort:.2f}.')


#################################### 3.15 ###########################################

num1 = float(input())
num2 = float(input())
num3 = float(input())
num4 = float(input())

your_value1 = num1 * num2 * num3 * num4
your_value2 = (num1 + num2 + num3 + num4) / 4
#your_value3 = int(your_value1)
#your_value4 = int(your_value2)

print(f'{your_value1:.0f} {your_value2:.0f}\n{your_value1:.3f} {your_value2:.3f}')



