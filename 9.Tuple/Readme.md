## Tuple
    # List is defined with Square [ ]
    # Tuple is defined with ()
     
     a = [5, 2.5, True, 'xyz']
     type(a)
     
     b = (5, 2.5, True, 'xyz')
     type(b)

## Slicing operations are same for Tuple
     b = (5, 2.5, True, 'xyz')
     b[0]
     b[2]
     b[::-1]
     len(b)
     
## Tuples is immutable - we cannot alter the content in Tuple
     b = (5, 2.5, True, 'xyz')
     
     b.append(99) #Error
     b.pop()      #Error
     
     #Example: Where can we use Tuple, Government ID proof number is the best example for Tuple, 
               Where ID Proof number is standard and never changed for a person
