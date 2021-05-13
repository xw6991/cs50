#include <cs50.h>
#include <stdio.h>

int main(void)
{
    // Get integer from user between 1 & 8
    int n;
    do
    {
        n = get_int("Height: ");
    }
    while (n < 1 || n > 8);

    //Going down rows
    for (int i = 0; i < n; i++)
    {
        //Printing out spaces
        for (int h = 0; h < n - (i + 1); h++)
        {

            printf(" ");

        }
        // Print out the hashes
        for (int j = 0; j < i + 1; j++)
        {

            printf("#");
        }


        printf("\n");
    }

}
