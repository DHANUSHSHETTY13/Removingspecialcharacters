#include<stdio.h>
int main()
{
int i=0,count=0,j;
char str[200];
printf("enter the string =");
gets(str);

while(str[i]!='\0')
{
    if(str[i]>='a' && str[i]<='z' || str[i]>='A' && str[i]<='Z')
    {
        printf("%c",str[i]);
        count++;

    }

i++;

}
printf("\n");
printf("total %d char\n",count);



}
