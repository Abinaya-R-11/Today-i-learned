### 1. What is a lambda function?
            A lambda function is a small, anonymous (unnamed) function in python that can take any number of arguments, but can only one expression.

### 2. Syntax comparison
-**Regular function:**

'''python

def square(x):

  return x*x

 -**Lambda equivalent:**
 
 square = lambda x:x*x

 ### 3. Practical use case: Sorting with key
           Lambda functions are especially handy inside sorted() or pandas .apply():

#### sorting pairs by the second value

 pairs = [(1,'apple'), (2,'banana'), (3,'cherry')]
 
 sorted_pairs = sorted(pairs, key=lambda item:item[1])
 
 print(sorted_pairs)
  
