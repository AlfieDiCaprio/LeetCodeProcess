# 跟着代码随想录刷LC（研二下自救）

### 1. 数组篇（7题 + 9题 + 12题）

#### 方法：二分算法、双指针法、滑动窗口、行为模拟

- [x] 1-1. [数组过于简单，但你该了解这些！](https://programmercarl.com/%E6%95%B0%E7%BB%84%E7%90%86%E8%AE%BA%E5%9F%BA%E7%A1%80.html) 

- [x] 1-2. [数组：704.二分查找](https://programmercarl.com/0704.%E4%BA%8C%E5%88%86%E6%9F%A5%E6%89%BE.html)

- [x] 1-3. [数组：27.移除元素](https://programmercarl.com/0027.%E7%A7%BB%E9%99%A4%E5%85%83%E7%B4%A0.html)

- [x] 1-4. [数组：977.有序数组的平方](https://programmercarl.com/0977.%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84%E7%9A%84%E5%B9%B3%E6%96%B9.html)    

- [x] 1-5. [数组：209.长度最小的子数组](https://programmercarl.com/0209.%E9%95%BF%E5%BA%A6%E6%9C%80%E5%B0%8F%E7%9A%84%E5%AD%90%E6%95%B0%E7%BB%84.html)

- [x] 1-6. [数组：59.螺旋矩阵II](https://programmercarl.com/0059.%E8%9E%BA%E6%97%8B%E7%9F%A9%E9%98%B5II.html)

- [x] 1-7. [数组总结](https://programmercarl.com/%E6%95%B0%E7%BB%84%E6%80%BB%E7%BB%93%E7%AF%87.html)

**补充题**
- [ ] 1-8. [1365.有多少小于当前数字的数字](https://programmercarl.com/1365.%E6%9C%89%E5%A4%9A%E5%B0%91%E5%B0%8F%E4%BA%8E%E5%BD%93%E5%89%8D%E6%95%B0%E5%AD%97%E7%9A%84%E6%95%B0%E5%AD%97.html)

- [ ] 1-9. （双指针）[941.有效的山脉数组](https://programmercarl.com/0941.%E6%9C%89%E6%95%88%E7%9A%84%E5%B1%B1%E8%84%89%E6%95%B0%E7%BB%84.html) 

- [ ] 1-10.（哈希法）[1207.独一无二的出现次数](https://programmercarl.com/1207.%E7%8B%AC%E4%B8%80%E6%97%A0%E4%BA%8C%E7%9A%84%E5%87%BA%E7%8E%B0%E6%AC%A1%E6%95%B0.html) 

- [ ] 1-11.（双指针）[283.移动零](https://programmercarl.com/0283.%E7%A7%BB%E5%8A%A8%E9%9B%B6.html)

- [ ] 1-13. [189.旋转数组](https://programmercarl.com/0189.%E6%97%8B%E8%BD%AC%E6%95%B0%E7%BB%84.html)

- [ ] 1-14. [724.寻找数组的中心索引](https://programmercarl.com/0724.%E5%AF%BB%E6%89%BE%E6%95%B0%E7%BB%84%E7%9A%84%E4%B8%AD%E5%BF%83%E7%B4%A2%E5%BC%95.html)

- [ ] 1-15.（二分法）[34.在排序数组中查找元素的第一个和最后一个位置](https://programmercarl.com/0034.%E5%9C%A8%E6%8E%92%E5%BA%8F%E6%95%B0%E7%BB%84%E4%B8%AD%E6%9F%A5%E6%89%BE%E5%85%83%E7%B4%A0%E7%9A%84%E7%AC%AC%E4%B8%80%E4%B8%AA%E5%92%8C%E6%9C%80%E5%90%8E%E4%B8%80%E4%B8%AA%E4%BD%8D%E7%BD%AE.html) 

- [ ] 1-16. [922.按奇偶排序数组II](https://programmercarl.com/0922.%E6%8C%89%E5%A5%87%E5%81%B6%E6%8E%92%E5%BA%8F%E6%95%B0%E7%BB%84II.html) 

- [ ] 1-17. [35.搜索插入位置](https://programmercarl.com/0035.%E6%90%9C%E7%B4%A2%E6%8F%92%E5%85%A5%E4%BD%8D%E7%BD%AE.html)

**相关题目推荐**

**1-2 二分查找 相关推荐**

- [ ] 1-18. [35.搜索插入位置](https://programmercarl.com/0035.%E6%90%9C%E7%B4%A2%E6%8F%92%E5%85%A5%E4%BD%8D%E7%BD%AE.html)

- [ ] 1-19. [34.在排序数组中查找元素的第一个和最后一个位置](https://programmercarl.com/0034.%E5%9C%A8%E6%8E%92%E5%BA%8F%E6%95%B0%E7%BB%84%E4%B8%AD%E6%9F%A5%E6%89%BE%E5%85%83%E7%B4%A0%E7%9A%84%E7%AC%AC%E4%B8%80%E4%B8%AA%E5%92%8C%E6%9C%80%E5%90%8E%E4%B8%80%E4%B8%AA%E4%BD%8D%E7%BD%AE.html)

- [ ] 1-20. [69.x 的平方根](https://leetcode.cn/problems/sqrtx/)

- [ ] 1-21. [367.有效的完全平方数](https://leetcode.cn/problems/valid-perfect-square/)
      
**1-3 移除元素 相关推荐**

- [ ] 1-22. [26.删除排序数组中的重复项](https://leetcode.cn/problems/remove-duplicates-from-sorted-array/)
      
- [ ] 1.23. [283.移动零](https://leetcode.cn/problems/move-zeroes/)

- [ ] 1-24. [844.比较含退格的字符串](https://leetcode.cn/problems/backspace-string-compare/)
    
- [ ] 1-25. [977.有序数组的平方](https://leetcode.cn/problems/squares-of-a-sorted-array/)

**1-5 长度最小的子数组 相关推荐**

- [ ] 1-26. [904.水果成篮](https://leetcode.cn/problems/fruit-into-baskets/)
      
- [ ] 1-27. [76.最小覆盖子串](https://leetcode.cn/problems/minimum-window-substring/)

**1-6 螺旋矩阵II 相关推荐**

- [ ] 1-28. [54.螺旋矩阵](https://leetcode.cn/problems/spiral-matrix/)
      
- [ ] 1-29. [剑指Offer 29.顺时针打印矩阵](https://leetcode.cn/problems/shun-shi-zhen-da-yin-ju-zhen-lcof/)
      

### 2. 链表篇（9题 + 5题）
- [ ] 2-1. [关于链表，你该了解这些！](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/%E9%93%BE%E8%A1%A8%E7%90%86%E8%AE%BA%E5%9F%BA%E7%A1%80.md)
      
- [ ] 2-2. [链表：203.移除链表元素](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0203.%E7%A7%BB%E9%99%A4%E9%93%BE%E8%A1%A8%E5%85%83%E7%B4%A0.md)
      
- [ ] 2-3. [链表：707.设计链表](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0707.%E8%AE%BE%E8%AE%A1%E9%93%BE%E8%A1%A8.md)
      
- [ ] 2-4. [链表：206.翻转链表](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0206.%E7%BF%BB%E8%BD%AC%E9%93%BE%E8%A1%A8.md)
      
- [ ] 2-5. [链表：24.两两交换链表中的节点](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0024.%E4%B8%A4%E4%B8%A4%E4%BA%A4%E6%8D%A2%E9%93%BE%E8%A1%A8%E4%B8%AD%E7%9A%84%E8%8A%82%E7%82%B9.md)
      
- [ ] 2-6. [链表：19.删除链表的倒数第 N 个结点](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0019.%E5%88%A0%E9%99%A4%E9%93%BE%E8%A1%A8%E7%9A%84%E5%80%92%E6%95%B0%E7%AC%ACN%E4%B8%AA%E8%8A%82%E7%82%B9.md)
      
- [ ] 2-7. [链表：链表相交](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/%E9%9D%A2%E8%AF%95%E9%A2%9802.07.%E9%93%BE%E8%A1%A8%E7%9B%B8%E4%BA%A4.md)
      
- [ ] 2-8. [链表：142.环形链表](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0142.%E7%8E%AF%E5%BD%A2%E9%93%BE%E8%A1%A8II.md)
      
- [ ] 2-9. [链表：总结篇！](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/%E9%93%BE%E8%A1%A8%E6%80%BB%E7%BB%93%E7%AF%87.md)

**补充题**

- [ ] 2-10. [24.两两交换链表中的节点](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0024.%E4%B8%A4%E4%B8%A4%E4%BA%A4%E6%8D%A2%E9%93%BE%E8%A1%A8%E4%B8%AD%E7%9A%84%E8%8A%82%E7%82%B9.md)
      
- [ ] 2-11. [234.回文链表](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0234.%E5%9B%9E%E6%96%87%E9%93%BE%E8%A1%A8.md)
      
- [ ] 2-12.（数组、双向队列、直接操作链表）[143.重排链表](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0143.%E9%87%8D%E6%8E%92%E9%93%BE%E8%A1%A8.md)
      
- [ ] 2-13. [141.环形链表](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0141.%E7%8E%AF%E5%BD%A2%E9%93%BE%E8%A1%A8.md)
      
- [ ] 2-14. [160.相交链表](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/%E9%9D%A2%E8%AF%95%E9%A2%9802.07.%E9%93%BE%E8%A1%A8%E7%9B%B8%E4%BA%A4.md)


### 3. 哈希表篇（11题 + 1题 + 4题）
- [ ] 3-1. [关于哈希表，你该了解这些！](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/%E5%93%88%E5%B8%8C%E8%A1%A8%E7%90%86%E8%AE%BA%E5%9F%BA%E7%A1%80.md)
   
- [ ] 3-2. [哈希表：242.有效的字母异位词](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0242.%E6%9C%89%E6%95%88%E7%9A%84%E5%AD%97%E6%AF%8D%E5%BC%82%E4%BD%8D%E8%AF%8D.md)
   
- [ ] 3-3. [哈希表：1002.查找常用字符](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/1002.%E6%9F%A5%E6%89%BE%E5%B8%B8%E7%94%A8%E5%AD%97%E7%AC%A6.md)
   
- [ ] 3-4. [哈希表：349.两个数组的交集](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0349.%E4%B8%A4%E4%B8%AA%E6%95%B0%E7%BB%84%E7%9A%84%E4%BA%A4%E9%9B%86.md)
   
- [ ] 3-5. [哈希表：202.快乐数](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0202.%E5%BF%AB%E4%B9%90%E6%95%B0.md)
    
- [ ] 3-6. [哈希表：1.两数之和](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0001.%E4%B8%A4%E6%95%B0%E4%B9%8B%E5%92%8C.md)
    
- [ ] 3-7. [哈希表：454.四数相加II](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0454.%E5%9B%9B%E6%95%B0%E7%9B%B8%E5%8A%A0II.md)
    
- [ ] 3-8. [哈希表：383.赎金信](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0383.%E8%B5%8E%E9%87%91%E4%BF%A1.md)
    
- [ ] 3-9. [哈希表：15.三数之和](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0015.%E4%B8%89%E6%95%B0%E4%B9%8B%E5%92%8C.md)
    
- [ ] 3-10. [双指针法：18.四数之和](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0018.%E5%9B%9B%E6%95%B0%E4%B9%8B%E5%92%8C.md)
    
- [ ] 3-11. [哈希表：总结篇！](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/%E5%93%88%E5%B8%8C%E8%A1%A8%E6%80%BB%E7%BB%93.md)
    
**补充题**
- [ ] 3-12. （哈希表的应用）[205.同构字符串](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0205.%E5%90%8C%E6%9E%84%E5%AD%97%E7%AC%A6%E4%B8%B2.md)

**相关题目推荐**

**3-2 有效的字母异位词 相关推荐**

- [ ] 3-13. [383.赎金信](https://programmercarl.com/0383.%E8%B5%8E%E9%87%91%E4%BF%A1.html)
      
- [ ] 3-14. [49.字母异位词分组](https://leetcode.cn/problems/group-anagrams/)
      
- [ ] 3-15. [438.找到字符串中所有字母异位词](https://leetcode.cn/problems/find-all-anagrams-in-a-string/)

**3-4 两个数组的交集 相关推荐**

- [ ] 3-16. [350.两个数组的交集 II](https://leetcode.cn/problems/intersection-of-two-arrays-ii/)
