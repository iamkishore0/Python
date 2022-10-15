## Classes 
Classes are defined as Blueprint or Overall picture, 
Funtions can be called easily with classes names
 
    class func1:          #func1 is name of the class
      def names(self):     #functions defined under classes expects atleast one arguement, here self is the arguement, We can give any name for arguement
        print('kishore')
                   
     a = func1()
     a.names()
                
     class func2:
       def my_name(self, r):
         print('my name is:', r)
         
      b = func2()
      a.my_name('kishore')

## Variables in Classes
      
      class var:
        a = 6
        b = 'India'
        c = '8.1'
        d = True
        
      print(var.a)
      print(var.b)
      print(var.c)
      print(var.d)
      
      
      class var:
       def xyz(self, x, y):
        self.x = x
        self.y = y
        self.z = 9


      b = var()
      b.xyz(6,7)
      print(b.x,b.y,b.z)

## The __init__ Constructor

    class abc:
      def __init__(self,a,b):
        print(a+b)
        
    abc(6, 9)

## Inheritance
    class X:
     def first(self):
      print('this is class 1')
    class Y(X):
     def second(self):
      print('this is class 2')
     
    a = X()
    a.first()
    
    b = Y()
    b.second()
    
    b.first()
    
    
