
# **PROGRAMMING FOR PROGRAM SOLVING ESC-18105**
## NAME-*SIDHANT JINDAL*
## ROLL NO-*1914109*
## BRANCH-*CIVIL*
## SECTION-*CE(B2)*
![LOGO](https://blog.coachingkaro.org/wp-content/uploads/2019/07/logo.jpg)
## **DEPARTMENT OF CIVIL ENGENEERING**
# **GURU NANAK DEV ENGENEERING COLLEGE,LUDHIANA**



------------------------------------------------------------------------------------------------------------------------

# PROGRAM TO PRINT HELLO WORLD

         include<stdio.h>
         void main()
         {
         puts("hello world\n");
         }
        
## OUTPUT OF PROGRAM         
         
         hello world
--------------------------------------------------------------------------------------------------------------------------------
# PROGRAM TO PRINT MULTIPLICATION TABLE

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
 
 # PROGRAM TO ADD 2 NUMBERS
 
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
 # PROGRAM FOR ARITHMATIC OPERATIONS
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
# PROGRAM TO PRINT A TO Z

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
# PROGRAM TO FIND DIVIDEND AND DIVISOR

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
             
 -------------------------------------------------------------------------------------------------------------------------------------- 
 
 # PROGRAM TO FIND MAXIMUM NUMBER
            
            
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
 
 # PROGRAM TO FIND MINIMUM OF TWO NUMBERS
              
              
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
  
  # PROGRAM TO PRONT CALCULATOR
                
                
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
  
