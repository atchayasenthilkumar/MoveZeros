# MoveZeros
leetcodesolution

class Solution
{
public void moveZeros(int[] nums)
{
int p=0;
for(int s=0;s<nums.length;s+=1)
{
if(nums[s]!=0)
{
nums[p]=nums[s];
p+=1;
}
}
while(p<nums.length)
{
nums[p]=0;
p+=1;
}
}
}
