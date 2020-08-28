// Conditional-statements-grading-
// It is a program that takes user's input as student"s marks and then grades it.
#include<stdio.h>
int main()
{
    int studentmarks;
    printf("Enter student's marks:");
    scanf("%d",&studentmarks);
    if(studentmarks>=85 && studentmarks<=100)
    {
        printf("Grade A");
    }
    if(studentmarks>=70 && studentmarks<=84)
    {
        printf("Grade B");
    }
    if(studentmarks>=55 && studentmarks<=69)
    {

        printf("Grade C");
    }
    if(studentmarks>=40 && studentmarks<=54)
    {
        printf("Grade D");
    }
    if(studentmarks<40  && studentmarks>=0)
    {
        printf("Grade F");
    }
    else
    {
        printf("Wrong marks");
    }
    return 0;
}
