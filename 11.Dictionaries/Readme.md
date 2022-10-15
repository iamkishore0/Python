## Dictionaries
   Dictionaries are defined as key and values
   
         x = {'Region':'USA',
              'Vehicle':'four wheeler',
              'Brand':'Benz',
              'Model':'R1'
             }
        
         type(a)

## Accessing Dictionary
       print(x['Region'])
       print(x['vehicle'])
       print(x['Brand'])
       print(x['model'])
       
  
## Adding Data to Dictionary

       x['Manfacturing_Year'] = '2009'
       print(x)

## Manipulating Values
   Chaning value of Brand 'Benz' to 'Audi'
   
       x['Brand'] = 'Audi'
       
## Removing a value
 
       x.pop('Region')
       print(x)
       
## Empty entire directory
       x.clear()
       print(x)
      
## Delete variable
       del a
