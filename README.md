# reboot-your-brain

>>>import more_itertools
>>>list_ = [1,2,(3,4,[5,6],[7,8])]
>>>print(list(more_itertools.collapse(list_)))

OUTPUT:
  [1,2,3,4,5,6,7,8]
  
 --------------------------------------------------------------- 
 
 >>>t1 = (1,2,3)
 >>>t2 = (10,20,30)
 >>>print(dict(zip(t1,t2)))
 
 OUTPUT:
  {1: 10, 2: 20, 3: 30}
----------------------------------------------------------------

#difference between == and is in python3
>>>a = [1,2,3]
>>>b = [1,2,3]
>>>a == b
True
>>>a is b
False
>>>c = a
>>>c == a
True
>>>a is c 
True
