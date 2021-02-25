# Pattern1to7

# Pattern 1---------

n=int(input("enter n value:"))

for i in range(n):

    print('*',end='')
    
  # Pattern 2 --------- 
  
  n=int(input("enter n value:"))
  
   for i in range(n):

    print('*'*n)

 # Pattern 3 ---------
 
 n=int(input("enter n value:"))
 
 for i in range(n):

    print((str(n)+' ')*n)
    

 # Pattern 4 ---------
 
 n=int(input("Enter No. of Row--->"))
 
for i in range(n):

    print((str(i+1)+'')*n)

 
  # Pattern 5 -----------
  
  n=int(input("Enter No. of Row---------->"))
  
for i in range(n):

  print(('A')*n)
 

 # Pattern 6 ---------
 
 n=int(input("Enter No. of Row---------->"))
 
for i in range(n):

    print((chr(65+i)+' ')*n)
    
 # Pattern 7 ------------
 
 n=int(input("Enter No. of Row---------->"))
 
for i in range(n):

  for j in range(n):
  
      print(str(j+1),end='')
      print()
