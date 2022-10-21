#include <stdio.h>
#include<math.h>

void Hello();

int main() {

    /*
    int user_input;
    printf("enter 2nd Odd no : \n");
    scanf("%d",&user_input);
    if (user_input==3)
    {
        printf("Your answer is correct \n");
    }
    else
    {
        printf("Your answer is incorrect \n");
    }
    */

    /*
    int age;
    printf("What is your age? \n");
    scanf("%d",&age);
    printf("%d is your age \n",age);
    */

    /*
    int a,b,sum;
    printf("Enter you first no. : \n");
    scanf("%d",&a);
    printf("Enter you second no. : \n");
    scanf("%d",&b);
    sum = a+b;
    printf("The sum of these two no is : %d \n",sum);
    */
  
    /*
    int side;
    printf("Enter the side of the square : \n");
    scanf("%d", &side);
    int area = side*side;
    printf("Area of the square is :%d \n",area);
    */

    /*
    float radius;
    printf("Enter the radius of the circle : \n");
    scanf("%f",&radius);
    printf("Radius of the circle is : %f \n",22.0/7*radius*radius);
    */

    /*
    int input;
    printf("Write a no : \n");
    scanf("%d",&input);
    if (input%2==0)
    {
        printf("The number entered is even \n");
    }
    else{
        printf("The number entered is odd \n");
    }
    */

    /*
    float first , second , third ;
    printf("Enter the first no. : ");
    scanf("%f",&first);
    printf("Enter the second no. : ");
    scanf("%f",&second);
    printf("Enter the third no. : ");
    scanf("%f",&third);
    float avg = (first + second + third)/3;
    printf("The avg of these no is  %f \n",avg);
    */

    /*
    char character;
    printf("Enter a digit : ");
    scanf("%c",&character);
    if (character == int )
    {
        printf("This is a number \n");
    }
    else 
    {
        printf("This is a character \n");
    }
    */

    /*
    int age;
    printf("Enter your age : ");
    scanf("%d",&age);
    if (age<18)
    {
        printf("You aren not a adult, but you will be in %d years \n",18-age);
    }
    else 
    {
        printf("You are an adult \n");
        printf("You can drive");
        printf("You can vote");
    }
    */
    
    /*
    int input;
    printf("Enter a number : ");
    scanf("%d",&input);
    input%2==0 ? printf("Number you entered is a even number\n"): printf("Number you entered is a odd number \n");
    */

    /*
    float marks_obtained,total_marks;
    int option;
    printf("If you want to enter percentage enter 1 \nIf you want to enter marks enter 2 \n");
    scanf("%d",&option);
    char Grade;
    float percentage;
    if (option==1)
    {
        printf("Enter percentage obtained : ");
        scanf("%f",&percentage);
        if (percentage>100)
        {
            printf("input is invalid! \n");
            return 0;
        }
    }
    else if (option==2)
    {
        printf("Enter marks obtained : ");
        scanf("%f",&marks_obtained);
        printf("Total marks : ");
        scanf("%f",&total_marks);
        if (marks_obtained>total_marks)
        {
            printf("Input is invalid! \n");
            return 0;
        }
        percentage = (marks_obtained/total_marks)*100;
    }
    else 
    {
        printf("Input is invalid! \n");
        return 0;
    }

    if (percentage>=90)
    {
        printf("You have scored A+ Grade \n");
    }
    else if(percentage>=80 && percentage<90)
    {
        printf("You have scored A Grade \n");
    }
    else if(percentage>=70 && percentage<80)
    {
        printf("You have scored B Grade \n");
    }
    else if(percentage>=60 && percentage<70)
    {
        printf("You have scored C Grade \n");
    }
    else if(percentage>=50 && percentage<60)
    {
        printf("You have scored D Grade \n");
    }
    else if(percentage>=33 && percentage<50)
    {
        printf("You have scored E Grade \n");
    }
    else 
    {
        printf("You have failed \n");
    }
    */

    /*
    int user_input,input;
    printf("Enter a 3 digit number : ");
    scanf("%d",&user_input);
    input = user_input;
    int check = 0;
    check += pow((input%10),3);
    input /= 10;
    check += pow((input%10),3);
    input /= 10;
    check += pow((input%10),3);
    input /= 10;
    check == user_input ? printf("This is an armstrong number \n") : printf("This is not an armstrong number \n");
    */

    /*
    int userinput;
    printf("Enter a number ; ");
    scanf("%d",&userinput);
    if (userinput>0)
    {
        printf("This is a natural number \n");
    }
    else if (userinput ==0)
    {
        printf("This is a whole number \n");
    }
    else if (userinput<0)
    {
        printf("This is a integer \n");
    }
    */

    /*
    int userinput;
    printf("Till what number do you want to print ? \n");
    scanf("%d",&userinput);
    for(int i =0;i <= userinput;i++)
    {
        printf("%d ",i);
    }
    */

    /*
    int input,check,temp,digits;
    printf("Enter the number you want to check - \n");
    scanf("%d",&input);
    printf("How many digits are in the number : ");
    scanf("%d",&digits);
    temp = input;
    for(int i =1; i <=temp; i=i+0)
    {
        check += pow(temp%10,digits);
        temp/=10;
    }
    check==input? printf("The number you entered is an armstrong number \n") : printf("The number you entered is not an armstrong number \n");
    */

    /*
    int side, length ,width,choice;
    char symbol;
    printf("Enter the charatcer you want : ");
    scanf("%c",&symbol);
    printf("Enter 1 if you wish to print a square\nEnter 2 if you wish to print a rectangle \n");
    scanf("%d",&choice);
    if (choice==1)
    {
        printf("Enter the side of the square you want : ");
        scanf("%d",&side);
        for(int i =1;i<=side;i++)
        {
            for (int f =1;f<=side;f++)
            {
                printf("%c",symbol);
            }
            printf("\n");
        }
    }
    else if (choice==2)
    {
        printf("Enter the length of the rectangle you want : ");
        scanf("%d",&length);
        printf("Enter the width of the rectangle you want : ");
        scanf("%d",&width);
        for(int i =1;i<=length ;i++)
        {
            for (int f =1;f<=width;f++)
            {
                printf("%c",symbol);
            }
            printf("\n");
        }
    }
    else 
    {
        printf("Invalid input! \n");
    }
    */
   
    /*
    int input,check,factors =0;
    printf("Enter the number you want to check : ");
    scanf("%d",&input);
    int i=1;
    while(i<=input)
    {
        if(input%i==0)
        {
            factors++;
        }
        i++;
    }
    printf("Number of factors %d \n",factors);
    if (factors==2)
    {
        printf("This is a prime number \n");
    }
    else if(factors>2)
    {
        printf("This is not a prime number \n");
    }
    else 
    {
        printf("Invalid input!");
    }
    */
    
    /*
    int start,end,factors=0,count=0;
    printf("Enter the starting number : ");
    scanf("%d",&start);
    printf("Enter the ending number : ");
    scanf("%d",&end);
    while(start<=end)
    {
        for(int i=1;i<=start;i++)
        {
            if(start%i==0)
            {
                factors++;
            }
        }
        if(factors==2)
        {
            printf("%d \n",start);
            count++;
        }
        factors=0;
        start++;
    }
    printf("Count of prime numbers in this range %d\n",count);
    */

    /*
    int limit,sum =0;
    printf("Enter till what number you want the sum of : ");
    scanf("%d",&limit);
    for(int i=1;i<=limit;i++)
    {
        sum +=i;
    }
    printf("Sum of the numbers is : %d \n",sum);
    for(int i=limit;i>0;i--)
    {
        printf("%d\n",i);
    }
    */
    
    /*
    int input,limit;
    printf("what table do you want : ");
    scanf("%d",&input);
    printf("Upto how many digits do you want the table : ");
    scanf("%d",&limit);
    for(int i =1;i<=limit;i++)
    {
        printf("%d X %d = %d \n",input,i,input*i);
    }
    */

    /*
    int even;
    for(int i =1; i>0;)
    {
        printf("Enter an even number : ");
        scanf("%d",&even);
        if(even%2!=0)
        {
            printf("OH No!! You entered a odd number!! \n");
            break;
        }
    }
    */

    /*
    int input;
    for(int i =1; i>0;)
    {
        printf("Enter an number that isn't a multiple of 7 : ");
        scanf("%d",&input);
        if(input%7==0)
        {
            printf("OH No!! You entered a multiple of 7!! \n");
            break;
        }
    }
    */

    /*
    int input,factorial = 1;
    printf("Enter a number : ");
    scanf("%d",&input);
    for(int i=1;i<=input;i++)
    {
        factorial *= i;
    }
    printf("%d\n",factorial);
    */

    // int height;
    // printf("Enter the length of pyramid required : ");
    // scanf("%d",&height);
    // for (int i = 1; i <=height;i++)
    // {
    //     for(int j=i;j>0;j--)
    //     {
    //         printf("*");
    //     }
    //     printf("\n");
    // }
    
    // int height;
    // printf("Enter the length of pyramid required : ");
    // scanf("%d",&height);
    // int width =1;
    // for (int i = height; i >0 ;i--)
    // {
    //     for(int j=0;j<i;j++)
    //     {
    //         printf(" ");
    //     }
    //     for(int k=1;k<=width;k++)
    //     {
    //         printf("*");
    //     }
    //     printf("\n");
    //     width+=2;
    // }

    // int height,mid,line=1;
    // printf("Enter the length of pyramid required : ");
    // scanf("%d",&height);
    // int width =1;
    // for (int i = height; i >0 ;i--)
    // {
    //     for(int j=1;j<=i;j++)
    //     {
    //         printf(" ");
    //     }
    //     if (line==1 || line ==height)
    //     {
    //         for(int k=1;k<=width;k++)
    //         {
    //             printf("*");
    //         }
    //     }
    //     else
    //     {
    //         printf("*");
    //         for(int l=1;l<=width-2;l++)
    //         {
    //             printf(" ");
    //         }
    //         printf("*");
    //     }
    //     printf("\n");
    //     width+=2;
    //     mid = (width+1)/2;
    //     line++;
    // }
   



    

 return 0;
}

void Hello(){
    printf("Hello \n");
}