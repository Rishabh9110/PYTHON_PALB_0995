class Solution:
    def reverseArray(self, arr):
        left = 0
        right = len(arr) - 1

        while left < right:
            arr[left], arr[right] = arr[right], arr[left]
            left += 1
            right -= 1

        return arr

        <img width="959" height="555" alt="REVERSE_AN_ARRAY" src="https://github.com/user-attachments/assets/b36e24a8-0aa6-4799-a4ed-15715a4d8046" />
