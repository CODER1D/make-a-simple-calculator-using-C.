# make-a-simple-calculator-using-C.
#include<stdio.h>
//Hi guys today we are going to make a simple addition and subtraction calculator.
int main()
{
    double input1=0;
    double input2=0;
    double ans=0;
    char operator;
    printf("please choose one operator /*+-\n");
    scanf(" %c",&operator);
    if(operator=='/'){  
        printf("--------------------\n");   
        printf("|Enter the first number : \n");
        scanf("%lf",&input1);
        printf("|Enter the second number : \n");
        scanf("%lf",&input2);  
        ans = input1/input2;
        printf("|%f/%f = %f\n ",input1,input2,ans); 
        printf("--------------------\n");
    }
    // and just do the above for 3 more times
    else if(operator=='*'){
        printf("--------------------\n");
        printf("|Enter the first number : \n");
        printf("|");
        scanf("%lf",&input1);
        printf("|Enter the second number : \n");
        printf("|");
        scanf("%lf",&input2);  
        ans = input1*input2;
        printf("|%f*%f = %f\n ",input1,input2,ans);
        printf("--------------------\n"); 
    }
    //and we will do this for the addition.
    // and we could also use the switch to do this 
    else if(operator=='+'){
        printf("--------------------\n");
        printf("|Enter the first number : \n");
        printf("|");
        scanf("%lf",&input1);
        printf("|Enter the second number : \n");
        printf("|");
        scanf("%lf",&input2);  
        ans = input1+input2;
        printf("|%f+%f = %f\n ",input1,input2,ans); 
        printf("--------------------\n");
    }
    else if(operator=='-'){
        printf("--------------------\n");
        printf("|Enter the first number : \n");
        printf("|");
        scanf("%lf",&input1);
        printf("|Enter the second number : \n");
        printf("|");
        scanf("%lf",&input2);  
        ans = input1-input2;
        printf("|%f-%f = %f\n",input1,input2,ans); 
        printf("---------------------\n");
    }
    return 0;
    //the code will be in the description.


}
