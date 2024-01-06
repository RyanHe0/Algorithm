# AcWing 820. 递归求斐波那契数列

`rgb(0,255,0)`请使用递归的方式求斐波那契数列的第 $n$ 项，下标从 1  开始。

斐波那契数列：1,1,2,3,5…
请使用递归的方式求斐波那契数列的第 $n$
 项，下标从1开始。

斐波那契数列：1,1,2,3,5…，这个数列从第 3 项开始，每一项都等于前两项之和

`rgb(255,255,255)`输入格式
共一行，包含整数 $n$  。

`rgb(255,0,255)`输出格式

共一行，包含一个整数，表示斐波那契数列的第 $n$ 项。

```c++

#include<bits/stdc++.h>
using namespace std;

int f(int n){
    if (n<2) return n;
    return f(n-1)+f(n-2);
}

int main(){
    int in;
    cin>>in;
    cout<<f(in);
    return 0;
}
```



---

* Link: https://github.com/RyanHe0/Algorithm/issues/9
* Labels: 
* Creation Date: 2024-01-06T04:52:37Z
