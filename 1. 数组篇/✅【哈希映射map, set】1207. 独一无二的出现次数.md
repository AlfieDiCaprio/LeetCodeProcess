## [1207. 独一无二的出现次数](https://leetcode.cn/problems/unique-number-of-occurrences/description/)

### 思路：
map可以很容易统计不同数字的数量，set可以把相同数量合并

### 题解：
                     
```c++
class Solution {
public:
    bool uniqueOccurrences(vector<int>& arr) {
        int n = arr.size();
        vector<int> res;

        map<int, int> cmp;

        for(int i = 0 ; i < n ; i ++){
            mp[arr[i]]++;
        }

        for(auto it = mp.begin() ; it != mp.end() ; it ++){
            printf("%d -> %d \n", it->first, it->second);
        }

        /*
        int i = 0;
        for(auto it = mp.begin() ; it != mp.end() ; it ++){
            res.push_back(it -> second);
            //printf("%d -> %d \n", it->first, it->second);
        }

        set<int> ans;
        for(i = 0 ; i < res. size() ; i ++){
            ans.insert(res[i]);
        }
        */

        //不用再建一个数组，直接拿mp和set数比
        set<int> ans;
        for(auto m : mp){
            ans.insert(m.second);
        }

        return ans.size() == mp.size();
    }
};
```
