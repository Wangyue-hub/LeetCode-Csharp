public class Solution {
    public int RemoveDuplicates(int[] nums) {
        var len = nums.Length;
        if (len == 0) return 0;
        var curr = 0;
        for (var i = 1; i < len; i++)
        {
            if (nums[i] > nums[curr])
            {
                nums[++curr] = nums[i];
            }
        }
        return curr + 1;
    }
}
