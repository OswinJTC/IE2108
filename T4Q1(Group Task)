#group work

import random

def arrayMax(A,n):
    
    currentMax = A[0]
    time_executed = 0
    
    for count in range(1,n):
        if A[count] > currentMax:
            time_executed += 1
            currentMax = A[count]
            
    return time_executed
     


#=========================================# 500 times
each_experiment_500 = []

for i in range(500):
    
    arr = []
    for j in range(10):#random array
        arr.append(random.randint(1,10))
        
    each_experiment_500.append(arrayMax(arr, 10))
    
sum = 0   
for item in each_experiment_500:
    sum += item
ave_for_500 = sum/500
    
#=========================================# 1000 times
each_experiment_1000 = []

for i in range(1000):
    
    arr = []
    for j in range(10):#random array
        arr.append(random.randint(1,10))
        
    each_experiment_1000.append(arrayMax(arr, 10))
    
sum = 0   
for item in each_experiment_1000:
    sum += item
ave_for_1000 = sum/1000


#=========================================# 10000 times
each_experiment_10000 = []

for i in range(10000):
    
    arr = []
    for j in range(10):#random array
        arr.append(random.randint(1,10))
        
    each_experiment_10000.append(arrayMax(arr, 10))
    
sum = 0   
for item in each_experiment_10000:
    sum += item
ave_for_10000 = sum/10000

  
    

print(ave_for_500)
print(ave_for_1000)
print(ave_for_10000)    

