# Exam1
CodeNew
#include <stdio.h>

int main() {
    int num1, num2, result;
    int option;

    printf("=== Calculator ===\n");
    printf("1. Addition\n");
    printf("2. Subtraction\n");
    printf("3. Multiplication\n");
    printf("Select an option (1-3): ");
    scanf("%d", &option);

    printf("Enter the first number: ");
    scanf("%d", &num1);
    printf("Enter the second number: ");
    scanf("%d", &num2);

    if (option == 1) {
        result = num1 + num2;
        printf("Result of addition: %d\n", result);
    } else if (option == 2) {
        result = num1 - num2;
        printf("Result of subtraction: %d\n", result);
    } else if (option == 3) {
        result = num1 * num2;
        printf("Result of multiplication: %d\n", result);
    } else {
        printf("Invalid option.\n");
    }

    return 0;
}
