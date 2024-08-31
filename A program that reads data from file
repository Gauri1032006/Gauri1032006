
#include <stdio.h>

int main() {
    FILE *filePointer;
    char data[100];

    // Open file in read mode
    filePointer = fopen("sample.txt", "r");

    if (filePointer == NULL) {
        printf("File could not be opened.");
        return 1;
    }

    // Read data from the file
    while (fgets(data, sizeof(data), filePointer) != NULL) {
        printf("%s", data);
    }

    // Close the file
    fclose(filePointer);

    return 0;
}
