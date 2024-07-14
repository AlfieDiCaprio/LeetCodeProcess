### [1365. 有多少小于当前数字的数字](https://leetcode.cn/problems/how-many-numbers-are-smaller-than-the-current-number/solutions/461021/1365-you-duo-shao-xiao-yu-dang-qian-shu-zi-de-s-35/)

### 思路

哈希表hash（本题可以就用一个数组）来做数值和下标的映射，通过数值快速知道下标（也就是前面有几个比它小的）。

在构造数组hash的时候，从后向前遍历，这样hash里存放的就是相同元素最左面的数值和下标了。

时间复杂度：$O(n\log n)$

![image](https://github.com/user-attachments/assets/5cf585cc-b5c0-4adc-8376-be8a56ea367b)


### 题解

```c++
class Solution {
public:
    vector<int> smallerNumbersThanCurrent(vector<int>& nums) {

        vector<int> tmp = nums;

        sort(tmp.begin(), tmp.end());

        vector<int> res(101);
        for(int i = tmp.size() - 1 ; i >= 0 ; i --){
            res[tmp[i]] = i;
        }

        for(int i = 0 ; i < nums.size() ; i ++){
            tmp[i] = res[nums[i]];
        }
        return tmp;
    }
};
```
