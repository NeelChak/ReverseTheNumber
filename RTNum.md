# ReverseTheNumber
#include <iostream>
using namespace std;

int main() {
	// your code goes here
	int t;
	cin>>t;
	for(int i=0;i<t;i++){
	    int n,r,rev=0;
	    cin>>n;
	    while(n>0){
	        r=n%10;
	        n=n/10;
	        rev=rev*10+r;
	    }
	    cout<<rev<<endl;
	}
	return 0;
}
