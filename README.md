#include <stdio.h>

int main() {char a[20];
int i,j;
printf("enter a word\n");
gets(a);
j=strlen(a);
printf("the reverse of word is\n");
for(i=j-1;i >=0;i-- )
{
    printf("%c",a[i]);
}
    return 0;
}
