#include<stdio.h>
int main()
{
    int i,n,m,x;
    printf("how many numbers you want in 1st array?\n");
    scanf("%d", &n);
    printf("how many numbers you want in 2nd array?\n");
    scanf("%d", &m);
    int a[n], b[m];
    for(i=0; i<n; i++)
    {
        scanf("%d", &a[i]);
    }
    for(i=0; i<m; i++)
    {
        scanf("%d", &b[i]);
    }
      //a[]= 2 5 7
    //index= 0 1 2
    // b[]= 2 4 6 8
  // index= 0 1 2 3
   // c[]= 2 5 7 2 4 6 8
  // index=0 1 2 3 4 5 6
  int c[n+m];
    for(i=0; i<n; i++)
    {
      c[i]= a[i];
    }
    int j=0;
    for(i=n; i<n+m; i++)
    {
      c[i]= b[j];
      j++;
    }
    for(i=0; i<n+m; i++)
    { 
        printf("%d ", c[i]);
        
    }
    
    
}

