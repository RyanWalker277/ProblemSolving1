# ProblemSolving1

https://www.hackerrank.com/challenges/staircase/problem

#include <bits/stdc++.h>

using namespace std;

int main(){
   int n,sp,w = 1,k;
    cin >> n;
    k = n-1;
    for(int i = 0; i < n; i++){
     sp = k;
     for(int j = 0; j < sp; j++)cout << " ";
     for(int m = 0; m < w; m++)cout << "#";
     cout << endl;
     k--;
     w++;
    }
    return 0;
}


https://www.hackerrank.com/challenges/time-conversion

#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    string s;
    string h;
    int hr;
    cin>>s;
    hr = ((s[0]-'0')*10)+(s[1]-'0');
    if(s[8]=='P'&&s[9]=='M'&& hr ==12) cout<<to_string(hr);
    else if(s[8]=='P'&&s[9]=='M') cout<<to_string(hr+12);
    else if(s[8]=='A'&&s[9]=='M'&&hr==12) cout<<"00";
    
    else cout<< s[0]<<s[1];
    
   
    for(int i =2;i<8;i++)
        cout<<s[i];
    cout<<endl;
    return 0;
}


https://www.hackerrank.com/challenges/apple-and-orange
               
               #include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;

int main()
{
    int s,t,a,b,m,n,ap,apcnt = 0,ora,orcnt = 0;
    
    cin >> s >> t >> a >> b >> m >> n;
    
    for(int i = 0;i < m;i++)
 {
        cin >> ap;
        if(a+ap >= s && a+ap <= t)apcnt++;
    }
    
    for(int i = 0;i < n;i++)
 {
        cin >> ora;
        if(b+ora >= s && b+ora <= t)orcnt++;
    }
    cout << apcnt <<endl<< orcnt << endl;
    return 0;
}


https://www.hackerrank.com/challenges/between-two-sets/problem

https://www.hackerrank.com/challenges/breaking-best-and-worst-records/problem
