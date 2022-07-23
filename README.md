# recursion

// find factorial by recursion
#include <iostream>
using namespace std;

int fact(int n){
  //base case
  if(n==0){
    return 1;
    }
  // recurcive relation
    int output = n*fact(n-1);
    return output;
  
}



int main() {
  int n;
  cin>>n;
  int ans = fact(n);
  cout<< ans << endl;
  
}
