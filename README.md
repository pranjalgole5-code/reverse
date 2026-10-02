#include <stdio.h>

int main()
{
    float temperature;

    printf("Enter temperature: ");
    scanf("%f", &temperature);

    if (temperature < 20)
    {
        printf("Cold");
    }
    else
    {
        if (temperature <= 30)
        {
            printf("Normal");
        }
        else
        {
            printf("Hot");
        }
    }

    return 0;
}
