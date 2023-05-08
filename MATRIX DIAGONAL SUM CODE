Approach:
{take a loop
see which are the positions are to be added.
[i][i] th position and [i][n-i-1]th position.}

Time complexity:
O(n)
Space complexity:
O(1)


Code:
class Solution {
public:
    int diagonalSum(vector<vector<int>>& mat) {
        int i=0,sum=0;
        int rows=mat.size();   
      for(i=0;i<rows;i++)
      {
          sum+=mat[i][i]+mat[i][rows-i-1];
      }
      if(rows%2!=0)  
      sum-=mat[rows/2][rows/2];
      return sum;
    }
};
