# SOLID-AND-HALLOW-RECTANGLE
Write a program to display a solid and hollow rectangle

HALLOW 
 
----------

#include <stdio.h>
 

void print_rectangle(int n, int m)
{
    int i, j;
    for (i = 1; i <= n; i++)
    {
        for (j = 1; j <= m; j++)
        {
            if (i==1 || i==n || j==1 || j==m)           
                printf("*");           
            else
                printf(" ");           
        }
        printf("\n");
    }
 
}
 

int main()
{
    int rows = 4, columns = 8;
    print_rectangle(rows, columns);
    return 0;
}

==================================================================

OUTPUT

----------------------------

********
*      *
*      *
********

======================================================================================

SOLID RECTANGLE

-------------

#include <stdio.h>

int main()
{
    int i, j, N;

    
    printf("Enter number of rows: ");
    scanf("%d", &N);

    
    for(i=1; i<=N; i++)
    {
       
        for(j=1; j<=N; j++)
        {
            
            printf("*");
        }
        
        
        printf("\n");
    }

    return 0;
}

============================================================

OUTPUT

------------------------------

Enter number of rows: 5
*****
*****
*****
*****
*****
