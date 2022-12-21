#include <iostream
using namespace std;
    int mySqrt(int x) {
        int low=0,high=x;
        int ans;
        while(low<=high){
            long long int mid=(low + high)/2;
            if(mid*mid<=x){
                low=mid+1;
                ans=mid;
            }
            else{
                high=mid-1;
            }
        }

    return ans;   
    }

int main()
{
    int x;
    cin>>x;
    cout<<mySqrt(x)<<endl;

    return 0;
}
