/*In Coding blocks test Kartik bhaiya gave students an array of n non-negative integers a1, a2, …, an ,where each represents a point at coordinate (i, ai). n vertical lines are drawn such that the two endpoints of line i is at (i, ai) and (i, 0). The task is to find two lines, which together with x-axis forms a container, such that the container contains the most water.
Note: You may not slant the container.

Input Format
First line contains integer n as size of array. Next n lines contains a single integer as elements of array.

Constraints
n>=2

Output Format
Output maximum water the container contains
*/

#include<bits/stdc++.h>
using namespace std;
#define rep(i,n) for (int i = 0; i < n; ++i)
int main()
{
  int n;
  cin>>n;
  int arr[n]={};
rep(i,n)cin>>arr[i];

int area=0;
int l=0;
int r=n-1;
while(l<r)
{
  area=max(area,min(arr[l],arr[r])*(r-l));
if(arr[l]<arr[r])l++;
else r--;

}
cout<<area;
 return 0;
}
