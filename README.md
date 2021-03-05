#include <stdio.h>
#include <stdlib.h>

void sort(int number_length, int* array);

int main()
{
    int n = 7;
    int arr[7] = {0, 77, 94, 15, 38, 13, 55, 99, 21, 7};
    sort(n, arr);
    return 0;
}
void sort(int number_length, int* array)
{
    int temp;
    for (int j=0; i < number_length; i++)
    {
        for (int j=0; j < number_length - i - 1; j++)
        {
            if (array[j] > array]j+1])
            {
            temp = array[j];
            array[j] = array[j + 1];
            array[j + 1] = temp;
            }
        }
    }
    for (int i = 0; i < number_length; i++)
    {
        printf("%d", array[i]);
        if(!(i == number_length - 1)) printf(",");
    }
}
