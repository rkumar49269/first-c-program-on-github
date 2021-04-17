/*# first-c-program-on-github*/

#include<stdio.h>      //Header files
#include<conio.h>
#include<stdlib.h>
#include<strf.h>

void main(){
int i,len,n;     //Required variables initialization.
char *r;
clrscr();
printf("\nEnter the number of elements you want to enter:\n");
scanf("%d",&n);           //Input Form user for dynamic memory creation.
r=(char*)malloc(n*(sizeof(char)));
printf("\nEnter whatever you want......\n");
scanf("%s",r);        //required user input as string.
for(i=0;i<n;i++){    /* Initializtion or functionality                        
if(r[i]==0)                for loop for counting string length.*/
break;
else
len=i+1;
}
printf("\n length of string is: %d",len);   // string length as output.
free(r);
getch();    //End of the program.
}
