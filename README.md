    
    #include <stdio.h>

    int main()
    {
        printf("x |");
        for (int i = 1; i <= 9; i++)
        {
            printf("%3d", i);
        }
        printf("\n--+");
        for (int i = 0; i < 27; i++)
        {
            printf("-");
        }
        printf("\n");
        for (int i = 1; i <= 9; i++)
        {
            printf("%d |", i);
            for (int j = 1; j < 10; j++)
            {

                printf("%3d", i * j);
            }
            printf("\n");
        }
        return 0;
    }
