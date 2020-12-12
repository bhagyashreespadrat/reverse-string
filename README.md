# reverse-string
#reverse string in c
#include<stdio.h>
#include<string.h>

int main()
{
    char mystring[60];
    int length, i;

    printf("Enter string you want to reverse\n: ");
    scanf("%s", mystring);

    // This will find the length of your string with the help of strlen() function of string.h header file
    length = strlen(mystring);

    // iterate through each and every character of the string for printing it backwards or reverse direction
    for(i = length - 1; i >= 0; i--) {
        printf("%c", mystring[i]);
    }
    return 0;
}
/*OUTPUT:
Enter string you want to reverse
: ramlakhan
nahkalmar
*/


