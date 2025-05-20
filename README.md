# 100-Patterns-Printing-using-Python
# Pattern Printing in Python

This README showcases various pattern programs with `n = 5`.

---


**1**

    '''n = int(input("Enter a number:"))
    for i in range(1,n+1):
        print(n*"* ")'''


    Enter a number: 5

    * * * * * 
    * * * * * 
    * * * * * 
    * * * * * 
    * * * * * 

**2**

    n = int(input("Enter a number:"))
    for i in range(1,n+1):
        print(n*(str(i)+" "))

    Enter a number: 5

    1 1 1 1 1 
    2 2 2 2 2 
    3 3 3 3 3 
    4 4 4 4 4 
    5 5 5 5 5 

**3**

    n = int(input("Enter a number:"))
    for i in range(1,n+1):
        for j in range(1,n+1):
            print(j,end=" ")
        print()

    Enter a number: 5

    1 2 3 4 5 
    1 2 3 4 5 
    1 2 3 4 5 
    1 2 3 4 5 
    1 2 3 4 5 

**4**

    n = int(input("Enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for j in l[0:n]:
        print(n*(str(j)+" "))

    Enter a number: 5

    A A A A A 
    B B B B B 
    C C C C C 
    D D D D D 
    E E E E E 

**5**

    n = int(input("Enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(1,n+1):
        for j in l[0:n]:
            print(j,end=" ")
        print()

    Enter a number: 5

    A B C D E 
    A B C D E 
    A B C D E 
    A B C D E 
    A B C D E 

**6**

    n = int(input("Enter a number"))
    for i in range(n,0,-1):
        print(n*(str(i)+" "))

    Enter a number 5

    5 5 5 5 5 
    4 4 4 4 4 
    3 3 3 3 3 
    2 2 2 2 2 
    1 1 1 1 1 

**7**

    n = int(input("Enter a number"))
    for i in range(n,0,-1):
        for j in range(n,0,-1):
            print(j,end=" ")
        print()

    Enter a number 5

    5 4 3 2 1 
    5 4 3 2 1 
    5 4 3 2 1 
    5 4 3 2 1 
    5 4 3 2 1 

**8**

    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    n = int(input("Enter a number:"))
    for i in l[n-1::-1]:
            print((i+" ")*n)

    Enter a number: 5

    E E E E E 
    D D D D D 
    C C C C C 
    B B B B B 
    A A A A A 

**9**

    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    n = int(input("Enter a number:"))
    for i in range(1,n):
        for j in l[n-1::-1]:
            print(j,end=" ")
        print()

    Enter a number: 5

    E D C B A 
    E D C B A 
    E D C B A 
    E D C B A 

**10**

    n = int(input("Enter a number:"))
    for i in range(1,n+1):
        print(i*"* ")

    Enter a number: 5

    * 
    * * 
    * * * 
    * * * * 
    * * * * * 

**11**

    n = int(input("Enter a number:"))
    for i in range(1,n+1):
        print(i*(str(i)+" "))

    Enter a number: 5

    1 
    2 2 
    3 3 3 
    4 4 4 4 
    5 5 5 5 5 

**12**

    n = int(input("Enter a number:"))
    for i in range(1,n+1):
        for j in range(1,i+1):
            print(j,end=" ")
        print()

    Enter a number: 5

    1 
    1 2 
    1 2 3 
    1 2 3 4 
    1 2 3 4 5 

**13**

    n = int(input("enter a number"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(1,n+1):
        for j in l[0:i]:
            pass
        print(i*(j+" "))

    enter a number 5

    A 
    B B 
    C C C 
    D D D D 
    E E E E E 

**14**

    n = int(input("enter a number"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(1,n+1):
        for j in l[0:i]:
            print(j,end=" ")
        print()

    enter a number 5

    A 
    A B 
    A B C 
    A B C D 
    A B C D E 

**15**

    n = int(input("Enter a number:"))
    for i in range(n,0,-1):
        print(i*"* ")

    Enter a number: 5

    * * * * * 
    * * * * 
    * * * 
    * * 
    * 

**16**

    n = int(input("Enter a number: "))
    for i in range(1, n + 1):
        print((str(i)+" ") * (n + 1 - i))

    Enter a number:  5

    1 1 1 1 1 
    2 2 2 2 
    3 3 3 
    4 4 
    5 

**17**

    n =int(input("Enter a number: "))
    for i in range(n,0,-1):
        for j in range(1,i+1):
            print(str(j),end=" ")
        print()

    Enter a number:  5

    1 2 3 4 5 
    1 2 3 4 
    1 2 3 
    1 2 
    1 

**18**

    n = int(input("Enter a numbe: "))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n,0,-1):
        for j in l[n-i]:
            print((j+" ")*i)
            break

    Enter a numbe:  5

    A A A A A 
    B B B B 
    C C C 
    D D 
    E 

**19**

    n = int(input("Enter a numbe: "))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n,0,-1):
        for j in l[0:i]:
            print(j,end=" ")
        print()

    Enter a numbe:  5

    A B C D E 
    A B C D 
    A B C 
    A B 
    A 

**20**

    n = int(input("Enter a number: "))
    for i in range(n,0,-1):
        print((str(i)+" ")*i)

    Enter a number:  5

    5 5 5 5 5 
    4 4 4 4 
    3 3 3 
    2 2 
    1 

**21**

    n = int(input("Enter a number: "))
    for i in range(n,0,-1):
        for j in range(n,n-i,-1):
            print(j,end=" ")
        print()

    Enter a number:  5

    5 4 3 2 1 
    5 4 3 2 
    5 4 3 
    5 4 
    5 

**22**

    n = int(input("Enter a number"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n-1, -1, -1):  
            if i==0:
                print(l[i])
            else:
                print((l[i]+" ")*(i+1))

    Enter a number 5

    E E E E E 
    D D D D 
    C C C 
    B B 
    A

**23**

    n = int(input("Enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n-1,-1,-1):
        for j in range(n-1,(n-i)-2,-1):
            print(l[j],end=" ")
        print()

    Enter a number: 5

    E D C B A 
    E D C B 
    E D C 
    E D 
    E 

**24**

    n = int(input("Enter a number:"))
    for i in range(1,n+1):
        print((n-i)*" "+i*"*")

    Enter a number: 5

        *
       **
      ***
     ****
    *****

**25**

    n = int(input("Enter a number:"))
    for i in range(1,n+1):
        print((n-i)*" "+(str(i))*i)

    Enter a number: 5

        1
       22
      333
     4444
    55555

**26**

    n = int(input("Enter a number:"))
    for i in range(1,n+1):
        print((n-i)*" ",end="")
        for j in range(1,i+1):
            print(j,end="")
        print()

    Enter a number: 5

        1
       12
      123
     1234
    12345

**27**

    n = int(input("Enter a numer: "))
    n =int(input("Enter a number: "))
    for i in range(0,n+1):
        for j in range(1,i+1):
            print((n-i)*" "+str(j),end="")
        print()
    for i in range(0,n+1):
        print(" "*(n-i)+l[i] * (i + 1))

    Enter a numer:  4

        A
       BB
      CCC
     DDDD
    EEEEE

**28**

    n = int(input("Enter a numer: "))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n+1):
        print(" "*(n-i),end="")
        for j in range(i+1):
            print(l[j],end="")
        print()

    Enter a numer:  4

        A
       AB
      ABC
     ABCD
    ABCDE

**29**

    n = int(input("Enter a number:"))
    for i in range(n,0,-1):
        print((n-i)*" "+(i)*"*")

    Enter a number: 5

    *****
     ****
      ***
       **
        *

**30**

    n = int(input("Enter a numer:"))
    for i in range(n,0,-1):
        print((n-i)*" "+str(i)*i)

    Enter a numer: 5

    55555
     4444
      333
       22
        1

**31**

    n = int(input("Enter a number:"))
    for i in range(n+1,0,-1):
        print(((n+1)-i)*" ",end="")
        for j in range(1,i):
            print(j,end="")
        print()

    Enter a number: 5

    12345
     1234
      123
       12
        1
         

**32**

    n = int(input("Enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n,0,-1):
        print((n-i)*" "+i*l[i-1])

    Enter a number: 5

    EEEEE
     DDDD
      CCC
       BB
        A

**33**

    n = int(input("Enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(0,n):
        print(i*" ",end="")
        for j in range(0,n-i):
            print(l[j],end="")
        print()

    Enter a number: 5

    ABCDE
     ABCD
      ABC
       AB
        A

**34**

    n = int(input("Enter a number:"))
    for i in range(1,n+1):
        print((n-i)*" "+i*"*"+"*"*(i-1))

    Enter a number: 5

        *
       ***
      *****
     *******
    *********

**35**

    n = int(input("Enter a number:"))
    for i in range(1,n+1):
        print((n-i)*" "+i*str(i)+str(i)*(i-1))

    Enter a number: 5

        1
       222
      33333
     4444444
    555555555

**36**

    n = int(input("Enter a number: "))
    num = 1  
    for i in range(1, n+1):
        print(" " * (n - i), end="")  
        print(str(num) * num)
        num += 2  

    Enter a number:  5

        1
       333
      55555
     7777777
    999999999

**37**

    n = int(input("Enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    num= 1
    for i in range(0,n):
        print(" "*(n-i),end="")
        print(l[i]*num)
        num+=2

    Enter a number: 5

         A
        BBB
       CCCCC
      DDDDDDD
     EEEEEEEEE

**38**

    n = int(input("Enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    num= 1
    al = 0
    for i in range(0,n):
        print(" "*(n-i),end="")
        print(l[al]*num)
        num+=2
        al+=2

    Enter a number: 5

         A
        CCC
       EEEEE
      GGGGGGG
     IIIIIIIII

**39**

    n = int(input("Enter a number:"))
    for i in range(1,n+1):
        print(" "*(n-i),end="")
        for j in range(1,2*i):
            print(j,end="")
        print()

    Enter a number: 5

        1
       123
      12345
     1234567
    123456789

**40**

    n = int(input("Enter a number:"))
    for i in range(1,n+1):
        print(" "*(n-i),end="")
        for j in range(2*i-1,0,-1):
            print(j,end="")
        print()

    Enter a number: 5

        1
       321
      54321
     7654321
    987654321

**41**

    n = int(input("enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(1,n+1):
        print(" "*(n-i),end="")
        for j in range(0,2*i-1):
            print(l[j],end="")
        print()

    enter a number: 5

        A
       ABC
      ABCDE
     ABCDEFG
    ABCDEFGHI

**42**

    n = int(input("enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(0,n):
        print(" "*(n-i),end="")
        for j in range(2*i,-1,-1):
            print(l[j],end="")
        print()

    enter a number: 5

         A
        CBA
       EDCBA
      GFEDCBA
     IHGFEDCBA

**43*

    n = int(input("Enter a number:"))
    for i in range(0,n):
        print(" "*(n-i),end="")
        for j in range(i,-1,-1):
            print(j,end="")
        for k in range(1,i+1):
            print(k,end="")
        print()

    Enter a number: 5

         0
        101
       21012
      3210123
     432101234

**44**

    n= int(input("enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(1,n+1):
        print(" "*(n-i),end="")
        for j in range(i-1,-1,-1):
            print(l[j],end="")
        for k in range(1,i):
            print(l[k],end="")
        print()

    enter a number: 5

        A
       BAB
      CBABC
     DCBABCD
    EDCBABCDE

**45**

    n = int(input("enter a number:"))
    for i in range(1,n+1):
        print(" "*(n-i),end="")
        for j in range(1,i+1):
            print(j,end="")
        for k in range(i-1,0,-1):
            print(k,end="")
        print()

    enter a number: 5

        1
       121
      12321
     1234321
    123454321

**46**

n = int(input("enter a number:")) l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ" for i
in range(0,n): print(" "*(n-i),end="") for j in range(0,i+1):
print(l[j],end="") for k in range(i-1,-1,-1): print(l[k],end="") print()

**47**

    n = int(input("Enter a number:"))
    for i in range(n,0,-1):
        print((n-i)*" "+i*"*"+"*"*(i-1))

    Enter a number: 5

    *********
     *******
      *****
       ***
        *

**48**

    n = int(input("enter a number:"))
    for i in range(n,0,-1):
        print((n-i)*" "+i*str(i)+(i-1)*str(i))

    enter a number: 5

    555555555
     4444444
      33333
       222
        1

**49**

    n = int(input("enter a nuber:"))
    for i in range(n,0,-1):
        print((n-i)*" "+(2*i-1)*str(2*i-1))

    enter a nuber: 5

    999999999
     7777777
      55555
       333
        1

**50**

    n = int(input("enter a number:"))
    for i in range(n,0,-1):
        print((n-i)*" ",end="")
        for j in range(1,2*i-2):
            print(j,end="")
        print()

    enter a number: 5

    1234567
     12345
      123
       1
        

**51**

    n = int(input("Enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n,0,-1):
        print((n-i)*" "+(2*i-1)*l[i-1])
            

    Enter a number: 5

    EEEEEEEEE
     DDDDDDD
      CCCCC
       BBB
        A

**52**

    n = int(input("Enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n,0,-1):
        print((n-i)*" "+(2*i-1)*l[2*i-2])

    Enter a number: 5

    IIIIIIIII
     GGGGGGG
      EEEEE
       CCC
        A

**53**

    n = int(input("enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n,0,-1):
        print((n-i)*"  ",end="")
        for j in range(0,2*i-1):
            print(l[j],end=" ")
        print()

    enter a number: 5

    A B C D E F G H I 
      A B C D E F G 
        A B C D E 
          A B C 
            A 

**54**

    n = int(input("enter a number:"))
    for i in range(1,n+1):
        print(i*"* ")
    for j in range(n-1,0,-1):
        print(j*"* ")

    enter a number: 5

    * 
    * * 
    * * * 
    * * * * 
    * * * * * 
    * * * * 
    * * * 
    * * 
    * 

**55**

    n = int(input("enter a number: "))
    for i in range(n-1, -1, -1):
        for j in range(n-1, i-1, -1):
            print(j, end=" ")
        print()
    for k in range(1,n):
        for l in range(n-1, k-1, -1):
            print(l, end=" ")
        print()

    enter a number:  5

    4 
    4 3 
    4 3 2 
    4 3 2 1 
    4 3 2 1 0 
    4 3 2 1 
    4 3 2 
    4 3 
    4 

**56**

    n = int(input("enter a number:"))
    for i in range(n-1,-1,-1):
        for j in range(i,n):
            print(j,end=" ")
        print()
    for i in range(1,n):
        for j in range(i,n):
            print(j,end=" ")
        print()

    enter a number: 5

    4 
    3 4 
    2 3 4 
    1 2 3 4 
    0 1 2 3 4 
    1 2 3 4 
    2 3 4 
    3 4 
    4 

**57**

    n = int(input("enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n-1,-1,-1):
        for j in range(n-1,i-1,-1):
            print(l[j],end=" ")
        print()
    for k in range(1,n):
        for m in range(n-1,k-1,-1):
            print(l[m],end=" ")
        print()

    enter a number: 5

    E 
    E D 
    E D C 
    E D C B 
    E D C B A 
    E D C B 
    E D C 
    E D 
    E 

**58**

    n = int(input("enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n-1,-1,-1):
        for j in range(i,n):
            print(l[j],end=" ")
        print()
    for k in range(1,n):
        for m in range(k,n):
            print(l[m],end=" ")
        print()

    enter a number: 5

    E 
    D E 
    C D E 
    B C D E 
    A B C D E 
    B C D E 
    C D E 
    D E 
    E 

**59**

    n = int(input("enter a number:"))
    for i in range(1,n+1):
        print((n-i)*"  "+i*" *")
    for i in range(n-1,1,-1):
        print((n-i)*"  "+i*" *")

    enter a number: 5

             *
           * *
         * * *
       * * * *
     * * * * *
       * * * *
         * * *
           * *

**60**

    n = int(input("enter a number"))
    for i in range(1,n+1):
        print((n-i)*"  ",end="")
        for j in range(n-1,(n-i)-1,-1):
            print(str(j),end=" ")
        print()
    for k in range(1,n):
        print(k*"  ",end="")
        for l in range(n-1,k-1,-1):
            print(str(l),end=" ")
        print()

    enter a number 5

            4 
          4 3 
        4 3 2 
      4 3 2 1 
    4 3 2 1 0 
      4 3 2 1 
        4 3 2 
          4 3 
            4 

**61**

    n = int(input("Enter a number:"))
    for i in range(n,-1,-1):
        print((i)*"  ",end=" ")
        for j in range(i,n):
            print(j,end=" ")
        print()
    for k in range(1,n):
        print(k*"  ",end=" ")
        for l in range(k,n):
            print(l,end=" ")
        print()

    Enter a number: 5

               
             4 
           3 4 
         2 3 4 
       1 2 3 4 
     0 1 2 3 4 
       1 2 3 4 
         2 3 4 
           3 4 
             4 

**62**

    n = int(input("enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n,-1,-1):
        print(i*"  ",end=" ")
        for j in range(i,n):
            print(l[j],end=" ")
        print()
    for k in range(1,n):
        print(k*"  ",end=" ")
        for m in range(k,n):
            print(l[m],end=" ")
        print()

    enter a number: 5

               
             E 
           D E 
         C D E 
       B C D E 
     A B C D E 
       B C D E 
         C D E 
           D E 
             E 

**63**

    n = int(input("enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n-1,-1,-1):
        print(i*"  ",end=" ")
        for j in range(n-1,i-1,-1):
            print(l[j],end=" ")
        print()
    for k in range(1,n):
        print(k*"  ",end=" ")
        for m in range(n-1,k-1,-1):
            print(l[m],end=" ")
        print()

    enter a number: 5

             E 
           E D 
         E D C 
       E D C B 
     E D C B A 
       E D C B 
         E D C 
           E D 
             E 

**64**

    n = int(input("Enter a number:"))
    for i in range(1,n+1):
        print((n-i)*" ",i*("* "))

    Enter a number: 5

         * 
        * * 
       * * * 
      * * * * 
     * * * * * 

**65**

    n = int(input("Enter a number:"))
    for i in range(1,n+1):
        print((n-i)*" "+i*(str(i)+" "))

    Enter a number: 5

        1 
       2 2 
      3 3 3 
     4 4 4 4 
    5 5 5 5 5 

**66**

    n = int(input("enter a number:"))
    for i in range(1,n+1):
        print((n-i)*" ",end="")
        for j in range(1,i+1):
            print(j,end=" ")
        print()

    enter a number: 5

        1 
       1 2 
      1 2 3 
     1 2 3 4 
    1 2 3 4 5 

**67**

    n = int(input("enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(1,n+1):
        print((n-i)*" "+(i)*(l[i-1]+" "))

    enter a number: 5

        A 
       B B 
      C C C 
     D D D D 
    E E E E E 

**68**

    n = int(input("Enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(1,n+1):
        print((n-i)*" ",end="")
        for j in range(0,i):
            print(l[j],end=" ")
        print()

    Enter a number: 5

        A 
       A B 
      A B C 
     A B C D 
    A B C D E 

**69**

    n =int(input("enter a number:"))
    for i in range(n,0,-1):
        print((n-i)*" "+i*"* ")

    enter a number: 5

    * * * * * 
     * * * * 
      * * * 
       * * 
        * 

**70**

    n = int(input("enter a number:"))
    for i in range(n,0,-1):
        print((n-i)*" "+i*(str(i)+" "))

    enter a number: 5

    5 5 5 5 5 
     4 4 4 4 
      3 3 3 
       2 2 
        1 

**71**

    n = int(input("Enter a number:"))
    for i in range(n,0,-1):
        print((n-i)*" ",end="")
        for j in range(i,0,-1):
            print(j,end=" ")
        print()

    Enter a number: 5

    5 4 3 2 1 
     4 3 2 1 
      3 2 1 
       2 1 
        1 

**72**

    n = int(input("enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n,-1,-1):
        print((n-i)*" "+i*(l[i-1]+" "))

    enter a number: 5

    E E E E E 
     D D D D 
      C C C 
       B B 
        A 
         

**73**

    n = int(input("enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n-1,-1,-1):
        print((n-i)*" ",end="")
        for j in range(i,-1,-1):
            print(l[j],end=" ")
        print()

    enter a number: 5

     E D C B A 
      D C B A 
       C B A 
        B A 
         A 

**74**

    n = int(input("enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n,-1,-1):
        print((n-i)*" ",end="")
        for j in range(0,i):
            print(l[j],end=" ")
        print()

    enter a number: 5

    A B C D E 
     A B C D 
      A B C 
       A B 
        A 
         

**75**

    n = int(input("enter a number:"))
    for i in range(n,-1,-1):
        print(i*" "+(n-i)*" *")
    for j in range(1,n+1):
        print(j*" "+(n-j)*" *")

    enter a number: 5

         
         *
        * *
       * * *
      * * * *
     * * * * *
      * * * *
       * * *
        * *
         *
         

**76**

    n = int(input("enter a number:"))
    for i in range(1,n+1):
        print((n-i)*" "+i*(str(i)+" "))
    for j in range(1,n):
        print(j*" "+(n-j)*(str(n-j)+" "))

    enter a number: 5

        1 
       2 2 
      3 3 3 
     4 4 4 4 
    5 5 5 5 5 
     4 4 4 4 
      3 3 3 
       2 2 
        1 

**77**

    n = int(input("Enter a number:"))
    for i in range(1,n+1):
        print((n-i)*" ",end="")
        for j in range(1,i+1):
            print(j,end=" ")
        print()
    for k in range(1,n):
        print(k*" ",end="")
        for l in range(k+1,n+1):
            print(l,end=" ")
        print()

    Enter a number: 5

        1 
       1 2 
      1 2 3 
     1 2 3 4 
    1 2 3 4 5 
     2 3 4 5 
      3 4 5 
       4 5 
        5 

**78**

    n = int(input("Enter a number:"))
    for i in range(1,n+1):
        print((n-i)*" ",end="")
        for j in range(1,i+1):
            print(j,end=" ")
        print()
    for k in range(n-1,0,-1):
        print((n-k)*" ",end="")
        for l in range(1,k+1):
            print(l,end=" ")
        print()

    Enter a number: 5

        1 
       1 2 
      1 2 3 
     1 2 3 4 
    1 2 3 4 5 
     1 2 3 4 
      1 2 3 
       1 2 
        1 

**79**

    n = int(input("Enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(1,n+1):
        print((n-i)*" "+i*(l[i-1]+" "))
    for j in range(n-1,-1,-1):
        print((n-j)*" "+j*(l[j-1]+" "))

    Enter a number: 5

        A 
       B B 
      C C C 
     D D D D 
    E E E E E 
     D D D D 
      C C C 
       B B 
        A 
         

**80**

    n = int(input("Enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(1,n+1):
        print((n-i)*" ",end="")
        for j in range(0,i):
            print(l[j],end=" ")
        print()
    for k in range(1,n+1):
        print(k*" ",end="")
        for m in range(k,n):
            print(l[m],end=" ")
        print()

    Enter a number: 5

        A 
       A B 
      A B C 
     A B C D 
    A B C D E 
     B C D E 
      C D E 
       D E 
        E 
         

**81**

    n = int(input("enter a number:"))
    for i in range(n):
        print(" "*(n-i-1)+ "*"+" "*(i*2-1)+("*"if i>0 else ""))

    enter a number: 5

        *
       * *
      *   *
     *     *
    *       *

**82**

    n = int(input("enter a number:"))
    for i in range(1,n+1):
        print(" "*((n+1)-i)+str(i)+" "*(i*2-3)+(str(i) if i>1 else ""))

    enter a number: 5

         1
        2 2
       3   3
      4     4
     5       5

**83**

    n = int(input("enter a number:"))
    for i in range(0,n):
            print(" "*(n-i-1)+str(n-i)+" "*(i*2-1)+(str(n-i) if i>0 else ""))

    enter a number: 5

        5
       4 4
      3   3
     2     2
    1       1

**84**

    n = int(input("enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(0,n):
            print(" "*(n-i-1)+l[i]+" "*(i*2-1)+(l[i] if i>0 else ""))

    enter a number: 5

        A
       B B
      C   C
     D     D
    E       E

**85**

    n = int(input("enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(1,n+1):
            print(" "*(n-i)+l[n-i]+" "*(i*2-3)+(l[n-i] if i>1 else ""))

    enter a number: 5

        E
       D D
      C   C
     B     B
    A       A

**86**

    n = int(input("enter a number:"))
    for i in range(n,-1,-1):
        print(" "*(n-i)+ "*"+" "*(i*2-1)+("*"if i>0 else ""))

    enter a number: 5

    *         *
     *       *
      *     *
       *   *
        * *
         *

**87**

    n = int(input("enter a number:"))
    for i in range(n,0,-1):
        print(" "*(n-i)+str(n-i+1)+" "*(i*2-3)+(str(n-i+1) if i>1 else ""))

    enter a number: 5

    1       1
     2     2
      3   3
       4 4
        5

**88**

    n = int(input("Enter a number:"))
    for i in range(0,n):
        print(i*" "+str(n-i)+" "*((n-i)*2-3)+(str(n-i) if i<n-1 else ""))

    Enter a number: 5

    5       5
     4     4
      3   3
       2 2
        1

**89**

    n = int(input("Enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n):
        print((i)*" "+l[i]+" "*((n-i)*2-3)+(l[i] if i<n-1 else ""))

    Enter a number: 5

    A       A
     B     B
      C   C
       D D
        E

**90**

    n = int(input('enter a number:'))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n,0,-1):
        print((n-i)*" "+l[i-1]+" "*(i*2-3)+(l[i-1] if i>1 else ""))

    enter a number: 5

    E       E
     D     D
      C   C
       B B
        A

**91**

    n = int(input("Enter a number"))
    for i in range(n):
        print((n-i)*" "+"*"+(i*2-1)*" "+("*" if i>0 else ""))
    for j in range(n+1):
        print(j*" "+"*"+((n-j)*2-1)*" "+("*" if j<n else ""))

    Enter a number 5

         *
        * *
       *   *
      *     *
     *       *
    *         *
     *       *
      *     *
       *   *
        * *
         *

**92**

    n = int(input("Enter a number:"))
    for i in range(1,n+1):
        print((n-i)*" "+str(i)+(i*2-3)*" "+(str(i) if i>1 else ""))
    for j in range(1,n):
        print(j*" "+str(n-j)+((n-j)*2-3)*" "+(str(n-j) if j<n-1 else ""))

    Enter a number: 5

        1
       2 2
      3   3
     4     4
    5       5
     4     4
      3   3
       2 2
        1

**93**

    n = int(input("Enter a number:"))
    for i in range(n,0,-1):
        print((i-1)*" "+str(i)+(((n-i)*2-1)*" "+(str(i) if i<n else "")))
    for j in range(1,n):
        print(j*" "+str(j+1)+((n-j)*2-3)*" "+(str(j+1) if j<n-1 else ""))

    Enter a number: 5

        5
       4 4
      3   3
     2     2
    1       1
     2     2
      3   3
       4 4
        5

**94**

    n = int(input("Enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n):
        print((n-i)*" "+l[i]+(i*2-1)*" "+(l[i] if i>0 else ""))
    for j in range(n-2,-1,-1):
        print((n-j)*" "+l[j]+(j*2-1)*" "+(l[j] if j>0 else ""))

    Enter a number: 5

         A
        B B
       C   C
      D     D
     E       E
      D     D
       C   C
        B B
         A

**95**

    n = int(input("enter a number:"))
    l = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    for i in range(n-1,-1,-1):
        print(i*" "+l[i]+((n-i)*2-3)*" "+(l[i] if i<n-1 else ""))
    for j in range(1,n):
        print(j*" "+l[j]+((n-j)*2-3)*" "+(l[j] if j<n-1 else ""))

    enter a number: 5

        E
       D D
      C   C
     B     B
    A       A
     B     B
      C   C
       D D
        E

**96**

    n = int(input("enter a number:"))
    for i in range(n):
        print((n-i)*"*"+(i*2)*" "+(n-i)*"*")

    enter a number: 5

    **********
    ****  ****
    ***    ***
    **      **
    *        *

**97**

    n = int(input("enter a number:"))
    for i in range(n,-1,-1):
        print((n-i)*"*"+(2*i)*" "+(n-i)*"*")

    enter a number: 5

              
    *        *
    **      **
    ***    ***
    ****  ****
    **********

**98**

    n = int(input("enter a number:"))
    for i in range(n,-1,-1):
        print((n-i)*"*"+(2*i)*" "+(n-i)*"*")
    for j in range(1,n):
            print((n-j)*"*"+(j*2)*" "+(n-j)*"*")

    enter a number: 5

              
    *        *
    **      **
    ***    ***
    ****  ****
    **********
    ****  ****
    ***    ***
    **      **
    *        *
              
**99**
    n = int(input("enter a number:"))
    for i in range(1,n+1):
        print((n-i)*" "+(i*2-1)*"*"+(n-i)*" "+(n-i)*" "+(i*2-1)*"*")

    enter a number: 5

        *        *
       ***      ***
      *****    *****
     *******  *******
    ******************

**100**
    n = int(input("enter a number:"))
    for i in range(1,n+1):
        print((n-i)*" "+i*"* "+(n-i)*" "+(n-i)*" "+i*"* ")

    enter a number: 5

        *         * 
       * *       * * 
      * * *     * * * 
     * * * *   * * * * 
    * * * * * * * * * * 

