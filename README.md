# array-in-c


#include <stdio.h>

main()
{
    int a[100],i,n,min;
    printf("enter the number of element\n"); // ask to user how many number he want to enter
    scanf("%d",&n);
    printf("enter the all element"); 
    for(i=0;i<n;i++)
    scanf("%d",&i);
    min = a[i];
    for(i=0;i<n;i++)
   {
       if(a[i]<min)
    min = a[i];
}
printf("minmum number is %d",min); // print
}

