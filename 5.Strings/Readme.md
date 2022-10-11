## Slicing
    a = 'Hello World' 
    
    #Access H in Hello world
     print (a[0])        #Indexing starts from 0 in python
     print (a[-1])       #From back, it will be -1 and not -0
     print (a[0:3])      #3 is not counted
     print (a[4:])       #prints to the end
     print (a[:5])       #prints from begining up to 5
     print(a[::])        #prints every thing
     print(a[::-1])      #Entire string will get reversed
     
     
     
## Concatenation
     a = 'Hello'
     b = 'World'
     
     c = a+b
     
     print(c)
     print(a+a)
     print(a+a+b+b)
     print(a+b+a+b)
     print(a*3)
     print(a*5)
     print(c*6)
     
## Concatenation with Data Conversions
     a = 'my name is: '
     b = 25
     
     c = a+b        #error, Concatenating an integer with string is not possible   
     c = a+str(b)   #converting int to string
     print(c)
     
     
## Format method
    region = 'Iam from {}'
    b = 'Asia'
    output = region.format(a)
    print(output)
    
    
    region = 'are you from {}, or {} or {}'
    a = 'USA'
    b = 'UK'
    c = 'India'
    output = region.format(a, b, c)
    print(output)

## Quotes issue

    a = "my name is "kishore""   #gives error
    
    a = 'my name is "ksihore"'
    a = "my name is /"ksihore"/"
    
## 
     
     
