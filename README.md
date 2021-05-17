# evenChange


class Solution {
  public:
    long long int convertEvenBitToZero(long long int n) {
        // code here
        string s="101010101010101010101010101010";
long long int p=stoi(s,0,2);
long long int r=p&n;
return r;
    }
};
