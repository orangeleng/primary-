# primary-

第一个简单的代码
#include <stdio.h>
int main()
{
int a=1;
int b=2;
switch(a){
    case 1:
    a++;
    case 2:
    b++;
    case 3:{switch(a){
        case 1: 
        a++;b++;
        case 2:
        a++;a++;
        case 3:
        a++;
        break;
    }
    printf("a=%d b=%d",a,b);
    }
}
return 0;
