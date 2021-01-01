import random
from string import ascii_letters
from string import digits

RandNum = "0"
password = ""
Length = input("Type length of password: ")
Length = int(Length)

for x in range(Length):
  Type = random.randint(1,2)
  if Type == 1:
    RandNum = random.choice(digits)
    ConvertedNum = str(RandNum)
    password = password + ConvertedNum
  elif Type ==2:
    password = password + random.choice(ascii_letters)

print (password)