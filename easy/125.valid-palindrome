class Solution:
    def isPalindrome(self, s: str) -> bool:
        s=s.lower()
        cleaned=""

        for ch in s:
            if ch.isalnum():
                cleaned += ch
        
        return cleaned == cleaned[::-1]
