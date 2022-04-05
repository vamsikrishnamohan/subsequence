# subsequence
//length of string 
#include <bits/stdc++.h>
using namespace std;
 
int main()
{   
  /*  int t;
    cin>> t;
    while(t--)
    {
    int x; // size of string 
    cin >> x;
    if(x==n)
    {*/
    string s;
    cin >> s;
   
   int n= s.size();
   cout<< n<< endl;
    for(int i =0;i<s.size();i++)
      {  
        if (s[i]==s[i+1])
        {
            n=n-1;
        }
      }
    cout<< n<< endl;
     }
   // }
//}
