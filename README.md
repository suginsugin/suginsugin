#include <stdio.h>
 
int main()
{
   int m, n, c, d, first[10][10], second[10][10], sum[10][10];
   printf("suginbalaji.G\n192321111\n");
   printf("Enter the number of rows and columns of matrix\n");
   scanf("%d%d", &m, &n);
   printf("Enter the elements of first matrix\n");
 
   for (c = 0; c < m; c++)
      for (d = 0; d < n; d++)
         scanf("%d", &first[c][d]);
 
   printf("Enter the elements of second matrix\n");
 
   for (c = 0; c < m; c++)
      for (d = 0 ; d < n; d++)
         scanf("%d", &second[c][d]);
   
   printf("Sum of entered matrices:-\n");
   
   for (c = 0; c < m; c++) {
      for (d = 0 ; d < n; d++) {
         sum[c][d] = first[c][d] + second[c][d];
         printf("%d\t", sum[c][d]);
      }
      printf("\n");
   }
 
   return 0;
}![WhatsApp Image 2023-12-20 at 21 01 23_ce7b26cd](https://github.com/suginsugin/suginsugin/assets/154415799/e4be4aee-b78a-402b-84f8-9195821deec9)
