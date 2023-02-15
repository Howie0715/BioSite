---
title: Coding-Midterm
type: page
description: 
---
# 1 我的位置在哪裡
```
#By Turtle

n=int(input())
r=n/12
c=n%12
if c==0:
  r=r-1
  c=12
print(int(r+1),c)
```

# 2 韓信點兵
```
#By Brian

for soldier in range(10000, 20001):
  if (soldier%13==5 and soldier%17==7 and soldier%19==11):
    print(soldier)
```
