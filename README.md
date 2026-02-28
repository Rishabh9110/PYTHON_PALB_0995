#PROBLEM NUMBER 1 Reverse an Array

## Python Code

```python
class Solution:
    def reverseArray(self, arr):
        left = 0
        right = len(arr) - 1

        while left < right:
            arr[left], arr[right] = arr[right], arr[left]
            left += 1
            right -= 1

        return arr
```

## Output Screenshot

<img src="https://github.com/user-attachments/assets/a1e33e29-768f-4a59-ace0-cc802799466e" width="600"/>
