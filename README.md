⚙️ 𝗗𝗮𝘆 𝟳 𝗼𝗳 hashtag#𝗗𝗦𝗔 𝗟𝗲𝗮𝗿𝗻𝗶𝗻𝗴 | 
✅ Problem Solved: Sort Array By Parity

 🔗 My LeetCode Profile : https://lnkd.in/d8_WAS8K

🧩 Problem Overview:
 Given an array of integers, sort it so that all even numbers appear before all the odd numbers.

 Example:
 Input: [3,1,2,4]
 Output: [2,4,3,1] (even numbers first, order doesn't matter)

🧠 Approach I Used:
 This was a good opportunity to practice in-place swapping using a two-pointer technique.
Pointer start tracks the correct position for the next even number.
Traverse the array, and when an even number is found, swap it with the element at start.
This keeps all even numbers to the front of the array.

🔽 Code Logic (Python):
for i in range(len(nums)):
 if nums[i] % 2 == 0:
 nums[i], nums[start] = nums[start], nums[i]
 start += 1
📈 Runtime: 3ms
 🧠 Memory Usage: 18.37MB
 ✅ Beats:
 • Runtime: 47.95%
 • Memory: 82.13%

🎯 What I Learned:
 🔸 How to efficiently rearrange elements with just one pass
 🔸 When and how to use the in-place swap
 🔸 Importance of checking conditions early (nums[i] % 2 == 0)
 🔸 Swapping values using Python’s elegant tuple unpacking
