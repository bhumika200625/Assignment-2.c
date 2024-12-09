#include <stdio.h>
#include <string.h>

int main() {
    char original_string[100];
    char copied_string[100];


    printf("Enter a string: ");
    fgets(original_string, sizeof(original_string), stdin);


    size_t len = strlen(original_string);
    if (len > 0 && original_string[len - 1] == '\n') {
        original_string[len - 1] = '\0';
    }

        strcpy(copied_string, original_string);


    printf("The new string is %s\n", copied_string);

    return 0;
}
