
# **PROGRAMMING FOR PROBLEM SOLVING**

##ESC-18105 
## NAME-*SIDHANT JINDAL*
## ROLL NO-*1914109*
## BRANCH-*CIVIL*
## SECTION-*CE(B2)*
![LOGO](https://blog.coachingkaro.org/wp-content/uploads/2019/07/logo.jpg)
## **DEPARTMENT OF CIVIL ENGENEERING**
# **GURU NANAK DEV ENGENEERING COLLEGE,LUDHIANA**



------------------------------------------------------------------------------------------------------------------------

# 1.PROGRAM TO PRINT HELLO WORLD

         include<stdio.h>
         void main()
         {
         puts("hello world\n");
         }
        
## OUTPUT OF PROGRAM         
         
         hello world
--------------------------------------------------------------------------------------------------------------------------------
# 2.PROGRAM TO PRINT MULTIPLICATION TABLE

          #include <stdio.h>
           int main()
           {
           int a, b ;
           printf("enter the number=",a);
           scanf("%d", &a);
           for(int b=1;b<=10;b++)
           {
           printf("%d x %d=%d\n", a, b, a*b);
           }
           return 0;
           }

## OUTPUT OF PROGRAM

             enter the number=12
               12 x 1=12
               12 x 2=24
               12 x 3=36
               12 x 4=48
               12 x 5=60
               12 x 6=72
               12 x 7=84
               12 x 8=96
               12 x 9=108
               12 x 10=120
               
 -------------------------------------------------------------------------------------------------------------------------
 
 # 3.PROGRAM TO ADD 2 NUMBERS
 
          #include<stdio.h>
           int main()
          {
          int a, b, c;
          printf("Enter two numbers to add\n"); 
          scanf("%d%d", &a, &b);
          c = a + b;
          printf("Sum of the numbers = %d\n", c);
          return 0;
          }

## OUTPUT OF PROGRAM

         Enter two numbers to add
                      12
                      12
         Sum of the numbers = 24
         
 ------------------------------------------------------------------------------------------------------------------------------
 # 4.PROGRAM FOR ARITHMATIC OPERATIONS
              #include<stdio.h>
               int main()
              { 
              int a, b, c;
              printf("Enter two numbers\n"); 
              scanf("%d%d", &a, &b);
                c = a + b;
              printf("Sum of the numbers = %d\n", c);
                 c=a-b;
              printf("Diff of 2 numbers=%d\n",c);
                 c=a*b;
              printf("product of 2 numbers=%d\n",c);
              return 0;
              }

## OUTPUT OF PROGRAM

           Enter two numbers
               12
               15
           Sum of the numbers = 27
           Diff of 2 numbers=-3
           product of 2 numbers=180
----------------------------------------------------------------------------------------------------------------------------------------
# 5.PROGRAM TO PRINT A TO Z

        #include<stdio.h>
         int main()
        {
         char c;
         for(char c='A';c<='Z';c++)
         {
          printf("%c \n",c);
          }
          return 0;
          }

## OUTPUT OF PROGRAM

                  A 
                  B 
                  C 
                  D 
                  E 
                  F 
                  G 
                  H 
                  I 
                  J 
                  K 
                  L 
                  M 
                  N 
                  O   
                  P 
                  Q 
                  R 
                  S 
                  T 
                  U 
                  V 
                  W 
                  X 
                  Y 
                  Z

--------------------------------------------------------------------------------------------------------------------------------
# 6.PROGRAM TO FIND DIVIDEND AND DIVISOR

       #include <stdio.h>
        double main()
        {
        int a,b;
        double c,d;
        printf("enter dividend=",a);
        scanf("%d",&a);
        printf("enter divisor=",b);
        scanf("%d",&b);
          c=a/b;
        printf("\n quotient=%0.2f\n",c);
          d=a % b;
       printf("reminder=%0.2f\n",d);
       return 0;
       }
 ## OUTPUT OF PROGRAM
            enter dividend=124
            enter divisor=12

             quotient=10.00
             reminder=4.00
-----------------------------------------------------------------------------------------------------------------------------------
# 7.PROGRAM TO CHECK EVEN ODD NUMBER
  
  
         #include<stdio.h>
         int main()
         {
         int a;
         printf("enter the number=", a);
         scanf("%d", &a);
         if (a%2==0)
         printf("number is even\n\n");
         else
         printf("number is odd\n\n");
         return 0;
         }
 ## OUTPUT OF PROGRAM
         enter the number=12
         number is even
 -------------------------------------------------------------------------------------------------------------------------------------- 
 
 # 8.PROGRAM TO FIND MAXIMUM NUMBER
            
            
            #include<stdio.h>
             int main ()
             {
             int a,b,ret;
             printf("enter two numbers=",a,b);
             scanf("%d%d",&a,&b);
             if (a>b)
             ret=a;
             else 
             ret=b;
              printf("Anwser=%d\n",ret);
              return ret;
              }
## OUTPUT OF PROGRAM 

      enter two numbers=15
                        14
                 Anwser=15
 -----------------------------------------------------------------------------------------------------------------------------------
 
 # 9.PROGRAM TO FIND MINIMUM OF TWO NUMBERS
              
              
              #include<stdio.h>
               int main ()
              {
               int a,b,ret;
               printf("enter two numbers=",a,b);
               scanf("%d%d",&a,&b);
               if (a<b)
               ret=a;
               else 
               ret=b;
               printf("Anwser=%d\n",ret);
               return ret;
              }

## OUTPUT OF PROGRAM

                 enter two numbers=14 
                   200
                  Anwser=14
 -----------------------------------------------------------------------------------------------------------------------------
  
  # 10.PROGRAM TO PRINT CALCULATOR
                
                
                #include<stdio.h>
                  void main()
                 {
              puts("\n\
                     _______________\n\
                    | 1 | 2 | 3 |   |\n\
                    |___|___|___| + |\n\
                    | 4 | 5 | 6 |   |\n\
                    |___|___|___|___|\n\
                    | 7 | 8 | 9 | - |\n\
                    |___|___|___|___|\n\
                    |     0     | * |\n\
                    |___________|___|\n");
                   }

## OUTPUT OF PROGRAM


          _______________
         | 1 | 2 | 3 |   |
         |___|___|___| + |
         | 4 | 5 | 6 |   |
         |___|___|___|___|
         | 7 | 8 | 9 | - |
         |___|___|___|___|
         |     0     | * |
         |___________|___|
         
-------------------------------------------------------------------------------------------------------------------

# 11.PROGRAM TO PRINT FACE

              #include<stdio.h>
               void main()
             {
            puts("________________"); 
            puts("|  XXXXXXXXX   |");
            puts("| (  ^    ^ )  |");
            puts("| (  0    0 )  |");
            puts("|  \\    |  /   |");
            puts("|   \\   = /    |");
            puts("|    \\__ /     |");
            puts("|       |      |");
            puts("|_______|______|\n");
            }
            
  ## OUTPUT OF PROGRAM

              ________________
              |  XXXXXXXXX   |
              | (  ^    ^ )  |
              | (  0    0 )  |
              |  \    |  /   |
              |   \   = /    |
              |    \__ /     |
              |       |      |
              |_______|______|
              
----------------------------------------------------------------------------------------------------------------------------------

# 12.PROGRAM TO PRINT LINE OF ANY LENGTH

          #include<stdio.h>
           int main()
           {
           int a;
           printf("enter length of line=");
           scanf("%d",&a);
           for(int  i=1;i<=a;i++)
           {
           printf("_____");
           }
           printf("\n\n");
           return 0;
            }

## OUTPUT OF PROGRAM
                 
                 enter length of line=12
                  ____________________________________________________________
----------------------------------------------------------------------------------------------------------------------------------------
# 13.PROGRAM TO FIND SUN OF N NATURAL NUMBERS
         
         #include<stdio.h>
         int main()
         {
         int n,sum;
         printf("enter number=",n);
         scanf("%d",&n);
         sum=n*(n+1)/2;
         printf("\n%d\n\n",sum);
         return 0;
         }

## OUTPUT OF PROGRAM

         enter number=12

         78

----------------------------------------------------------------------------------------------------------------------------
# 14.PROGRAM TO FIND PERIMETER,AREA AND VOLUME OF RECTANGLE

                #include<stdio.h>
                int main()
               {
                int a,b,c,peri,area,vol;
                printf("enter length,bredth and height of rectangle", a,b,c );
                scanf("%d%d%d",&a ,&b ,&c);
                  peri= 2*(a+b);
                  area=a*b;
                  vol=a*b*c;
                printf("\nperimeter=%d\n\n", peri);
                printf("area=%d\n\n",area); 
                printf("volume=%d\n\n", vol);
                return 0;
                }

## OUTPUT OF PROGRAM

                    enter length,bredth and height of rectangle12
                                 14
                                 14

                     perimeter=52

                     area=168 

                     volume=2352
   ----------------------------------------------------------------------------------------------------------------------------
  # 15.PROGRAM TO FIND PERIMETER ANSD AREA OF CIRCLE
  
             #include<stdio.h>
              int main()
             {
              float a,pi=22/7.0,peri,area;
              printf("enter radius=");
              scanf("%f", &a);
              peri=2*pi*a;
              area=pi*a*a;
              printf("Perimeter of circle=%.2f\n", peri );
              printf("Area=%.2f\n", area);
              return 0;
             } 
 ## OUTPUT OF PROGRAM
 
      enter radius=7
      Perimeter of circle=44.00
      Area=154.00
-----------------------------------------------------------------------------------------------------------------------------------
# 16.PROGRAM TO FIND POWER OF A NUMBER
         
         #include<stdio.h>
         int main()
         {
         int base,exp;
         int result=1;
         printf("\nEnter base number\n");
         scanf("%d",&base);
         printf("Enter exponent");
         scanf("%d",&exp); 
         while (exp!=0)
         {
         result *=base;
         exp--;
         }
         printf("awnser=%d\n", result);
         return 0;
         }
## OUTPUT OF PROGRAM

         Enter base number
         2
         Enter exponent5
         awnser=32
-----------------------------------------------------------------------------------------------------------------------------------
# 17.PROGRAM TO CHECK PRIME NUMBER
        
        
        #include<stdio.h>
         int main()
        {
         int n;

        printf("enter number");
        scanf("%d",&n);

        for(int i=1;i<n;i++)
          {
                if(n%i!=0)
          {  printf("no is prime");
                             break;  }
           else
            {
                printf("no is not prime");
                                    break;  }
                  }

                 return 0;
          }
## OUTPUT OF PROGRAM

           enter number15
           no is not prime
---------------------------------------------------------------------------------------------------------------------------------------

# 18.PROGRAM TO PRINT NUMBERS USING WHILE LOOP
        
        
        #include<stdio.h>
         int main()
       {
         int n=1;

        while(n<=10)
        {
          printf("%d\n",n);
           n++;
          }
        return 0;
         }
 # OUTPUT OF PROGRAM

                    1
                    2
                    3
                    4
                    5
                    6
                    7
                    8
                    9
                   10
--------------------------------------------------------------------------------------------------------------------------------------

# 19.PROGRAM TO PRINT NUMBERS USING DO WHILE LOOP
    
     #include<stdio.h>
      int main()
     {
       int i=1;
       do{
          printf("%d\n",i);
           i++;
               }
         while(i<=20);
      return 0;
      }
      
## OUTPUT OF PROGRAM

                      1
                      2
                      3
                      4
                      5
                      6
                      7
                      8
                      9
                      10
                      11
                      12
                      13
                      14
                      15
                      16
                      17
                      18
                      19
                      20
----------------------------------------------------------------------------------------------------------------------------------------

# 20.PROGRAM FOR LINEAR SEARCH

     #include<stdio.h>
      int main()
     {
       int sidhant[15]={1,4,48,78,45,12,14,15,20,21,3,5,7,2,9};
       int size=15;
       int flag=0;
       int item,a,i;
       printf("enter number you want to find=");
       scanf("%d",&a);
       for(int i=0;i<size;i++)
    {
        if(a==sidhant[i])
        {
            flag++; 
         }
         }
         if (flag>0){
         printf("\nserach is sucessfull\n");}
         else{
         printf("\nelement not found\n");}
         return 0;
         }
        
 ## OUTPUT OF PROGRAM  
 
       enter number you want to find=12

        serach is sucessfull
      1914109@computer-centre:~/public_html/PPS/Content/Programs/Week02/1914109$ ./a.out 
          enter number you want to find=100

          element not found
--------------------------------------------------------------------------------------------------------------------------------------
## 21.PROGRAM FOR BINARY SEARCH

       #include <stdio.h>
        int main()
       {
         int a[10],i,s,l,n,f,m=0;
         printf("number of element in array");
         scanf("%d",&n);
         for(i=0;i<n;i++)
         {
         printf("enter [%d] element=",i);
         scanf("%d",&a[i]);
         }
         printf("enter element to be searched");
         scanf("%d",&s);
         f=0;
         l=n-1;
         m=(f+l)/2;
         while(f<=l)
         {
         if(a[m]>s)
         {
         l=m-1;
         }
         else if(a[m]<s)
         {
         f=m+1;
         }
         if (a[m]=s)
         {
         printf("location of given element is %d\n",m);
         break;
         }
         else
         l =m-1;
         m = (f + l)/2;
          }
         if (f > l)
         printf("Not found! %d isn't present in the list.\n", s);
 
         return 0;  
         }
         
  ## OUTPUT OF PROGRAM
         number of element in array5
         enter [0] element=1
         enter [1] element=2
         enter [2] element=3
         enter [3] element=4
         enter [4] element=5
         enter element to be searched3
         location of given element is 3
----------------------------------------------------------------------------------------------------------------------------------
