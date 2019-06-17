#### 实现strStr方法:

链接:https://leetcode-cn.com/problems/implement-strstr/

案例:

```python
class Solution:
    def strStr(self, haystack: str, needle: str) -> int:
        num = haystack.find(needle)
        
        return num
```

这个有点狗,一个find函数暴力解决