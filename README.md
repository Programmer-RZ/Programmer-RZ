```c++
#include <bits/stdc++.h>
using namespace std;int
main() {
int a=0;                   a^=1;               a&=1;
int b=0;                   b^=1;               b|=1;
int c=0;             c^=1>>(1|(0<<1));   c=(*(&a))!=(b^1);
int d=0;             d^=0>>(1|(1<<0));   d=(a^1)!=(*(&c));
int e=0;                   e^=1;               e==d;
int f=0;                   f^=1;               f==e;
cout<<a<<b<<c<<d<<e<<a;
cout<<0<<f<<0<<(a&0)<<0;}

```
