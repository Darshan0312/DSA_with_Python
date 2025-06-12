# Algorithmic Complexity

### -> Efficiency in Programming

1.Time
2.Space

## Techniques to mesaure the Time efficiency

##### Techniques
-> Measure the time to execute.
-> Counting Operations Involved.
-> Abstract notion of order of growth.

#### 1.Measuring Time

Example:

import time

start = time.time()

for i  in range(1,101):
    print(i)

print(time.time()-start)


#### Problems with this apporoch
-> Different time for different algorithm = Good
-> Time varies if implimentation chnages = Not Good 
-> Different machines different time = NOt Good 
-> Does not work for extrmely small input = Not Good 
-> Time varies for different inputs , but cant't establish a relationship = Not Good 


