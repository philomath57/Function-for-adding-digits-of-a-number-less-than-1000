# Function-for-adding-digits-of-a-number-less-than-1000
In this python program, a number which should be less 1000 would be required to be entered by the user and the functions provides the sum of the digits of the numbers present in that given number
def sum(num):
  s=0
  if num<1000:
    for i in range (3):
      d=num%10
      num=num//10
      s=s+d
    print(s)
  else:
    print('Please enter number less than 1000')
sum(6596)
