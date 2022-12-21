bool isBadVersion(int version);
class Solution {
public:
    int firstBadVersion(int n) {
        int low=1,high=n;
        long long ans;
        while(low<=high){
            long long mid=(low+high)/2;
            cout<<"low:"<<low<<" "<<"high:"<<high<<" "<<"mid:"<<mid<<"\n";
            if(isBadVersion(mid)==true){
                high=mid-1;
                ans=mid;
            }
            else low=mid+1;
        }
        return ans;
    }
    
};
