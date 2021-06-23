from random import randint

heads = 0
tails = 0 

for i in range(10):
  x = randint(0, 1)
  if x == 0:    
      print("heads")
      heads+=1
  else:
      print("tails")
      tails+=1
