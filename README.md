class Solution {
    public int[][] transpose(int[][] matrix) {
        int a=matrix.length;//3
        int b=matrix[0].length;//3
        int [][]ans=new int[b][a];
        for(int i=0;i<a;i++)
        {
            for(int j=0;j<b;j++)
                ans[j][i]=matrix[i][j];
        }
        return ans;// [[1,4,7],[2,5,8],[3,6,9]]
    }
}
