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

https://www.hackerrank.com/challenges/apple-and-orange

https://www.hackerrank.com/challenges/between-two-sets/problem

https://www.hackerrank.com/challenges/breaking-best-and-worst-records/problem
