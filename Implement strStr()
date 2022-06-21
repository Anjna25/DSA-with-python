class Solution:
    def strStr(self, haystack: str, needle: str) -> int:
        m, n = len(haystack), len(needle)
        if needle in haystack:
            for i in range(m):
                if needle in haystack[i:i+n]:
                    return i
                    break
        else:
            return -1
