#include <stdio.h>

int main() {
    int arr[] = {10, 20, 30, 40, 50};
    int size = sizeof(arr) / sizeof(arr[0]);
    

    printf("Addresses of all elements of an array\n");
    for (int i = 0; i < size; i++) {
        printf("Address of arr[%d] element: %p\n", i, &arr[i]);
    }

    return 0;
}
