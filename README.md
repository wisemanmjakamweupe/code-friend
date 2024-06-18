# code-friend
my friend code
#include <stdio.h>
#include <stdio.h>
int main() {
    char name [50];
    //Prompt user to enter friend's name
    printf("Enter your friend's name:");
    fgets(name,sizeof(name),stdin);
    //Remove newLine character from fgets input
    name[strcspn(name, "/n")] = 0;
    //Display the message 
    printf("%s , you are the best!/n",name);

    return 0;
    }
