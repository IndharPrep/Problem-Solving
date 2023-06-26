
Day 1 Problem's solutions:

1 [Convert the Temperature](https://leetcode.com/problems/convert-the-temperature)

    class Solution(object):
        def convertTemperature(self, celsius):
            """
            :type celsius: float
            :rtype: List[float]
            """
            return [celsius + 273.15, celsius*1.80 + 32.00]


2 [Number of Good Pairs](https://leetcode.com/problems/number-of-good-pairs)

    class Solution(object):
        def numIdenticalPairs(self, nums):
            """
            :type nums: List[int]
            :rtype: int
            """
            pairs=0
            for i in range(0,len(nums)):
                for j in range(i+1,len(nums)):
                    if nums[i]==nums[j]:
                        pairs+=1
    
            return pairs


3[Add Two Integers](https://leetcode.com/problems/add-two-integers)

    class Solution(object):
        def sum(self, num1, num2):
            """
            :type num1: int
            :type num2: int
            :rtype: int
            """
    
            return num1+num2
