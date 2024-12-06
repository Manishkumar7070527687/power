// power
#include<iostream>
using namespace std;
int main() {
int base=5;
int exp=2;
int res=1;                    //i=1 hoga to res = 5*1=5 step 2 me i=2 hoga to res = 5 * 5=25.
for (int  i = 1; i <=exp; i++)
{
    res *= base;
    /* code */
}
cout<<res;
    return 0;
}
