#include <cs50.h>
#include <stdio.h>
#include <math.h>

int main(void)
{
    float n;
    do
    {
        n = get_float("Change owed in dollars: ");

    }
    while (n < 0);

    int cents = round(n * 100);

    int q = 0;
    int d = 0;
    int ni = 0;
    int p = 0;

    //Counts number of quarters
        while (cents >= 25)
    {
        cents = cents - 25;
        q++;
    }
    //Counts number of dimes
    while (cents >= 10)
    {
        cents = cents - 10;
        d++;
    }
    //Counts number of nickles
    while (cents >= 5)
    {
        cents = cents - 5;
        ni++;
    }
    //Counts number of pennies
    while (cents >= 1)
    {
        cents = cents - 1;
        p++;
    }
    //Adds up total number of coins
    int total = q + d + ni + p;

    printf("%i\n", total);






}
