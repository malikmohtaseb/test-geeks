# test-geeks
#include <stdio.h>

int main()
{
    printf("name:malik\n");
    
 printf("birthday:8/4/2003\n"); 
  printf("phone number\n");
    return 0;
}
out put
name:malik
birthday:8/4/2003
phone number


...Program finished with exit code 0
Press ENTER to exit console.


include <stdio.h>
#include <string.h>

int main() {
    char chars[] = {'X', 'M', 'L', '\0'};
    char reverse[4];
    int i, j;

    // Print the original characters
    printf("Characters: %s\n", chars);

    // Reverse the characters
    j = 0;
    for (i = strlen(chars) - 1; i >= 0; i--) {
        reverse[j] = chars[i];
        j++;
    }
    reverse[j] = '\0';

    // Print the reversed characters
    printf("The reverse of %s is %s\n", chars, reverse);

    return 0;
}


Characters: XML
The reverse of XML is LMX
