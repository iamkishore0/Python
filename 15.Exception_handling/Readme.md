## Exception Handing 
   To handle errors
   
    x = 5
    y = 9
    z = 'Hello'
    
    print(x/z)    #Error
    
    try:
      print(x/z)
    except:
      print('Operation not possible')
