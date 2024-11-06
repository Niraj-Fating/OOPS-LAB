#include <iostream>
using namespace std;

inline int add(int x , int y)
{
    int c;
    c=x+y;
    return c;
}
inline int sub(int n, int p)
{
    int s;
    s= n-p;
    return s;
}
int main() 
{
    int m,a,b,d;
    m=40;
    a=30;
    b=add(m,a);
    cout<<"Addition od number is "<<b;

    d=sub(m,a);
    cout<<"\nSubtraction of number is "<<d; 
    return 0;
}
