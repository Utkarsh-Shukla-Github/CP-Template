# CP-Template

My personal Competitive Programming templates in C++.

```cpp

#include<bits/stdc++.h>
using namespace std;

const int MOD = 1e9 + 7;
const double PI = acos(-1.0);


#define FAST_IO                 ios_base::sync_with_stdio(false), cin.tie(nullptr), cout.tie(nullptr)
#define TESTCASES               int t; cin>>t; while(t--)
#define endl                    ('\n')
#define RETURN                  return 0;

#define int                     long long
#define float                   double

#define fill(arr,val)           memset(arr,val,sizeof(arr))
#define sz(x)                   (int((x).size()))

template<typename T> T          gcd(T a, T b)           { return(b?__gcd(a,b):a); }
template<typename T> T          lcm(T a, T b)           { return(a*(b/gcd(a,b))); }
template<typename T> T          expo(T e, T n)          { T x=1,p=e;while(n){if(n&1)x=x*p;p=p*p;n>>=1; } return x; }
template<typename T> T          power(T e, T n, T m)    { T x=1,p=e;while(n){ if(n&1)x=mul(x,p,m);p=mul(p,p,m);n>>=1; }return x; }



void SOLVE() {

  /*Write the Solution Here*/
   
}



int32_t main()
{
  FAST_IO
  TESTCASES
    SOLVE();
  RETURN
}
```
