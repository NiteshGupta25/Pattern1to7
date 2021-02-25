# Pattern1to7

# Pattern 1------------------------------------------------------------

n=int(input("enter n value:"))

for i in range(n):

    print('*',end='')
    
    Output:
    
    enter n value : 5
    
 * * * * * 
            
  # Pattern 2 ----------------------------------------------------------------  
  
  n=int(input("enter n value:"))
  
   for i in range(n):

    print('*'*n)
    
    output :
    
    enter n value: 5
    
*****
*****
*****
*****
*****

 # Pattern 3 ------------------- ---------------------------------------------
 
 n=int(input("enter n value:"))
 
 for i in range(n):

    print((str(n)+' ')*n)
    
    output:
    
    enter n value: 4
    
4 4 4 4 
4 4 4 4 
4 4 4 4 
4 4 4 4 

 # Pattern 4 ------------------------------------------------------------------------------------------
 
 n=int(input("Enter No. of Row--->"))
 
for i in range(n):

    print((str(i+1)+'')*n)
    
 Enter No. of Row---> 4
 
1111
2222
3333
4444
 
  # Pattern 5 ------------------------------------------------------------------------------------------
  
  n=int(input("Enter No. of Row---------->"))
  
for i in range(n):

  print(('A')*n)
 
Enter No. of Row---------->5

AAAAA
AAAAA
AAAAA
AAAAA
AAAAA

 # Pattern 6 ------------------------------------------------------------------------------------------
 
 n=int(input("Enter No. of Row---------->"))
 
for i in range(n):

    print((chr(65+i)+' ')*n)
    
    Enter No. of Row----------> 4
    
A A A A 
B B B B 
C C C C 
D D D D 
    
 # Pattern 7 ------------------------------------------------------------------------------------------
 
 n=int(input("Enter No. of Row---------->"))
 
for i in range(n):

  for j in range(n):
  
      print(str(j+1),end='')
      print()
