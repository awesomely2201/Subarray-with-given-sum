
class Subarray{
    static ArrayList<Integer> subarraySum(int[] arr, int n, int s) {
        
        // Your code here
        ArrayList <Integer> list=new ArrayList <Integer>();
        int i,j;
        for(i=0;i<n;i++)
        {
            int sum=0;
            for(j=i;sum<=s && j<n;j++)
            {
                sum=sum+arr[j];
                if(sum==s)
                {
                    list.add(i+1);
                    list.add(j+1);
                    return list;
                }
            }
        }
        list.add(-1);
        return list;
    }
}
