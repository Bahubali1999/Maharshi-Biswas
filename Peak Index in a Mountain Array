class Solution:
    def peakIndexInMountainArray(self, arr: List[int]) -> int:
        max_num=0
        max_index=0
        for i in range(len(arr)):
            if arr[i]>max_num:
                max_num=arr[i]
                max_index=i
            else:
                i+=1
        return max_index
