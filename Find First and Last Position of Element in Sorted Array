class Solution:
    def searchRange(self, nums: List[int], target: int) -> List[int]:
        start=0
        end=len(nums)-1
        res1=-1
        while(start<=end):
            mid=start+(end-start)//2
            if target==nums[mid]:
                res1=mid
                end=mid-1
            elif target>nums[mid]:
                start=mid+1
            else:
                end=mid-1
        start=0
        end=len(nums)-1
        res2=-1
        while(start<=end):
            mid=start+(end-start)//2
            if target==nums[mid]:
                res2=mid
                start=mid+1
            elif target>nums[mid]:
                start=mid+1
            else:
                end=mid-1
        return [res1,res2]
        
        
        
                
                
        
