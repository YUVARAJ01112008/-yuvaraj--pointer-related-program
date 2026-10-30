#include <stdio.h>

int main() {
    int age = 25;
    int *ptr = &age;

    printf("Value of age: %d\n", age);
    printf("Address of age: %p\n", (void*)&age);
    printf("Value stored in ptr: %p\n", (void*)ptr);
    printf("Value pointed to by ptr: %d\n", *ptr);

    *ptr = 30;
    printf("New value of age: %d\n", age);

    return 0;
}
