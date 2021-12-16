/# C-program
to find length of string without str.len/

#include<stdio.h>
void main()
{
    char St[100];
    int i,l=0;
    printf("Enter the String\n");
    scanf("%s",St);
    for(i=0;St[i]!='\0';i++);
    printf("Length of the string is :- %d",i);
}
