```
#include <stdlib.h>
#include <stdio.h>
using namespace std;

/*
atexit()函数是在函数正常终止之前被调用执行的函数,
而且执行顺序和调用顺序正好相反。
原型： int atexit( void (*)(void) );
在一个函数中最多可以用 atexit注册32个函数。

全局对象的析构函数会在main函数之后执行；
可以用 atexit() 注册一个函数，它会在main之后执行;
*/
int atexit(void (*function)(void));

void gao(){
  printf( "This is executed last.\n" );
}

int main(){
    atexit( gao );
    printf( "This is executed first.\n" );
    return 0;
}
```
