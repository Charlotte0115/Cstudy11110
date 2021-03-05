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
