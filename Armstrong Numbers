//{ Driver Code Starts
// Initial Template for C++
#include <bits/stdc++.h>
using namespace std;


// } Driver Code Ends
// User function Template for C++
class Solution {
  public:
    bool armstrongNumber(int n) {
        // code here
        int num=n;
        bool result = true;
        vector<int> dig;
        do{
            dig.push_back(n%10);
            n=n/10;
        }while(n!=0);
        int sum=0;
        for(int i=0; i<dig.size(); i++){
            sum+=(dig[i]*dig[i]*dig[i]);
        }
        if(sum!=num){
            result=false;
        }
        return result;
    }
};

//{ Driver Code Starts.
int main() {
    int t;
    cin >> t;
    while (t--) {
        int n;
        cin >> n;
        Solution ob;
        bool flag = ob.armstrongNumber(n);
        if (flag) {
            cout << "true" << endl;
        } else {
            cout << "false" << endl;
        }

        cout << "~"
             << "\n";
    }
    return 0;
}

// } Driver Code Ends
