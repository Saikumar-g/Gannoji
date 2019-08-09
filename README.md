#include<bits/stdc++.h>
using namespace std;
int main(){
int x,p;
int sum=x;
while(x>1){
x = ((100-p)/100)*x;
sum = sum + x;
}
cout<<sum;
return 0;
}
