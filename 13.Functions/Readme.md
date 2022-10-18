## Functions

Simple Function - Function is defined with the name called 'def' 
         
          def my_function():       #Here my_function() is the name of function, we are assigning a name
              print('Hi')          #Here we are defining what function should do
              
          
           my_function()           #Calling a function, here we are calling my_function(), It will print 'Hi'
          
   
## Arguments 

           def name(a):            #Defining a function 
               print(a)
               
               
           name('kishore')
           
           
## Mupltiple Arguments
 ##Strings
           def Names(name1, name2):
                print(Names)
               
           Names('yaswanth', 'kishore')

Mathematical 

           def Addition(x, y):
               print(x+y)
               
           Addition(5, 9)
           
           
           def Multiplication(a, b):
               print(a*b)
               
           Multiplcation(5, 4)
           
## Return_Statement - Saving the Output from function in to Variable

           def Addition(x, y):
               return x+y
               
           output = Addition(5, 9)
           print(output)

## Default Arguments

          def region_names(a = 'No_Input', b = 'No_Input'):
              print(a, b)

          region_names('Asia')
          
          
## Targeted Parameters
          def portfolio(name, age, current_position):
              print('my_name_is: ',name,' Iam',age,'years_of_old','and Iam :',current_position)
              
          portfolio('kishore', 25, ' devops engineer')
          
          portfolio(age='25', name='yaswanth', current_position ='data analyst')
          
          
## 
