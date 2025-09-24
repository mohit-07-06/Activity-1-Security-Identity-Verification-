// Program for Identity Verification Entry
/*The program will not allow un authorised person entry and will give a hassle free access to authorised one. 
*/
#include <stdio.h>

int main() {
    int code;
    printf("Welcome to the Institute\n");
    printf("Please enter your Personal security code to access Entry\n");
    scanf("%d",&code);
    if(code==1)
        {
           printf("You are an authorised Person of the Institute\n");
            printf("Access Granted\n");
        }
    else
        {
             printf("You are not an authorised Person of the Institute\n"); 
              printf("Access Denied\n");
        }

    return 0;
}
