#include <stdio.h>
//haslo
int main()
{
    int haslo=1453;

    for(int i=0;i<=9999;i++){
        printf("%d\n",i);
        if(i==haslo){
           printf("To jest liczba ktorej szukasz%d",i);
            break;
        }

    }

    return 0;
}
