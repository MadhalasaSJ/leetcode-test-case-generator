# Generated Unit Test Cases

## Problem Description:
Given an array of integers `nums` and an integer `target`, return indices of the two numbers such that they add up to `target`.

You may assume that each input would have exactly one solution, and you may not use the same element twice.

You can return the answer in any order.


Example 1:
Input: nums = [2,7,11,15], target = 9
Output: [0,1]
Output: Because nums[0] + nums[1] == 9, we return [0, 1].

Example 2:
Input: nums = [3,2,4], target = 6
Output: [1,2]

Example 3:
Input: nums = [3,3], target = 6
Output: [0,1]

Constraints:
`2 <= nums.length <= 103`
`-109 <= nums[i] <= 109`
`-109 <= target <= 109`
Only one valid answer exists.

### Generated Test Case:
```
target. nums = [2,7,11,15], target = 9 Output: [1,2] Example 3: Input: nums = [3,3,3], target = 6 Output: [1,2] Example 3: Input: nums = [3,3], target = 6 Output: [0,1] Constraints: 2 = nums.length =
```

## Problem Description:
You are given two non-empty linked lists representing two non-negative integers. The digits are stored in reverse order, and each of their nodes contains a single digit. Add the two numbers and return the sum as a linked list.

You may assume the two numbers do not contain any leading zero, except the number 0 itself.


Example 1:
Input: l1 = [2,4,3], l2 = [5,6,4]
Output: [7,0,8]
Explanation: 342 + 465 = 807.


Example 2:
Input: l1 = [0], l2 = [0]
Output: [0]

Example 3:
Input: l1 = [9,9,9,9,9,9,9], l2 = [9,9,9,9]
Output: [8,9,9,9,0,0,0,1]

Constraints:
The number of nodes in each linked list is in the range `[1, 100]`.

`0 <= Node.val <= 9`
It is guaranteed that the list represents a number that does not have leading zeros.

### Generated Test Case:
```
: Add two non-empty linked lists representing two non-negative integers. The digits are stored in reverse order, and each of their nodes contains a single digit. You may assume the two numbers do not contain any leading zero, except the number 0 itself. Title: Add two numbers and return the sum as a linked list.
```

## Problem Description:
Given a string `s`, find the length of the longest substring without repeating characters.


Example 1:
Input: s = "abcabcbb"
Output: 3
Explanation: The answer is "abc", with the length of 3.


Example 2:
Input: s = "bbbbb"
Output: 1
Explanation: The answer is "b", with the length of 1.


Example 3:
Input: s = "pwwkew"
Output: 3
Explanation: The answer is "wke", with the length of 3.

Notice that the answer must be a substring, "pwke" is a subsequence and not a substring.


Example 4:
Input: s = ""
Output: 0

Constraints:
`0 <= s.length <= 5 * 104`
`s` consists of English letters, digits, symbols and spaces.

### Generated Test Case:
```
: s = "bbbbbbbbbbbbbbbbbb" Output: 3 Explanation: The answer is "wke", with the length of 3. Note that the answer must be a substring, "pwke" is a subsequence and not a substring.
```

## Problem Description:
Given two sorted arrays `nums1` and `nums2` of size `m` and `n` respectively, return the median of the two sorted arrays.


Example 1:
Input: nums1 = [1,3], nums2 = [2]
Output: 2.00000
Explanation: merged array = [1,2,3] and median is 2.


Example 2:
Input: nums1 = [1,2], nums2 = [3,4]
Output: 2.50000
Explanation: merged array = [1,2,3,4] and median is (2 + 3) / 2 = 2.5.


Example 3:
Input: nums1 = [0,0], nums2 = [0,0]
Output: 0.00000

Example 4:
Input: nums1 = [], nums2 = [1]
Output: 1.00000

Example 5:
Input: nums1 = [2], nums2 = []
Output: 2.00000

Constraints:
`nums1.length == m`
`nums2.length == n`
`0 <= m <= 1000`
`0 <= n <= 1000`
`1 <= m + n <= 2000`
`-106 <= nums1[i], nums2[i] <= 106`
Follow up: The overall run time complexity should be `O(log (m+n))`.

### Generated Test Case:
```
: nums1 = [1,3], nums2 = [2] Output: 2.00000 Explanation: merged array = [1,2,3] and median is 2. Example 2: Input: nums1 = [1,2], nums2 = [3,4] Output: 2.50000 Explanation: merged array = [1,2,3,4] and median is (2 + 3) / 2 = 2.5.
```

## Problem Description:
Given a string `s`, return the longest palindromic substring in `s`.


Example 1:
Input: s = "babad"
Output: "bab"
Note: "aba" is also a valid answer.


Example 2:
Input: s = "cbbd"
Output: "bb"

Example 3:
Input: s = "a"
Output: "a"

Example 4:
Input: s = "ac"
Output: "a"

Constraints:
`1 <= s.length <= 1000`
`s` consist of only digits and English letters (lower-case and/or upper-case),

### Generated Test Case:
```
: Given a string s, return the longest palindromic substring in s. Example 1: Input: s = "babad" Output: "bb" Note: "aba" is also a valid answer.
```

## Problem Description:
The string `"PAYPALISHIRING"` is written in a zigzag pattern on a given number of rows like this: (you may want to display this pattern in a fixed font for better legibility)
P   A   H   N
A P L S I I G
Y   I   R
And then read line by line: `"PAHNAPLSIIGYIR"`
Write the code that will take a string and make this conversion given a number of rows:
string convert(string s, int numRows);

Example 1:
Input: s = "PAYPALISHIRING", numRows = 3
Output: "PAHNAPLSIIGYIR"

Example 2:
Input: s = "PAYPALISHIRING", numRows = 4
Output: "PINALSIGYAHRPI"
Explanation:
P     I    N
A   L S  I G
Y A   H R
P     I

Example 3:
Input: s = "A", numRows = 1
Output: "A"

Constraints:
`1 <= s.length <= 1000`
`s` consists of English letters (lower-case and upper-case), `','` and `'.'`.

`1 <= numRows <= 1000`

### Generated Test Case:
```
"PAYPALISHIRING" is written in a zigzag pattern on a given number of rows like this: (you may want to display this pattern in a fixed font for better legibility) P A H N A P L S I I G Y I R And then read line by line: "PAYPALISHIRING" Write the code that will take a string and make this conversion given a
```

## Problem Description:
Given a signed 32-bit integer `x`, return `x` with its digits reversed. If reversing `x` causes the value to go outside the signed 32-bit integer range `[-231, 231 - 1]`, then return `0`.

Assume the environment does not allow you to store 64-bit integers (signed or unsigned).


Example 1:
Input: x = 123
Output: 321

Example 2:
Input: x = -123
Output: -321

Example 3:
Input: x = 120
Output: 21

Example 4:
Input: x = 0
Output: 0

Constraints:
`-231 <= x <= 231 - 1`

### Generated Test Case:
```
: Given a signed 32-bit integer x, return x with its digits reversed. If reversing x causes the value to go outside the signed 32-bit integer range [-231, 231 - 1], then return 0. Title: Reverse Integer: Reverse Integer: Reverse Integer: Reverse Inte
```

## Problem Description:
Implement the `myAtoi(string s)` function, which converts a string to a 32-bit signed integer (similar to C/C++'s `atoi` function).

The algorithm for `myAtoi(string s)` is as follows:
Read in and ignore any leading whitespace.

Check if the next character (if not already at the end of the string) is `'-'` or `'+'`. Read this character in if it is either. This determines if the final result is negative or positive respectively. Assume the result is positive if neither is present.

Read in next the characters until the next non-digit charcter or the end of the input is reached. The rest of the string is ignored.

Convert these digits into an integer (i.e. `"123" -> 123`, `"0032" -> 32`). If no digits were read, then the integer is `0`. Change the sign as necessary (from step 2).

If the integer is out of the 32-bit signed integer range `[-231, 231 - 1]`, then clamp the integer so that it remains in the range. Specifically, integers less than `-231` should be clamped to `-231`, and integers greater than `231 - 1` should be clamped to `231 - 1`.

Return the integer as the final result.

Note:
Only the space character `' '` is considered a whitespace character.

Do not ignore any characters other than the leading whitespace or the rest of the string after the digits.


Example 1:
Input: s = "42"
Output: 42
Explanation: The underlined characters are what is read in, the caret is the current reader position.

Step 1: "42" (no characters read because there is no leading whitespace)
         ^
Step 2: "42" (no characters read because there is neither a '-' nor '+')
         ^
Step 3: "42" ("42" is read in)
           ^
The parsed integer is 42.

Since 42 is in the range [-231, 231 - 1], the final result is 42.


Example 2:
Input: s = "   -42"
Output: -42
Explanation:
Step 1: "   -42" (leading whitespace is read and ignored)
            ^
Step 2: "   -42" ('-' is read, so the result should be negative)
             ^
Step 3: "   -42" ("42" is read in)
               ^
The parsed integer is -42.

Since -42 is in the range [-231, 231 - 1], the final result is -42.


Example 3:
Input: s = "4193 with words"
Output: 4193
Explanation:
Step 1: "4193 with words" (no characters read because there is no leading whitespace)
         ^
Step 2: "4193 with words" (no characters read because there is neither a '-' nor '+')
         ^
Step 3: "4193 with words" ("4193" is read in; reading stops because the next character is a non-digit)
             ^
The parsed integer is 4193.

Since 4193 is in the range [-231, 231 - 1], the final result is 4193.


Example 4:
Input: s = "words and 987"
Output: 0
Explanation:
Step 1: "words and 987" (no characters read because there is no leading whitespace)
         ^
Step 2: "words and 987" (no characters read because there is neither a '-' nor '+')
         ^
Step 3: "words and 987" (reading stops immediately because there is a non-digit 'w')
         ^
The parsed integer is 0 because no digits were read.

Since 0 is in the range [-231, 231 - 1], the final result is 0.


Example 5:
Input: s = "-91283472332"
Output: -2147483648
Explanation:
Step 1: "-91283472332" (no characters read because there is no leading whitespace)
         ^
Step 2: "-91283472332" ('-' is read, so the result should be negative)
          ^
Step 3: "-91283472332" ("91283472332" is read in)
                     ^
The parsed integer is -91283472332.

Since -91283472332 is less than the lower bound of the range [-231, 231 - 1], the final result is clamped to -231 = -2147483648. 

Constraints:
`0 <= s.length <= 200`
`s` consists of English letters (lower-case and upper-case), digits (`0-9`), `' '`, `'+'`, `'-'`, and `'.'`.

### Generated Test Case:
```
: Step 1: " -42" Output: 42 Explanation: Step 1: "-42" Output: 42 Explanation: Step 1: "-42" (no characters read because there is no leading whitespace)  Step 2: "-91283472332" (no characters read because there is no leading whitespace)  Step 2: "-91283472332" (no characters read because there
```

## Problem Description:
Given an integer `x`, return `true` if `x` is palindrome integer.

An integer is a palindrome when it reads the same backward as forward. For example, `121` is palindrome while `123` is not.


Example 1:
Input: x = 121
Output: true

Example 2:
Input: x = -121
Output: false
Explanation: From left to right, it reads -121. From right to left, it becomes 121-. Therefore it is not a palindrome.


Example 3:
Input: x = 10
Output: false
Explanation: Reads 01 from right to left. Therefore it is not a palindrome.


Example 4:
Input: x = -101
Output: false

Constraints:
`-231 <= x <= 231 - 1`
Follow up: Could you solve it without converting the integer to a string?

### Generated Test Case:
```
: x = -121 Output: true Example 2: Input: x = -121 Output: false Explanation: Reads 01 from right to left. Therefore it is not a palindrome. Title: Palindrome Number: Palindrome Number: Palindrome Number: Palindrome Number: Palindrome Number: Palindrome Number: Palindrome Number: Palindrome Number: Palindrome Number: Palind
```

## Problem Description:
Given an input string (`s`) and a pattern (`p`), implement regular expression matching with support for `'.'` and `'*'` where:` `
`'.'` Matches any single character.​​​​
`'*'` Matches zero or more of the preceding element.

The matching should cover the entire input string (not partial).


Example 1:
Input: s = "aa", p = "a"
Output: false
Explanation: "a" does not match the entire string "aa".


Example 2:
Input: s = "aa", p = "a*"
Output: true
Explanation: '*' means zero or more of the preceding element, 'a'. Therefore, by repeating 'a' once, it becomes "aa".


Example 3:
Input: s = "ab", p = ".*"
Output: true
Explanation: ".*" means "zero or more (*) of any character (.)".


Example 4:
Input: s = "aab", p = "c*a*b"
Output: true
Explanation: c can be repeated 0 times, a can be repeated 1 time. Therefore, it matches "aab".


Example 5:
Input: s = "mississippi", p = "mis*is*p*."
Output: false

Constraints:
`0 <= s.length <= 20`
`0 <= p.length <= 30`
`s` contains only lowercase English letters.

`p` contains only lowercase English letters, `'.'`, and `'*'`.

It is guaranteed for each appearance of the character `'*'`, there will be a previous valid character to match.

### Generated Test Case:
```
: '*' Matches zero or more of the preceding element. The matching should cover the entire input string (not partial). Example 1: Input: s = "aa", p = "a*" Output: false Explanation: "a" does not match the entire string "aa"
```

## Problem Description:
Given `n` non-negative integers `a1, a2, ..., an` , where each represents a point at coordinate `(i, ai)`. `n` vertical lines are drawn such that the two endpoints of the line `i` is at `(i, ai)` and `(i, 0)`. Find two lines, which, together with the x-axis forms a container, such that the container contains the most water.

Notice that you may not slant the container.


Example 1:
Input: height = [1,8,6,2,5,4,8,3,7]
Output: 49
Explanation: The above vertical lines are represented by array [1,8,6,2,5,4,8,3,7]. In this case, the max area of water (blue section) the container can contain is 49.


Example 2:
Input: height = [1,1]
Output: 1

Example 3:
Input: height = [4,3,2,1,4]
Output: 16

Example 4:
Input: height = [1,2,1]
Output: 2

Constraints:
`n == height.length`
`2 <= n <= 105`
`0 <= height[i] <= 104`

### Generated Test Case:
```
:,,, = 105 = height[i] = 104. Title: Container With Most Water. Title: Container With Most Water. Title: Container With Most Water. Title: Container With Most Water. Title: Container With Most Water. Title: Container With Most Water. Title: Container With Most Water.
```

## Problem Description:
Roman numerals are represented by seven different symbols: `I`, `V`, `X`, `L`, `C`, `D` and `M`.

Symbol       Value
I             1
V             5
X             10
L             50
C             100
D             500
M             1000
For example, `2` is written as `II` in Roman numeral, just two one's added together. `12` is written as `XII`, which is simply `X + II`. The number `27` is written as `XXVII`, which is `XX + V + II`.

Roman numerals are usually written largest to smallest from left to right. However, the numeral for four is not `IIII`. Instead, the number four is written as `IV`. Because the one is before the five we subtract it making four. The same principle applies to the number nine, which is written as `IX`. There are six instances where subtraction is used:
`I` can be placed before `V` (5) and `X` (10) to make 4 and 9. 
`X` can be placed before `L` (50) and `C` (100) to make 40 and 90. 
`C` can be placed before `D` (500) and `M` (1000) to make 400 and 900.

Given an integer, convert it to a roman numeral.


Example 1:
Input: num = 3
Output: "III"

Example 2:
Input: num = 4
Output: "IV"

Example 3:
Input: num = 9
Output: "IX"

Example 4:
Input: num = 58
Output: "LVIII"
Explanation: L = 50, V = 5, III = 3.


Example 5:
Input: num = 1994
Output: "MCMXCIV"
Explanation: M = 1000, CM = 900, XC = 90 and IV = 4.


Constraints:
`1 <= num <= 3999`

### Generated Test Case:
```
num = 3 Output: "III" Example 2: Input: num = 4 Output: "III" Example 2: Input: num = 58 Output: "LVIII" Explanation: L = 50, V = 5, III = 3. Constraints: 1 = num = 3999. Title: Integer to Roman numerals are represented by seven different symbols:
```

## Problem Description:
Roman numerals are represented by seven different symbols: `I`, `V`, `X`, `L`, `C`, `D` and `M`.

Symbol       Value
I             1
V             5
X             10
L             50
C             100
D             500
M             1000
For example, `2` is written as `II` in Roman numeral, just two one's added together. `12` is written as `XII`, which is simply `X + II`. The number `27` is written as `XXVII`, which is `XX + V + II`.

Roman numerals are usually written largest to smallest from left to right. However, the numeral for four is not `IIII`. Instead, the number four is written as `IV`. Because the one is before the five we subtract it making four. The same principle applies to the number nine, which is written as `IX`. There are six instances where subtraction is used:
`I` can be placed before `V` (5) and `X` (10) to make 4 and 9. 
`X` can be placed before `L` (50) and `C` (100) to make 40 and 90. 
`C` can be placed before `D` (500) and `M` (1000) to make 400 and 900.

Given a roman numeral, convert it to an integer.


Example 1:
Input: s = "III"
Output: 3

Example 2:
Input: s = "IV"
Output: 4

Example 3:
Input: s = "IX"
Output: 9

Example 4:
Input: s = "LVIII"
Output: 58
Explanation: L = 50, V= 5, III = 3.


Example 5:
Input: s = "MCMXCIV"
Output: 1994
Explanation: M = 1000, CM = 900, XC = 90 and IV = 4.


Constraints:
`1 <= s.length <= 15`
`s` contains only the characters `('I', 'V', 'X', 'L', 'C', 'D', 'M')`.

It is guaranteed that `s` is a valid roman numeral in the range `[1, 3999]`.

### Generated Test Case:
```
: s = "III" Output: 4 Example 2: Input: s = "IV" Output: 4 Example 2: Input: s = "IV" Output: 4 Example 2: Input: s = "IV" Output: 9 Example 2: Input: s = "V" Output: 4 Example 2: Input: s = "IV" Output: 9 Example 2: Input:
```

## Problem Description:
Write a function to find the longest common prefix string amongst an array of strings.

If there is no common prefix, return an empty string `""`.


Example 1:
Input: strs = ["flower","flow","flight"]
Output: "fl"

Example 2:
Input: strs = ["dog","racecar","car"]
Output: ""
Explanation: There is no common prefix among the input strings.


Constraints:
`0 <= strs.length <= 200`
`0 <= strs[i].length <= 200`
`strs[i]` consists of only lower-case English letters.

### Generated Test Case:
```
= strs.length = 200 0 = strs[i].length = 200 strs[i] consists of only lower-case English letters.
```

## Problem Description:
Given an integer array nums, return all the triplets `[nums[i], nums[j], nums[k]]` such that `i != j`, `i != k`, and `j != k`, and `nums[i] + nums[j] + nums[k] == 0`.

Notice that the solution set must not contain duplicate triplets.


Example 1:
Input: nums = [-1,0,1,2,-1,-4]
Output: [[-1,-1,2],[-1,0,1]]

Example 2:
Input: nums = []
Output: []

Example 3:
Input: nums = [0]
Output: []

Constraints:
`0 <= nums.length <= 3000`
`-105 <= nums[i] <= 105`

### Generated Test Case:
```
: Given an integer array nums, return all the triplets [nums[i], nums[j], nums[k]] such that i!= j, i!= k, and j!= k, and j!= k, and j!= k, and j!
```

## Problem Description:
Given an array `nums` of n integers and an integer `target`, find three integers in `nums` such that the sum is closest to `target`. Return the sum of the three integers. You may assume that each input would have exactly one solution.


Example 1:
Input: nums = [-1,2,1,-4], target = 1
Output: 2
Explanation: The sum that is closest to the target is 2. (-1 + 2 + 1 = 2).


Constraints:
`3 <= nums.length <= 10^3`
`-10^3 <= nums[i] <= 10^3`
`-10^4 <= target <= 10^4`

### Generated Test Case:
```
: Given an array nums of n integers and an integer target, find three integers in nums such that the sum is closest to target. Return the sum of the three integers. You may assume each input would have exactly one solution. Title: 3Sum Closest: 3Sum Closest: 3Sum Closest: 3Sum Closest: 3Sum Close
```

## Problem Description:
Given a string containing digits from `2-9` inclusive, return all possible letter combinations that the number could represent. Return the answer in any order.

A mapping of digit to letters (just like on the telephone buttons) is given below. Note that 1 does not map to any letters.


Example 1:
Input: digits = "23"
Output: ["ad","ae","af","bd","be","bf","cd","ce","cf"]

Example 2:
Input: digits = ""
Output: []

Example 3:
Input: digits = "2"
Output: ["a","b","c"]

Constraints:
`0 <= digits.length <= 4`
`digits[i]` is a digit in the range `['2', '9']`.

### Generated Test Case:
```
0 = digits.length = 4 digits[i] is a digit in the range ['2', '9']. Title: Letter Combinations of a Phone Number of a Phone Number. Title: Letter Combinations of a Phone Number of a Phone Number.. Title: Letter Combinations of a Phone Number of a Phone Number.. Title:
```

## Problem Description:
Given an array `nums` of n integers and an integer `target`, are there elements a, b, c, and d in `nums` such that a + b + c + d = `target`? Find all unique quadruplets in the array which gives the sum of `target`.

Notice that the solution set must not contain duplicate quadruplets.


Example 1:
Input: nums = [1,0,-1,0,-2,2], target = 0
Output: [[-2,-1,1,2],[-2,0,0,2],[-1,0,0,1]]

Example 2:
Input: nums = [], target = 0
Output: []

Constraints:
`0 <= nums.length <= 200`
`-109 <= nums[i] <= 109`
`-109 <= target <= 109`

### Generated Test Case:
```
target? nums of n integers and an integer target. target?: Given an array nums of n integers and an integer target, are there elements a, b, c, and d in nums such that a + b + c + d = target? Find all unique quadr
```

## Problem Description:
Given the `head` of a linked list, remove the `nth` node from the end of the list and return its head.

Follow up: Could you do this in one pass?

Example 1:
Input: head = [1,2,3,4,5], n = 2
Output: [1,2,3,5]

Example 2:
Input: head = [1], n = 1
Output: []

Example 3:
Input: head = [1,2], n = 1
Output: [1]

Constraints:
The number of nodes in the list is `sz`.

`1 <= sz <= 30`
`0 <= Node.val <= 100`
`1 <= n <= sz`

### Generated Test Case:
```
: Given the head of a linked list, remove the nth node from the end of the list and return its head. Follow up: Could you do this in one pass? Title: Remove Nth Node From End of List and return its head.
```

## Problem Description:
Given a string `s` containing just the characters `'('`, `')'`, `'{'`, `'}'`, `'['` and `']'`, determine if the input string is valid.

An input string is valid if:
Open brackets must be closed by the same type of brackets.

Open brackets must be closed in the correct order.


Example 1:
Input: s = "()"
Output: true

Example 2:
Input: s = "()[]{}"
Output: true

Example 3:
Input: s = "(]"
Output: false

Example 4:
Input: s = "([)]"
Output: false

Example 5:
Input: s = "{[]}"
Output: true

Constraints:
`1 <= s.length <= 104`
`s` consists of parentheses only `'()[]{}'`.

### Generated Test Case:
```
: Given a string s containing just the characters '(', ')', '', '', '', '[' and ']', determine if the input string is valid if: Open brackets must be closed by the same type of brackets. Open brackets must be closed in correct order.
```

## Problem Description:
Merge two sorted linked lists and return it as a sorted list. The list should be made by splicing together the nodes of the first two lists.


Example 1:
Input: l1 = [1,2,4], l2 = [1,3,4]
Output: [1,1,2,3,4,4]

Example 2:
Input: l1 = [], l2 = []
Output: []

Example 3:
Input: l1 = [], l2 = [0]
Output: [0]

Constraints:
The number of nodes in both lists is in the range `[0, 50]`.

`-100 <= Node.val <= 100`
Both `l1` and `l2` are sorted in non-decreasing order.

### Generated Test Case:
```
= 100 Both l1 and l2 are sorted in non-decreasing order. Title: Merge Two Sorted Lists and return it as a sorted list. The list should be made by splicing together the nodes of the first two lists.
```

## Problem Description:
Given `n` pairs of parentheses, write a function to generate all combinations of well-formed parentheses.


Example 1:
Input: n = 3
Output: ["((()))","(()())","(())()","()(())","()()()"]

Example 2:
Input: n = 1
Output: ["()"]

Constraints:
`1 <= n <= 8`

### Generated Test Case:
```
n = 8. Title: Generate Parentheses: Generate Parentheses: Generate Parentheses: Generate Parentheses: Generate Parentheses: Generate Parentheses: Generate Parentheses: Generate Parentheses: Generate Parentheses: Generate Parentheses: Generate Parentheses: Generate Parentheses: Generate Parentheses: Generate Parentheses: Generate Parenthe
```

## Problem Description:
You are given an array of `k` linked-lists `lists`, each linked-list is sorted in ascending order.

Merge all the linked-lists into one sorted linked-list and return it.


Example 1:
Input: lists = [[1,4,5],[1,3,4],[2,6]]
Output: [1,1,2,3,4,4,5,6]
Explanation: The linked-lists are:
[
  1->4->5,
  1->3->4,
  2->6
]
merging them into one sorted list:
1->1->2->3->4->4->5->6

Example 2:
Input: lists = []
Output: []

Example 3:
Input: lists = [[]]
Output: []

Constraints:
`k == lists.length`
`0 <= k <= 10^4`
`0 <= lists[i].length <= 500`
`-10^4 <= lists[i][j] <= 10^4`
`lists[i]` is sorted in ascending order.

The sum of `lists[i].length` won't exceed `10^4`.

### Generated Test Case:
```
k linked-lists lists, each linked-list is sorted in ascending order. Each linked-list is sorted in ascending order. k == lists.length 0 = k = 500 -104 = lists[i][j] = 104 lists[i] is sorted in ascending
```

## Problem Description:
Given a linked list, swap every two adjacent nodes and return its head.


Example 1:
Input: head = [1,2,3,4]
Output: [2,1,4,3]

Example 2:
Input: head = []
Output: []

Example 3:
Input: head = [1]
Output: [1]

Constraints:
The number of nodes in the list is in the range `[0, 100]`.

`0 <= Node.val <= 100`
Follow up: Can you solve the problem without modifying the values in the list's nodes? (i.e., Only nodes themselves may be changed.)

### Generated Test Case:
```
: the list's nodes.:: Given a linked list, swap every two adjacent nodes and return its head. Title: Swap Nodes in Pairs: Swap Nodes in Pairs: Swap Nodes in Pairs: Swap Nodes in Pairs: Swap Nodes in Pairs: Swap Nodes in Pairs: Swap Nodes in Pairs: Swap Nodes in Pairs: Swap
```

## Problem Description:
Given a linked list, reverse the nodes of a linked list k at a time and return its modified list.

k is a positive integer and is less than or equal to the length of the linked list. If the number of nodes is not a multiple of k then left-out nodes, in the end, should remain as it is.

Follow up:
Could you solve the problem in `O(1)` extra memory space?
You may not alter the values in the list's nodes, only nodes itself may be changed.


Example 1:
Input: head = [1,2,3,4,5], k = 2
Output: [2,1,4,3,5]

Example 2:
Input: head = [1,2,3,4,5], k = 3
Output: [3,2,1,4,5]

Example 3:
Input: head = [1,2,3,4,5], k = 1
Output: [1,2,3,4,5]

Example 4:
Input: head = [1], k = 1
Output: [1]

Constraints:
The number of nodes in the list is in the range `sz`.

`1 <= sz <= 5000`
`0 <= Node.val <= 1000`
`1 <= k <= sz`

### Generated Test Case:
```
k, k = 2 Output: [2,1,4,3,5] Example 2: Input: head = [1,2,3,4,5], k = 3 Output: [3,2,3,4,5] Example 3: Input: head = [1,2,3,4,5], k = 1 Output: [1,2,3,4,5] Example 4: Input: head = [1], k = 1 Output: [1,2,3,4,5] Example 4
```

## Problem Description:
Given a sorted array nums, remove the duplicates in-place such that each element appears only once and returns the new length.

Do not allocate extra space for another array, you must do this by modifying the input array in-place with O(1) extra memory.

Clarification:
Confused why the returned value is an integer but your answer is an array?
Note that the input array is passed in by reference, which means a modification to the input array will be known to the caller as well.

Internally you can think of this:
// nums is passed in by reference. (i.e., without making a copy)
int len = removeDuplicates(nums);
// any modification to nums in your function would be known by the caller.

// using the length returned by your function, it prints the first len elements.

for (int i = 0; i < len; i++) {
    print(nums[i]);
}

Example 1:
Input: nums = [1,1,2]
Output: 2, nums = [1,2]
Explanation: Your function should return length = `2`, with the first two elements of `nums` being `1` and `2` respectively. It doesn't matter what you leave beyond the returned length.


Example 2:
Input: nums = [0,0,1,1,1,2,2,3,3,4]
Output: 5, nums = [0,1,2,3,4]
Explanation: Your function should return length = `5`, with the first five elements of `nums` being modified to `0`, `1`, `2`, `3`, and `4` respectively. It doesn't matter what values are set beyond the returned length.


Constraints:
`0 <= nums.length <= 3 * 104`
`-104 <= nums[i] <= 104`
`nums` is sorted in ascending order.

### Generated Test Case:
```
nums, remove the duplicates in-place so that each element appears only once and returns the new length. It doesn't matter what you leave beyond the returned length. Title: Remove Duplicates from Sorted Array Title: Remove Duplicates from Sorted Array. Title: Remove Duplicates from Sorted Array: Remove Duplicates from Sorted Array.
```

## Problem Description:
Given an array nums and a value `val`, remove all instances of that value in-place and return the new length.

Do not allocate extra space for another array, you must do this by modifying the input array in-place with `O(1)` extra memory.

The order of elements can be changed. It doesn't matter what you leave beyond the new length.

Clarification:
Confused why the returned value is an integer but your answer is an array?
Note that the input array is passed in by reference, which means a modification to the input array will be known to the caller as well.

Internally you can think of this:
// nums is passed in by reference. (i.e., without making a copy)
int len = removeElement(nums, val);
// any modification to nums in your function would be known by the caller.

// using the length returned by your function, it prints the first len elements.

for (int i = 0; i < len; i++) {
    print(nums[i]);
}

Example 1:
Input: nums = [3,2,2,3], val = 3
Output: 2, nums = [2,2]
Explanation: Your function should return length = 2, with the first two elements of nums being 2.

It doesn't matter what you leave beyond the returned length. For example if you return 2 with nums = [2,2,3,3] or nums = [2,2,0,0], your answer will be accepted.


Example 2:
Input: nums = [0,1,2,2,3,0,4,2], val = 2
Output: 5, nums = [0,1,4,0,3]
Explanation: Your function should return length = `5`, with the first five elements of `nums` containing `0`, `1`, `3`, `0`, and 4. Note that the order of those five elements can be arbitrary. It doesn't matter what values are set beyond the returned length.


Constraints:
`0 <= nums.length <= 100`
`0 <= nums[i] <= 50`
`0 <= val <= 100`

### Generated Test Case:
```
nums.length = 100 0 = nums.length = 100 0 = val = 100. Title: Remove Element: Remove Element: Remove Element: Remove Element: Remove Element: Remove Element: Remove Element: Remove Element: Remove Element: Remove Element: Remove Element: Remove Element: Remove Element: Remove Element:
```

## Problem Description:
Implement strStr().

Return the index of the first occurrence of needle in haystack, or `-1` if `needle` is not part of `haystack`.

Clarification:
What should we return when `needle` is an empty string? This is a great question to ask during an interview.

For the purpose of this problem, we will return 0 when `needle` is an empty string. This is consistent to C's strstr() and Java's indexOf().


Example 1:
Input: haystack = "hello", needle = "ll"
Output: 2

Example 2:
Input: haystack = "aaaaa", needle = "bba"
Output: -1

Example 3:
Input: haystack = "", needle = ""
Output: 0

Constraints:
`0 <= haystack.length, needle.length <= 5 * 104`
`haystack` and `needle` consist of only lower-case English characters.

### Generated Test Case:
```
needle is an empty string.: 0 = haystack.length, needle.length = 5 * 104 haystack and needle consist of only lower-case English characters.
```

## Problem Description:
Given two integers `dividend` and `divisor`, divide two integers without using multiplication, division, and mod operator.

Return the quotient after dividing `dividend` by `divisor`.

The integer division should truncate toward zero, which means losing its fractional part. For example, `truncate(8.345) = 8` and `truncate(-2.7335) = -2`.

Note: Assume we are dealing with an environment that could only store integers within the 32-bit signed integer range: `[−231, 231 − 1]`. For this problem, assume that your function returns `231 − 1` when the division result overflows.


Example 1:
Input: dividend = 10, divisor = 3
Output: 3
Explanation: 10/3 = truncate(3.33333..) = 3.


Example 2:
Input: dividend = 7, divisor = -3
Output: -2
Explanation: 7/-3 = truncate(-2.33333..) = -2.


Example 3:
Input: dividend = 0, divisor = 1
Output: 0

Example 4:
Input: dividend = 1, divisor = 1
Output: 1

Constraints:
`-231 <= dividend, divisor <= 231 - 1`
`divisor != 0`

### Generated Test Case:
```
dividend by divisor. The division should truncate toward zero, which means losing its fractional part. Title: Divide Two Integers: Divide Two Integers!= 0. Title: Divide Two Integers: Divide Two Integers: Divide Two Integers: Divide Two Integers: Divide Two Integers
```

## Problem Description:
You are given a string `s` and an array of strings `words` of the same length. Return all starting indices of substring(s) in `s` that is a concatenation of each word in `words` exactly once, in any order, and without any intervening characters.

You can return the answer in any order.


Example 1:
Input: s = "barfoothefoobarman", words = ["foo","bar"]
Output: [0,9]
Explanation: Substrings starting at index 0 and 9 are "barfoo" and "foobar" respectively.

The output order does not matter, returning [9,0] is fine too.


Example 2:
Input: s = "wordgoodgoodgoodbestword", words = ["word","good","best","word"]
Output: []

Example 3:
Input: s = "barfoofoobarthefoobarman", words = ["bar","foo","the"]
Output: [6,9,12]

Constraints:
`1 <= s.length <= 104`
`s` consists of lower-case English letters.

`1 <= words.length <= 5000`
`1 <= words[i].length <= 30`
`words[i]` consists of lower-case English letters.

### Generated Test Case:
```
s and an array of strings words of the same length. Return all starting indices of substring(s) in s that is a concatenation of each word in words exactly once, in any order, and without any intervening characters. The output order does not matter, returning [9,0] is fine too. Title: Substring with Concatenation of All Words.
```

## Problem Description:
Implement next permutation, which rearranges numbers into the lexicographically next greater permutation of numbers.

If such an arrangement is not possible, it must rearrange it as the lowest possible order (i.e., sorted in ascending order).

The replacement must be in place and use only constant extra memory.


Example 1:
Input: nums = [1,2,3]
Output: [1,3,2]

Example 2:
Input: nums = [3,2,1]
Output: [1,2,3]

Example 3:
Input: nums = [1,1,5]
Output: [1,5,1]

Example 4:
Input: nums = [1]
Output: [1]

Constraints:
`1 <= nums.length <= 100`
`0 <= nums[i] <= 100`

### Generated Test Case:
```
: Implement next permutation, which rearranges numbers into the lexicographically next greater permutation of numbers. If such an arrangement is not possible, it must rearrange it as the lowest possible order (i.e., sorted in ascending order). Title: Next Permutation, which rearranges numbers into the lexicographically next greater permutation of numbers.
```

## Problem Description:
Given a string containing just the characters `'('` and `')'`, find the length of the longest valid (well-formed) parentheses substring.


Example 1:
Input: s = "(()"
Output: 2
Explanation: The longest valid parentheses substring is "()".


Example 2:
Input: s = ")()())"
Output: 4
Explanation: The longest valid parentheses substring is "()()".


Example 3:
Input: s = ""
Output: 0

Constraints:
`0 <= s.length <= 3 * 104`
`s[i]` is `'('`, or `')'`.

### Generated Test Case:
```
: Given a string containing just the characters '(' and ')', find the length of the longest valid parentheses substring is "()". Title: Longest Valid Parentheses Substrings: Longest Valid Parentheses Substrings: Longest Valid Parentheses Substrings: Longest Valid Parentheses Substrings: Longest Valid Parentheses Substrings: Longest Valid Parentheses
```

## Problem Description:
There is an integer array `nums` sorted in ascending order (with distinct values).

Prior to being passed to your function, `nums` is rotated at an unknown pivot index `k` (`0 <= k < nums.length`) such that the resulting array is `[nums[k], nums[k+1], ..., nums[n-1], nums[0], nums[1], ..., nums[k-1]]` (0-indexed). For example, `[0,1,2,4,5,6,7]` might be rotated at pivot index `3` and become `[4,5,6,7,0,1,2]`.

Given the array `nums` after the rotation and an integer `target`, return the index of `target` if it is in `nums`, or `-1` if it is not in `nums`.


Example 1:
Input: nums = [4,5,6,7,0,1,2], target = 0
Output: 4

Example 2:
Input: nums = [4,5,6,7,0,1,2], target = 3
Output: -1

Example 3:
Input: nums = [1], target = 0
Output: -1

Constraints:
`1 <= nums.length <= 5000`
`-104 <= nums[i] <= 104`
All values of `nums` are unique.

`nums` is guaranteed to be rotated at some pivot.

`-104 <= target <= 104`
Follow up: Can you achieve this in `O(log n)` time complexity?

### Generated Test Case:
```
nums after the rotation and an integer target, return the index of target if it is in nums, or -1 if it is not in nums. Title: Search in Rotated Sorted Array.
```

## Problem Description:
Given an array of integers `nums` sorted in ascending order, find the starting and ending position of a given `target` value.

If `target` is not found in the array, return `[-1, -1]`.

Follow up: Could you write an algorithm with `O(log n)` runtime complexity?

Example 1:
Input: nums = [5,7,7,8,8,10], target = 8
Output: [3,4]

Example 2:
Input: nums = [5,7,7,8,8,10], target = 6
Output: [-1,-1]

Example 3:
Input: nums = [], target = 0
Output: [-1,-1]

Constraints:
`0 <= nums.length <= 105`
`-109 <= nums[i] <= 109`
`nums` is a non-decreasing array.

`-109 <= target <= 109`

### Generated Test Case:
```
target value. -109 = nums[i] = 109 nums is a non-decreasing array. Title: Find First and Last Position of Element in Sorted Array. Title: Find First and Last Position of Element in Sorted Array.
```

## Problem Description:
Given a sorted array of distinct integers and a target value, return the index if the target is found. If not, return the index where it would be if it were inserted in order.


Example 1:
Input: nums = [1,3,5,6], target = 5
Output: 2

Example 2:
Input: nums = [1,3,5,6], target = 2
Output: 1

Example 3:
Input: nums = [1,3,5,6], target = 7
Output: 4

Example 4:
Input: nums = [1,3,5,6], target = 0
Output: 0

Example 5:
Input: nums = [1], target = 0
Output: 0

Constraints:
`1 <= nums.length <= 104`
`-104 <= nums[i] <= 104`
`nums` contains distinct values sorted in ascending order.

`-104 <= target <= 104`

### Generated Test Case:
```
a sorted array of distinct integers and a target value, return the index if the target is found. If not, return the index where it would be if it were found.length = 104 -104 = nums[i] = 104 nums contains distinct values sorted in ascending order. Title: Search Insert Position: Search Insert Position: Search Insert Position: Search Insert
```

## Problem Description:
Determine if a `9 x 9` Sudoku board is valid. Only the filled cells need to be validated according to the following rules:
Each row must contain the digits `1-9` without repetition.

Each column must contain the digits `1-9` without repetition.

Each of the nine `3 x 3` sub-boxes of the grid must contain the digits `1-9` without repetition.

Note:
A Sudoku board (partially filled) could be valid but is not necessarily solvable.

Only the filled cells need to be validated according to the mentioned rules.


Example 1:
Input: board = 
[["5","3",".",".","7",".",".",".","."]
,["6",".",".","1","9","5",".",".","."]
,[".","9","8",".",".",".",".","6","."]
,["8",".",".",".","6",".",".",".","3"]
,["4",".",".","8",".","3",".",".","1"]
,["7",".",".",".","2",".",".",".","6"]
,[".","6",".",".",".",".","2","8","."]
,[".",".",".","4","1","9",".",".","5"]
,[".",".",".",".","8",".",".","7","9"]]
Output: true

Example 2:
Input: board = 
[["8","3",".",".","7",".",".",".","."]
,["6",".",".","1","9","5",".",".","."]
,[".","9","8",".",".",".",".","6","."]
,["8",".",".",".","6",".",".",".","3"]
,["4",".",".","8",".","3",".",".","1"]
,["7",".",".",".","2",".",".",".","6"]
,[".","6",".",".",".",".","2","8","."]
,[".",".",".","4","1","9",".",".","5"]
,[".",".",".",".","8",".",".","7","9"]]
Output: false

Explanation: Same as Example 1, except with the 5 in the top left corner being modified to 8. Since there are two 8's in the top left 3x3 sub-box, it is invalid.


Constraints:
`board.length == 9`
`board[i].length == 9`
`board[i][j]` is a digit or `'.'`.

### Generated Test Case:
```
: 9 x 9 Sudoku board is valid.: board[i][j] is a digit or '.'..: 8 8 9 x 9 Sudoku board is valid. 1-9 without repetition.: Each row must contain the digits 1-9 without repetition.::::
```

## Problem Description:
Write a program to solve a Sudoku puzzle by filling the empty cells.

A sudoku solution must satisfy all of the following rules:
Each of the digits `1-9` must occur exactly once in each row.

Each of the digits `1-9` must occur exactly once in each column.

Each of the digits `1-9` must occur exactly once in each of the 9 `3x3` sub-boxes of the grid.

The `'.'` character indicates empty cells.


Example 1:
Input: board = [["5","3",".",".","7",".",".",".","."],["6",".",".","1","9","5",".",".","."],[".","9","8",".",".",".",".","6","."],["8",".",".",".","6",".",".",".","3"],["4",".",".","8",".","3",".",".","1"],["7",".",".",".","2",".",".",".","6"],[".","6",".",".",".",".","2","8","."],[".",".",".","4","1","9",".",".","5"],[".",".",".",".","8",".",".","7","9"]]
Output: [["5","3","4","6","7","8","9","1","2"],["6","7","2","1","9","5","3","4","8"],["1","9","8","3","4","2","5","6","7"],["8","5","9","7","6","1","4","2","3"],["4","2","6","8","5","3","7","9","1"],["7","1","3","9","2","4","8","5","6"],["9","6","1","5","3","7","2","8","4"],["2","8","7","4","1","9","6","3","5"],["3","4","5","2","8","6","1","7","9"]]
Explanation: The input board is shown above and the only valid solution is shown below:

Constraints:
`board.length == 9`
`board[i].length == 9`
`board[i][j]` is a digit or `'.'`.

It is guaranteed that the input board has only one solution.

### Generated Test Case:
```
","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","5","
```

## Problem Description:
The count-and-say sequence is a sequence of digit strings defined by the recursive formula:
`countAndSay(1) = "1"`
`countAndSay(n)` is the way you would "say" the digit string from `countAndSay(n-1)`, which is then converted into a different digit string.

To determine how you "say" a digit string, split it into the minimal number of groups so that each group is a contiguous section all of the same character. Then for each group, say the number of characters, then say the character. To convert the saying into a digit string, replace the counts with a number and concatenate every saying.

For example, the saying and conversion for digit string `"3322251"`:
Given a positive integer `n`, return the `nth` term of the count-and-say sequence.


Example 1:
Input: n = 1
Output: "1"
Explanation: This is the base case.


Example 2:
Input: n = 4
Output: "1211"
Explanation:
countAndSay(1) = "1"
countAndSay(2) = say "1" = one 1 = "11"
countAndSay(3) = say "11" = two 1's = "21"
countAndSay(4) = say "21" = one 2 + one 1 = "12" + "11" = "1211"

Constraints:
`1 <= n <= 30`

### Generated Test Case:
```
: "1211" Explanation: countAndSay(1) = "1" countAndSay(n) is the way you would "say" a digit string from countAndSay(n-1), which is then converted into a different digit string. To determine how you "say" a digit string, split it into the minimal number of groups so that each group is
```

## Problem Description:
Given an array of distinct integers `candidates` and a target integer `target`, return a list of all unique combinations of `candidates` where the chosen numbers sum to `target`. You may return the combinations in any order.

The same number may be chosen from `candidates` an unlimited number of times. Two combinations are unique if the frequency of at least one of the chosen numbers is different.

It is guaranteed that the number of unique combinations that sum up to `target` is less than `150` combinations for the given input.


Example 1:
Input: candidates = [2,3,6,7], target = 7
Output: [[2,2,3],[7]]
Explanation:
2 and 3 are candidates, and 2 + 2 + 3 = 7. Note that 2 can be used multiple times.

7 is a candidate, and 7 = 7.

These are the only two combinations.


Example 2:
Input: candidates = [2,3,5], target = 8
Output: [[2,2,2,2],[2,3,3],[3,5]]

Example 3:
Input: candidates = [2], target = 1
Output: []

Example 4:
Input: candidates = [1], target = 1
Output: [[1]]

Example 5:
Input: candidates = [1], target = 2
Output: [[1,1]]

Constraints:
`1 <= candidates.length <= 30`
`1 <= candidates[i] <= 200`
All elements of `candidates` are distinct.

`1 <= target <= 500`

### Generated Test Case:
```
candidates and a target integer target. You may return the combinations in any order. The number of unique combinations that sum up to target is less than 150 combinations for the given input. Note that 2 can be used multiple times. 7 is a candidate, and 7 = 7. These are only two combinations.
```

## Problem Description:
Given a collection of candidate numbers (`candidates`) and a target number (`target`), find all unique combinations in `candidates` where the candidate numbers sum to `target`.

Each number in `candidates` may only be used once in the combination.

Note: The solution set must not contain duplicate combinations.


Example 1:
Input: candidates = [10,1,2,7,6,1,5], target = 8
Output: 
[
[1,1,6],
[1,2,5],
[1,7],
[2,6]
]

Example 2:
Input: candidates = [2,5,2,1,2], target = 5
Output: 
[
[1,2,2],
[5]
]

Constraints:
`1 <= candidates.length <= 100`
`1 <= candidates[i] <= 50`
`1 <= target <= 30`

### Generated Test Case:
```
candidates, find all unique combinations in candidates where the candidate numbers sum to target. Each number in candidates may only be used once in the combination.length = 100 1 = candidates[i] = 50 1 = target = 30. Title: Combination Sum II.
```

## Problem Description:
Given an unsorted integer array `nums`, find the smallest missing positive integer.


Example 1:
Input: nums = [1,2,0]
Output: 3

Example 2:
Input: nums = [3,4,-1,1]
Output: 2

Example 3:
Input: nums = [7,8,9,11,12]
Output: 1

Constraints:
`0 <= nums.length <= 300`
`-231 <= nums[i] <= 231 - 1`
Follow up: Could you implement an algorithm that runs in `O(n)` time and uses constant extra space?

### Generated Test Case:
```
Given an unsorted integer array nums, find the smallest missing positive integer. Title: First Missing Positive Positive: First Missing Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive Positive
```

## Problem Description:
Given `n` non-negative integers representing an elevation map where the width of each bar is `1`, compute how much water it can trap after raining.


Example 1:
Input: height = [0,1,0,2,1,0,1,3,2,1,2,1]
Output: 6
Explanation: The above elevation map (black section) is represented by array [0,1,0,2,1,0,1,3,2,1,2,1]. In this case, 6 units of rain water (blue section) are being trapped.


Example 2:
Input: height = [4,2,0,3,2,5]
Output: 9

Constraints:
`n == height.length`
`0 <= n <= 3 * 104`
`0 <= height[i] <= 105`

### Generated Test Case:
```
n == height.length 0 = n = 3 * 104 0 = height[i] = 105. Title: Trapping Rain Water (blue section) is a test case for: Given n non-negative integers representing an elevation map where the width of each bar is 1, compute how much water it can trap after raining. Title
```

## Problem Description:
Given two non-negative integers `num1` and `num2` represented as strings, return the product of `num1` and `num2`, also represented as a string.

Note: You must not use any built-in BigInteger library or convert the inputs to integer directly.


Example 1:
Input: num1 = "2", num2 = "3"
Output: "6"

Example 2:
Input: num1 = "123", num2 = "456"
Output: "56088"

Constraints:
`1 <= num1.length, num2.length <= 200`
`num1` and `num2` consist of digits only.

Both `num1` and `num2` do not contain any leading zero, except the number `0` itself.

### Generated Test Case:
```
num1 and num2 represented as strings, return the product of num1 and num2, also represented as strings. Note: You must not use any built-in BigInteger library or convert the inputs to integer directly. Title: Multiply Strings: Multiply Strings: Multiply Strings: Multiply Strings: Multiply Strings: Multiply Strings
```

## Problem Description:
Given an input string (`s`) and a pattern (`p`), implement wildcard pattern matching with support for `'?'` and `'*'` where:
`'?'` Matches any single character.

`'*'` Matches any sequence of characters (including the empty sequence).

The matching should cover the entire input string (not partial).


Example 1:
Input: s = "aa", p = "a"
Output: false
Explanation: "a" does not match the entire string "aa".


Example 2:
Input: s = "aa", p = "*"
Output: true
Explanation: '*' matches any sequence.


Example 3:
Input: s = "cb", p = "?a"
Output: false
Explanation: '?' matches 'c', but the second letter is 'a', which does not match 'b'.


Example 4:
Input: s = "adceb", p = "*a*b"
Output: true
Explanation: The first '*' matches the empty sequence, while the second '*' matches the substring "dce".


Example 5:
Input: s = "acdcb", p = "a*c?b"
Output: false

Constraints:
`0 <= s.length, p.length <= 2000`
`s` contains only lowercase English letters.

`p` contains only lowercase English letters, `'?'` or `'*'`.

### Generated Test Case:
```
: '*' matches any sequence. '*' Matches any sequence of characters (including the empty sequence). The matching should cover the entire input string (not partial). Title: Wildcard Matching:
```

## Problem Description:
Given an array of non-negative integers `nums`, you are initially positioned at the first index of the array.

Each element in the array represents your maximum jump length at that position.

Your goal is to reach the last index in the minimum number of jumps.

You can assume that you can always reach the last index.


Example 1:
Input: nums = [2,3,1,1,4]
Output: 2
Explanation: The minimum number of jumps to reach the last index is 2. Jump 1 step from index 0 to 1, then 3 steps to the last index.


Example 2:
Input: nums = [2,3,0,1,4]
Output: 2

Constraints:
`1 <= nums.length <= 1000`
`0 <= nums[i] <= 105`

### Generated Test Case:
```
: Given an array of non-negative integers nums, you are initially positioned at the first index of the array. Each element in the array represents your maximum jump length at that position. The minimum number of jumps to reach the last index is 2. Jump 1 step from index 0 to 1, then 3 steps to the last index. Title: Jump Game II.
```

## Problem Description:
Given an array `nums` of distinct integers, return all the possible permutations. You can return the answer in any order.


Example 1:
Input: nums = [1,2,3]
Output: [[1,2,3],[1,3,2],[2,1,3],[2,3,1],[3,1,2],[3,2,1]]

Example 2:
Input: nums = [0,1]
Output: [[0,1],[1,0]]

Example 3:
Input: nums = [1]
Output: [[1]]

Constraints:
`1 <= nums.length <= 6`
`-10 <= nums[i] <= 10`
All the integers of `nums` are unique.

### Generated Test Case:
```
nums = [1,2,3] Output: [[1,2,3],[1,3,2],[2,1,3,1],[2,3,1],[3,1,2],[3,2,1]] Example 2: Input: nums = [0,1] Output: [0,1],[2,3,1],[3,1,2],[3,2,1]] Example 3: Input: nums = [1] Out
```

## Problem Description:
Given a collection of numbers, `nums`, that might contain duplicates, return all possible unique permutations in any order.


Example 1:
Input: nums = [1,1,2]
Output:
[[1,1,2],
 [1,2,1],
 [2,1,1]]

Example 2:
Input: nums = [1,2,3]
Output: [[1,2,3],[1,3,2],[2,1,3],[2,3,1],[3,1,2],[3,2,1]]

Constraints:
`1 <= nums.length <= 8`
`-10 <= nums[i] <= 10`

### Generated Test Case:
```
= nums.length = 8 -10 = nums[i] = 10. Title: Permutations II. Title: Permutations II. Title: Permutations II. Title: Permutations II. Title: Permutations II. Title: Permutations II. Title: Permutations II. Title: Permutations II. Title: Permutations II. Title: Permut
```

## Problem Description:
You are given an n x n 2D `matrix` representing an image, rotate the image by 90 degrees (clockwise).

You have to rotate the image in-place, which means you have to modify the input 2D matrix directly. DO NOT allocate another 2D matrix and do the rotation.


Example 1:
Input: matrix = [[1,2,3],[4,5,6],[7,8,9]]
Output: [[7,4,1],[8,5,2],[9,6,3]]

Example 2:
Input: matrix = [[5,1,9,11],[2,4,8,10],[13,3,6,7],[15,14,12,16]]
Output: [[15,13,2,5],[14,3,4,1],[12,6,8,9],[16,7,10,11]]

Example 3:
Input: matrix = [[1]]
Output: [[1]]

Example 4:
Input: matrix = [[1,2],[3,4]]
Output: [[3,1],[4,2]]

Constraints:
`matrix.length == n`
`matrix[i].length == n`
`1 <= n <= 20`
`-1000 <= matrix[i][j] <= 1000`

### Generated Test Case:
```
matrix representing an image, rotate the image by 90 degrees (clockwise). You have to rotate the image in-place, which means you have to modify the input 2D matrix directly.
```

## Problem Description:
Given an array of strings `strs`, group the anagrams together. You can return the answer in any order.

An Anagram is a word or phrase formed by rearranging the letters of a different word or phrase, typically using all the original letters exactly once.


Example 1:
Input: strs = ["eat","tea","tan","ate","nat","bat"]
Output: [["bat"],["nat","tan"],["ate","eat","tea"]]

Example 2:
Input: strs = [""]
Output: [[""]]

Example 3:
Input: strs = ["a"]
Output: [["a"]]

Constraints:
`1 <= strs.length <= 104`
`0 <= strs[i].length <= 100`
`strs[i]` consists of lower-case English letters.

### Generated Test Case:
```
strs is a word or phrase formed by rearranging the letters of a different word or phrase, typically using all the original letters exactly once.length = 100 strs[i] consists of lower-case English letters. Title: Group Anagrams: Group Anagrams: Group Anagrams: Group Anagrams: Group Anagrams: Group Anagrams: Group Anagrams
```

## Problem Description:
Implement pow(x, n), which calculates `x` raised to the power `n` (i.e., `xn`).


Example 1:
Input: x = 2.00000, n = 10
Output: 1024.00000

Example 2:
Input: x = 2.10000, n = 3
Output: 9.26100

Example 3:
Input: x = 2.00000, n = -2
Output: 0.25000
Explanation: 2-2 = 1/22 = 1/4 = 0.25

Constraints:
`-100.0 < x < 100.0`
`-231 <= n <= 231-1`
`-104 <= xn <= 104`

### Generated Test Case:
```
: Implement pow(x, n), which calculates x raised to the power n (i.e., xn). Example 1: Input: x = 2.00000, n = 10 Output: 1024.00000 Example 2: Input: x = 2.10000, n = 3 Output: 9.26100 Example 3: Input: x = 2.00000, n =
```

## Problem Description:
The n-queens puzzle is the problem of placing `n` queens on an `n x n` chessboard such that no two queens attack each other.

Given an integer `n`, return all distinct solutions to the n-queens puzzle.

Each solution contains a distinct board configuration of the n-queens' placement, where `'Q'` and `'.'` both indicate a queen and an empty space, respectively.


Example 1:
Input: n = 4
Output: [[".Q..","...Q","Q...","..Q."],["..Q.","Q...","...Q",".Q.."]]
Explanation: There exist two distinct solutions to the 4-queens puzzle as shown above

Example 2:
Input: n = 1
Output: [["Q"]]

Constraints:
`1 <= n <= 9`

### Generated Test Case:
```
: 'Q' and '.' indicate a queen and an empty space, respectively. Q...","...Q",".Q.."] Explanation: There exist two distinct solutions to the 4-queens puzzle. Title: N-Queens puzzle is the problem of placing n queens on an n x n chessboard such that no two queens attack each other
```

## Problem Description:
The n-queens puzzle is the problem of placing `n` queens on an `n x n` chessboard such that no two queens attack each other.

Given an integer `n`, return the number of distinct solutions to the n-queens puzzle.


Example 1:
Input: n = 4
Output: 2
Explanation: There are two distinct solutions to the 4-queens puzzle as shown.


Example 2:
Input: n = 1
Output: 1

Constraints:
`1 <= n <= 9`

### Generated Test Case:
```
: 1 = n = 9. Title: N-Queens II. Title: N-Queens II. Title: N-Queens II. Title: N-Queens II. Title: N-Queens II. Title: N-Queens II. Title: N-Queens II. Title: N-Queens II. Title: N
```

## Problem Description:
Given an integer array `nums`, find the contiguous subarray (containing at least one number) which has the largest sum and return its sum.


Example 1:
Input: nums = [-2,1,-3,4,-1,2,1,-5,4]
Output: 6
Explanation: [4,-1,2,1] has the largest sum = 6.


Example 2:
Input: nums = [1]
Output: 1

Example 3:
Input: nums = [5,4,-1,7,8]
Output: 23

Constraints:
`1 <= nums.length <= 3 * 104`
`-105 <= nums[i] <= 105`
Follow up: If you have figured out the `O(n)` solution, try coding another solution using the divide and conquer approach, which is more subtle.

### Generated Test Case:
```
O(n) solution, try coding another solution using the divide and conquer approach, which is more subtle. Title: Maximum Subarray: Maximum Subarray: Maximum Subarray: Maximum Subarray: Maximum Subarray: Maximum Subarray: Maximum Subarray: Maximum Subarray: Maximum Subarray: Maximum Subarray: Maximum Subarray: Maximum Subarray: Maximum Subarray: Maximum Subarray:
```

## Problem Description:
Given an `m x n` `matrix`, return all elements of the `matrix` in spiral order.


Example 1:
Input: matrix = [[1,2,3],[4,5,6],[7,8,9]]
Output: [1,2,3,6,9,8,7,4,5]

Example 2:
Input: matrix = [[1,2,3,4],[5,6,7,8],[9,10,11,12]]
Output: [1,2,3,4,8,12,11,10,9,5,6,7]

Constraints:
`m == matrix.length`
`n == matrix[i].length`
`1 <= m, n <= 10`
`-100 <= matrix[i][j] <= 100`

### Generated Test Case:
```
: Given an m x n matrix, return all elements of the matrix in spiral order.
```

## Problem Description:
Given an array of non-negative integers `nums`, you are initially positioned at the first index of the array.

Each element in the array represents your maximum jump length at that position.

Determine if you are able to reach the last index.


Example 1:
Input: nums = [2,3,1,1,4]
Output: true
Explanation: Jump 1 step from index 0 to 1, then 3 steps to the last index.


Example 2:
Input: nums = [3,2,1,0,4]
Output: false
Explanation: You will always arrive at index 3 no matter what. Its maximum jump length is 0, which makes it impossible to reach the last index.


Constraints:
`1 <= nums.length <= 3 * 104`
`0 <= nums[i] <= 105`

### Generated Test Case:
```
:: Jump 1 step from index 0 to 1, then 3 steps to the last index. Constraints: 1 = nums.length = 3 * 104 0 = nums[i] = 105. Title: Jump Game: Jump Game: Jump Game: Jump Game: Jump Game: Jump Game: Jump Game: Jump Game: Jump Game: Jump Game: Jump Game:
```

## Problem Description:
Given an array of `intervals` where `intervals[i] = [starti, endi]`, merge all overlapping intervals, and return an array of the non-overlapping intervals that cover all the intervals in the input.


Example 1:
Input: intervals = [[1,3],[2,6],[8,10],[15,18]]
Output: [[1,6],[8,10],[15,18]]
Explanation: Since intervals [1,3] and [2,6] overlaps, merge them into [1,6].


Example 2:
Input: intervals = [[1,4],[4,5]]
Output: [[1,5]]
Explanation: Intervals [1,4] and [4,5] are considered overlapping.


Constraints:
`1 <= intervals.length <= 104`
`intervals[i].length == 2`
`0 <= starti <= endi <= 104`

### Generated Test Case:
```
intervals where intervals[i] = [starti, endi], merge all overlapping intervals, and return an array of the non-overlapping intervals that cover all intervals in the input. Example 1: Input: intervals = [1,3],[2,6],[8,10],[15,18]] Output: [1,6],[8,10],[15,18]] Explan
```

## Problem Description:
Given a set of non-overlapping intervals, insert a new interval into the intervals (merge if necessary).

You may assume that the intervals were initially sorted according to their start times.


Example 1:
Input: intervals = [[1,3],[6,9]], newInterval = [2,5]
Output: [[1,5],[6,9]]

Example 2:
Input: intervals = [[1,2],[3,5],[6,7],[8,10],[12,16]], newInterval = [4,8]
Output: [[1,2],[3,10],[12,16]]
Explanation: Because the new interval `[4,8]` overlaps with `[3,5],[6,7],[8,10]`.


Example 3:
Input: intervals = [], newInterval = [5,7]
Output: [[5,7]]

Example 4:
Input: intervals = [[1,5]], newInterval = [2,3]
Output: [[1,5]]

Example 5:
Input: intervals = [[1,5]], newInterval = [2,7]
Output: [[1,7]]

Constraints:
`0 <= intervals.length <= 104`
`intervals[i].length == 2`
`0 <= intervals[i][0] <= intervals[i][1] <= 105`
`intervals` is sorted by `intervals[i][0]` in ascending order.

`newInterval.length == 2`
`0 <= newInterval[0] <= newInterval[1] <= 105`

### Generated Test Case:
```
:  = 104 intervals[i][0] = intervals[i][1] = 105. Title: Insert Interval = 105. Title: Insert Interval = 105. Title: Insert Interval = 105. Title: Insert Interval = 105. Title: Insert Interval = 105
```

## Problem Description:
Given a string `s` consists of some words separated by spaces, return the length of the last word in the string. If the last word does not exist, return `0`.

A word is a maximal substring consisting of non-space characters only.


Example 1:
Input: s = "Hello World"
Output: 5

Example 2:
Input: s = " "
Output: 0

Constraints:
`1 <= s.length <= 104`
`s` consists of only English letters and spaces `' '`.

### Generated Test Case:
```
: Given a string s consists of some words separated by spaces, return 0. A word is a maximal substring consisting of non-space characters only.
```

## Problem Description:
Given a positive integer `n`, generate an `n x n` `matrix` filled with elements from `1` to `n2` in spiral order.


Example 1:
Input: n = 3
Output: [[1,2,3],[8,9,4],[7,6,5]]

Example 2:
Input: n = 1
Output: [[1]]

Constraints:
`1 <= n <= 20`

### Generated Test Case:
```
n = 3 Output: [[1,2,3],[8,9,4],[7,6,5]] Example 2: Input: n = 1 Output: [[1]] Constraints: 1 = n = 20. Title: Spiral Matrix II Title: Spiral Matrix II Title: Spiral Matrix II Title: Spiral Matrix
```

## Problem Description:
The set `[1, 2, 3, ..., n]` contains a total of `n!` unique permutations.

By listing and labeling all of the permutations in order, we get the following sequence for `n = 3`:
`"123"`
`"132"`
`"213"`
`"231"`
`"312"`
`"321"`
Given `n` and `k`, return the `kth` permutation sequence.


Example 1:
Input: n = 3, k = 3
Output: "213"

Example 2:
Input: n = 4, k = 9
Output: "2314"

Example 3:
Input: n = 3, k = 1
Output: "123"

Constraints:
`1 <= n <= 9`
`1 <= k <= n!`

### Generated Test Case:
```
kth permutation sequence. kth permutation sequence. kth permutation sequence. kth kth kth permutation sequence. Title: Permutation Sequence. Title: Permutation Sequence.
```

## Problem Description:
Given the `head` of a linked list, rotate the list to the right by `k` places.


Example 1:
Input: head = [1,2,3,4,5], k = 2
Output: [4,5,1,2,3]

Example 2:
Input: head = [0,1,2], k = 4
Output: [2,0,1]

Constraints:
The number of nodes in the list is in the range `[0, 500]`.

`-100 <= Node.val <= 100`
`0 <= k <= 2 * 109`

### Generated Test Case:
```
: Given the head of a linked list, rotate the list to the right by k places. Example 1: Input: head = [1,2,3,4,5], k = 2 Output: [4,5,1,2,3] Example 2: Input: head = [0,1,2], k = 4 Output: [2,0,1] Constraints: The number of nodes in the list is in the range
```

## Problem Description:
A robot is located at the top-left corner of a `m x n` grid (marked 'Start' in the diagram below).

The robot can only move either down or right at any point in time. The robot is trying to reach the bottom-right corner of the grid (marked 'Finish' in the diagram below).

How many possible unique paths are there?

Example 1:
Input: m = 3, n = 7
Output: 28

Example 2:
Input: m = 3, n = 2
Output: 3
Explanation:
From the top-left corner, there are a total of 3 ways to reach the bottom-right corner:
1. Right -> Down -> Down
2. Down -> Down -> Right
3. Down -> Right -> Down

Example 3:
Input: m = 7, n = 3
Output: 28

Example 4:
Input: m = 3, n = 3
Output: 6

Constraints:
`1 <= m, n <= 100`
It's guaranteed that the answer will be less than or equal to `2 * 109`.

### Generated Test Case:
```
: A robot is located at the top-left corner of a m x n grid (marked 'Start' in the diagram below). The robot can only move either down or right at any point in time. The robot is trying to reach the bottom-right corner of the grid (marked 'Finish' in the diagram below). How many possible unique paths are there? Title: Unique Paths: Unique Paths:
```

## Problem Description:
A robot is located at the top-left corner of a `m x n` grid (marked 'Start' in the diagram below).

The robot can only move either down or right at any point in time. The robot is trying to reach the bottom-right corner of the grid (marked 'Finish' in the diagram below).

Now consider if some obstacles are added to the grids. How many unique paths would there be?
An obstacle and space is marked as `1` and `0` respectively in the grid.


Example 1:
Input: obstacleGrid = [[0,0,0],[0,1,0],[0,0,0]]
Output: 2
Explanation: There is one obstacle in the middle of the 3x3 grid above.

There are two ways to reach the bottom-right corner:
1. Right -> Right -> Down -> Down
2. Down -> Down -> Right -> Right

Example 2:
Input: obstacleGrid = [[0,1],[0,0]]
Output: 1

Constraints:
`m == obstacleGrid.length`
`n == obstacleGrid[i].length`
`1 <= m, n <= 100`
`obstacleGrid[i][j]` is `0` or `1`.

### Generated Test Case:
```
: A robot is located at the top-left corner of a m x n grid (marked 'Start' in the diagram below). The robot can only move either down or right at any point in time. The robot is trying to reach the bottom-right corner of the grid (marked 'Finish' in the diagram below). Now consider if some obstacles are added to the grids. How many unique paths would there be
```

## Problem Description:
Given a `m x n` `grid` filled with non-negative numbers, find a path from top left to bottom right, which minimizes the sum of all numbers along its path.

Note: You can only move either down or right at any point in time.


Example 1:
Input: grid = [[1,3,1],[1,5,1],[4,2,1]]
Output: 7
Explanation: Because the path 1 → 3 → 1 → 1 → 1 minimizes the sum.


Example 2:
Input: grid = [[1,2,3],[4,5,6]]
Output: 12

Constraints:
`m == grid.length`
`n == grid[i].length`
`1 <= m, n <= 200`
`0 <= grid[i][j] <= 100`

### Generated Test Case:
```
m x n grid filled with non-negative numbers, find a path from top left to bottom right, which minimizes the sum of all numbers along its path. Note: You can only move either down or right at any point in time. Title: Minimum Path Sum: Minimum Path Sum: Minimum Path Sum: Minimum Path Sum: Minimum Path Sum: Minimum Path Sum: Minimum Path Sum: Minimum Path Sum: Minimum Path Sum: Minimum
```

## Problem Description:
A valid number can be split up into these components (in order):
A decimal number or an integer.

(Optional) An `'e'` or `'E'`, followed by an integer.

A decimal number can be split up into these components (in order):
(Optional) A sign character (either `'+'` or `'-'`).

One of the following formats:
	
At least one digit, followed by a dot `'.'`.

At least one digit, followed by a dot `'.'`, followed by at least one digit.

A dot `'.'`, followed by at least one digit.

An integer can be split up into these components (in order):
(Optional) A sign character (either `'+'` or `'-'`).

At least one digit.

For example, all the following are valid numbers: `["2", "0089", "-0.1", "+3.14", "4.", "-.9", "2e10", "-90E3", "3e+7", "+6e-1", "53.5e93", "-123.456e789"]`, while the following are not valid numbers: `["abc", "1a", "1e", "e3", "99e2.5", "--6", "-+3", "95a54e53"]`.

Given a string `s`, return `true` if `s` is a valid number.


Example 1:
Input: s = "0"
Output: true

Example 2:
Input: s = "e"
Output: false

Example 3:
Input: s = "."
Output: false

Example 4:
Input: s = ".1"
Output: true

Constraints:
`1 <= s.length <= 20`
`s` consists of only English letters (both uppercase and lowercase), digits (`0-9`), plus `'+'`, minus `'-'`, or dot `'.'`.

### Generated Test Case:
```
: Input: s = "0" Output: false Example 2: Input: s = "e" Output: false Example 2: Input: s = ".1" Output: false Example 2: Input: s = ".1" Output: false Example 2: Input: s = ".1" Output: true Constraints: 1 = s.length
```

## Problem Description:
Given a non-empty array of decimal digits representing a non-negative integer, increment one to the integer.

The digits are stored such that the most significant digit is at the head of the list, and each element in the array contains a single digit.

You may assume the integer does not contain any leading zero, except the number 0 itself.


Example 1:
Input: digits = [1,2,3]
Output: [1,2,4]
Explanation: The array represents the integer 123.


Example 2:
Input: digits = [4,3,2,1]
Output: [4,3,2,2]
Explanation: The array represents the integer 4321.


Example 3:
Input: digits = [0]
Output: [1]

Constraints:
`1 <= digits.length <= 100`
`0 <= digits[i] <= 9`

### Generated Test Case:
```
: Given a non-empty array of decimal digits representing a non-negative integer, increment one to the integer. The array represents the integer 4321. Title: Plus One: Plus One: Plus One: Plus One: Plus One: Plus One: Plus One: Plus One: Plus One: Plus One: Plus One: Plus One: Plus One: Plus One: Plus One: Plus One: Plus One: Plus One: Plus One: Plus One
```

## Problem Description:
Given two binary strings `a` and `b`, return their sum as a binary string.


Example 1:
Input: a = "11", b = "1"
Output: "100"

Example 2:
Input: a = "1010", b = "1011"
Output: "10101"

Constraints:
`1 <= a.length, b.length <= 104`
`a` and `b` consist only of `'0'` or `'1'` characters.

Each string does not contain leading zeros except for the zero itself.

### Generated Test Case:
```
: a and b.: a and b.::: a and b, return their sum as binary string.: a = "11", b = "1" Output: "100" Example 2: Input: a = "1010", b = "1011" Output: "10101" Constrain
```

## Problem Description:
Given an array of words and a width maxWidth, format the text such that each line has exactly maxWidth characters and is fully (left and right) justified.

You should pack your words in a greedy approach; that is, pack as many words as you can in each line. Pad extra spaces `' '` when necessary so that each line has exactly maxWidth characters.

Extra spaces between words should be distributed as evenly as possible. If the number of spaces on a line do not divide evenly between words, the empty slots on the left will be assigned more spaces than the slots on the right.

For the last line of text, it should be left justified and no extra space is inserted between words.

Note:
A word is defined as a character sequence consisting of non-space characters only.

Each word's length is guaranteed to be greater than 0 and not exceed maxWidth.

The input array `words` contains at least one word.


Example 1:
Input: words = ["This", "is", "an", "example", "of", "text", "justification."], maxWidth = 16
Output:
[
   "This    is    an",
   "example  of text",
   "justification.  "
]

Example 2:
Input: words = ["What","must","be","acknowledgment","shall","be"], maxWidth = 16
Output:
[
  "What   must   be",
  "acknowledgment  ",
  "shall be        "
]
Explanation: Note that the last line is "shall be    " instead of "shall     be", because the last line must be left-justified instead of fully-justified.

Note that the second line is also left-justified becase it contains only one word.


Example 3:
Input: words = ["Science","is","what","we","understand","well","enough","to","explain","to","a","computer.","Art","is","everything","else","we","do"], maxWidth = 20
Output:
[
  "Science  is  what we",
  "understand      well",
  "enough to explain to",
  "a  computer.  Art is",
  "everything  else  we",
  "do                  "
]

Constraints:
`1 <= words.length <= 300`
`1 <= words[i].length <= 20`
`words[i]` consists of only English letters and symbols.

`1 <= maxWidth <= 100`
`words[i].length <= maxWidth`

### Generated Test Case:
```
,,, "justification." = 300 = words.length = 300 = words.length = 20 words[i] consists of only English letters and symbols. Title: Text Justification: Text Justification: Text Justification: Text Justification: Text Justification: Text Justification: Text Justification: Text Justification: Text Justification: Text Justification: Text Just
```

## Problem Description:
Given a non-negative integer `x`, compute and return the square root of `x`.

Since the return type is an integer, the decimal digits are truncated, and only the integer part of the result is returned.


Example 1:
Input: x = 4
Output: 2

Example 2:
Input: x = 8
Output: 2
Explanation: The square root of 8 is 2.82842..., and since the decimal part is truncated, 2 is returned.


Constraints:
`0 <= x <= 231 - 1`

### Generated Test Case:
```
: x = 4 Output: 2 Example 2: Input: x = 8 Output: 2 Explanation: The square root of 8 is 2.82842..., and since the decimal part is truncated, 2 is returned. Constraints: 0 = x = 231 - 1. Title: Sqrt(x)
```

## Problem Description:
You are climbing a staircase. It takes `n` steps to reach the top.

Each time you can either climb `1` or `2` steps. In how many distinct ways can you climb to the top?

Example 1:
Input: n = 2
Output: 2
Explanation: There are two ways to climb to the top.

1. 1 step + 1 step
2. 2 steps

Example 2:
Input: n = 3
Output: 3
Explanation: There are three ways to climb to the top.

1. 1 step + 1 step + 1 step
2. 1 step + 2 steps
3. 2 steps + 1 step

Constraints:
`1 <= n <= 45`

### Generated Test Case:
```
3 Output: 3 Explanation: There are three ways to climb to the top. 1. 1 step + 1 step 2. 2 steps Example 2: Input: n = 3 Output: 3 Explanation: There are three ways to climb to the top.
```

## Problem Description:
Given a string `path`, which is an absolute path (starting with a slash `'/'`) to a file or directory in a Unix-style file system, convert it to the simplified canonical path.

In a Unix-style file system, a period `'.'` refers to the current directory, a double period `'..'` refers to the directory up a level, and any multiple consecutive slashes (i.e. `'//'`) are treated as a single slash `'/'`. For this problem, any other format of periods such as `'...'` are treated as file/directory names.

The canonical path should have the following format:
The path starts with a single slash `'/'`.

Any two directories are separated by a single slash `'/'`.

The path does not end with a trailing `'/'`.

The path only contains the directories on the path from the root directory to the target file or directory (i.e., no period `'.'` or double period `'..'`)
Return the simplified canonical path.


Example 1:
Input: path = "/home/"
Output: "/home"
Explanation: Note that there is no trailing slash after the last directory name.


Example 2:
Input: path = "/../"
Output: "/"
Explanation: Going one level up from the root directory is a no-op, as the root level is the highest level you can go.


Example 3:
Input: path = "/home//foo/"
Output: "/home/foo"
Explanation: In the canonical path, multiple consecutive slashes are replaced by a single one.


Example 4:
Input: path = "/a/./b/../../c/"
Output: "/c"

Constraints:
`1 <= path.length <= 3000`
`path` consists of English letters, digits, period `'.'`, slash `'/'` or `'_'`.

`path` is a valid absolute Unix path.

### Generated Test Case:
```
: Input: path = "/home//foo/" Output: "/home" Explanation: Note that there is no trailing slash after the last directory name. Example 2: Input: path = "/home//foo/" Output: "/home" Explanation: Note that there is no trailing slash after the last directory name. path is a valid absolute
```

## Problem Description:
Given two strings `word1` and `word2`, return the minimum number of operations required to convert `word1` to `word2`.

You have the following three operations permitted on a word:
Insert a character
Delete a character
Replace a character

Example 1:
Input: word1 = "horse", word2 = "ros"
Output: 3
Explanation: 
horse -> rorse (replace 'h' with 'r')
rorse -> rose (remove 'r')
rose -> ros (remove 'e')

Example 2:
Input: word1 = "intention", word2 = "execution"
Output: 5
Explanation: 
intention -> inention (remove 't')
inention -> enention (replace 'i' with 'e')
enention -> exention (replace 'n' with 'x')
exention -> exection (replace 'n' with 'c')
exection -> execution (insert 'u')

Constraints:
`0 <= word1.length, word2.length <= 500`
`word1` and `word2` consist of lowercase English letters.

### Generated Test Case:
```
word2. word1 and word2.:: Input: word1 = "horse", word2 = "ros" Output: 3 Explanation: horse -> rorse (replace 'h' with 'r') rose (remove 'r') rose -> ros (remove 'e') Example 2: In
```

## Problem Description:
Given an `m x n` matrix. If an element is 0, set its entire row and column to 0. Do it in-place.

Follow up:
A straight forward solution using O(mn) space is probably a bad idea.

A simple improvement uses O(m + n) space, but still not the best solution.

Could you devise a constant space solution?

Example 1:
Input: matrix = [[1,1,1],[1,0,1],[1,1,1]]
Output: [[1,0,1],[0,0,0],[1,0,1]]

Example 2:
Input: matrix = [[0,1,2,0],[3,4,5,2],[1,3,1,5]]
Output: [[0,0,0,0],[0,4,5,0],[0,3,1,0]]

Constraints:
`m == matrix.length`
`n == matrix[0].length`
`1 <= m, n <= 200`
`-231 <= matrix[i][j] <= 231 - 1`

### Generated Test Case:
```
m == matrix.length n == matrix[0].length n == matrix[0].length n == matrix[0].length n == matrix[0].length n == matrix[0].length n == matrix[0].length n == matrix[0].length n == matrix[0].length
```

## Problem Description:
Write an efficient algorithm that searches for a value in an `m x n` matrix. This matrix has the following properties:
Integers in each row are sorted from left to right.

The first integer of each row is greater than the last integer of the previous row.


Example 1:
Input: matrix = [[1,3,5,7],[10,11,16,20],[23,30,34,60]], target = 3
Output: true

Example 2:
Input: matrix = [[1,3,5,7],[10,11,16,20],[23,30,34,60]], target = 13
Output: false

Constraints:
`m == matrix.length`
`n == matrix[i].length`
`1 <= m, n <= 100`
`-104 <= matrix[i][j], target <= 104`

### Generated Test Case:
```
: m == matrix.length n == matrix[i].length n == matrix[i].length n == matrix[i].length 1 = m, n = 100 -104 = matrix[i][j], target = 104. Title: Search a 2D Matrix. Title: Search a
```

## Problem Description:
Given an array `nums` with `n` objects colored red, white, or blue, sort them in-place so that objects of the same color are adjacent, with the colors in the order red, white, and blue.

We will use the integers `0`, `1`, and `2` to represent the color red, white, and blue, respectively.


Example 1:
Input: nums = [2,0,2,1,1,0]
Output: [0,0,1,1,2,2]

Example 2:
Input: nums = [2,0,1]
Output: [0,1,2]

Example 3:
Input: nums = [0]
Output: [0]

Example 4:
Input: nums = [1]
Output: [1]

Constraints:
`n == nums.length`
`1 <= n <= 300`
`nums[i]` is `0`, `1`, or `2`.

Follow up:
Could you solve this problem without using the library's sort function?
Could you come up with a one-pass algorithm using only `O(1)` constant space?

### Generated Test Case:
```
: Given an array nums with n objects colored red, white, or blue, sort them in-place so that objects of the same color are adjacent, with the colors in the order red, white, and blue. Title: Sort Colors: Sort Colors: Sort Colors: Sort Colors: Sort Colors: Sort Colors: Sort Colors: Sort Colors: Sort Colors: Sort Colors: Sort Colors:
```

## Problem Description:
Given two strings `s` and `t`, return the minimum window in `s` which will contain all the characters in `t`. If there is no such window in `s` that covers all characters in `t`, return the empty string `""`.

Note that If there is such a window, it is guaranteed that there will always be only one unique minimum window in `s`.


Example 1:
Input: s = "ADOBECODEBANC", t = "ABC"
Output: "BANC"

Example 2:
Input: s = "a", t = "a"
Output: "a"

Constraints:
`1 <= s.length, t.length <= 105`
`s` and `t` consist of English letters.

Follow up: Could you find an algorithm that runs in `O(n)` time?

### Generated Test Case:
```
: Given two strings s and t, return the minimum window in s which will contain all the characters in t. Note that If there is no such window in s that covers all characters in t, return the empty string "".
```

## Problem Description:
Given two integers `n` and `k`, return all possible combinations of `k` numbers out of the range `[1, n]`.

You may return the answer in any order.


Example 1:
Input: n = 4, k = 2
Output:
[
  [2,4],
  [3,4],
  [2,3],
  [1,2],
  [1,3],
  [1,4],
]

Example 2:
Input: n = 1, k = 1
Output: [[1]]

Constraints:
`1 <= n <= 20`
`1 <= k <= n`

### Generated Test Case:
```
: n = 4, k = 2 Output: [ [2,4], [3,4], [2,3], [1,2], [1,3], [1,4], [1,4], [1,4], [1,4], ] Example 2: Input: n = 1, k = 1 Output: [[1]] Constraints: 1 = n = 20 1 =
```

## Problem Description:
Given an integer array `nums` of unique elements, return all possible subsets (the power set).

The solution set must not contain duplicate subsets. Return the solution in any order.


Example 1:
Input: nums = [1,2,3]
Output: [[],[1],[2],[1,2],[3],[1,3],[2,3],[1,2,3]]

Example 2:
Input: nums = [0]
Output: [[],[0]]

Constraints:
`1 <= nums.length <= 10`
`-10 <= nums[i] <= 10`
All the numbers of `nums` are unique.

### Generated Test Case:
```
Given an integer array nums of unique elements, return all possible subsets (the power set). The solution set must not contain duplicate subsets. The solution set must not contain duplicate subsets.
```

## Problem Description:
Given an `m x n` grid of characters `board` and a string `word`, return `true` if `word` exists in the grid.

The word can be constructed from letters of sequentially adjacent cells, where adjacent cells are horizontally or vertically neighboring. The same letter cell may not be used more than once.


Example 1:
Input: board = [["A","B","C","E"],["S","F","C","S"],["A","D","E","E"]], word = "ABCCED"
Output: true

Example 2:
Input: board = [["A","B","C","E"],["S","F","C","S"],["A","D","E","E"]], word = "SEE"
Output: true

Example 3:
Input: board = [["A","B","C","E"],["S","F","C","S"],["A","D","E","E"]], word = "ABCB"
Output: false

Constraints:
`m == board.length`
`n = board[i].length`
`1 <= m, n <= 6`
`1 <= word.length <= 15`
`board` and `word` consists of only lowercase and uppercase English letters.

Follow up: Could you use search pruning to make your solution faster with a larger `board`?

### Generated Test Case:
```
board and a string word, return true if word exists in the grid. The word can be constructed from letters of sequentially adjacent cells, where adjacent cells are horizontal or vertical neighboring.
```

## Problem Description:
Given a sorted array nums, remove the duplicates in-place such that duplicates appeared at most twice and return the new length.

Do not allocate extra space for another array; you must do this by modifying the input array in-place with O(1) extra memory.

Clarification:
Confused why the returned value is an integer, but your answer is an array?
Note that the input array is passed in by reference, which means a modification to the input array will be known to the caller.

Internally you can think of this:
// nums is passed in by reference. (i.e., without making a copy)
int len = removeDuplicates(nums);
// any modification to nums in your function would be known by the caller.

// using the length returned by your function, it prints the first len elements.

for (int i = 0; i < len; i++) {
    print(nums[i]);
}

Example 1:
Input: nums = [1,1,1,2,2,3]
Output: 5, nums = [1,1,2,2,3]
Explanation: Your function should return length = `5`, with the first five elements of `nums` being `1, 1, 2, 2` and 3 respectively. It doesn't matter what you leave beyond the returned length.


Example 2:
Input: nums = [0,0,1,1,1,1,2,3,3]
Output: 7, nums = [0,0,1,1,2,3,3]
Explanation: Your function should return length = `7`, with the first seven elements of `nums` being modified to `0`, 0, 1, 1, 2, 3 and 3 respectively. It doesn't matter what values are set beyond the returned length.


Constraints:
`1 <= nums.length <= 3 * 104`
`-104 <= nums[i] <= 104`
`nums` is sorted in ascending order.

### Generated Test Case:
```
nums, remove the duplicates in-place so that duplicates appeared at most twice and return the new length. It doesn't matter what you leave beyond the returned length. Title: Remove Duplicates from Sorted Array II. Title: Remove Duplicates from Sorted Array II. Title: Remove Duplicates from Sorted Array II. Title: Remove Duplicates from Sorted Array II. Title:
```

## Problem Description:
There is an integer array `nums` sorted in non-decreasing order (not necessarily with distinct values).

Before being passed to your function, `nums` is rotated at an unknown pivot index `k` (`0 <= k < nums.length`) such that the resulting array is `[nums[k], nums[k+1], ..., nums[n-1], nums[0], nums[1], ..., nums[k-1]]` (0-indexed). For example, `[0,1,2,4,4,4,5,6,6,7]` might be rotated at pivot index `5` and become `[4,5,6,6,7,0,1,2,4,4]`.

Given the array `nums` after the rotation and an integer `target`, return `true` if `target` is in `nums`, or `false` if it is not in `nums`.


Example 1:
Input: nums = [2,5,6,0,0,1,2], target = 0
Output: true

Example 2:
Input: nums = [2,5,6,0,0,1,2], target = 3
Output: false

Constraints:
`1 <= nums.length <= 5000`
`-104 <= nums[i] <= 104`
`nums` is guaranteed to be rotated at some pivot.

`-104 <= target <= 104`
Follow up: This problem is the same as Search in Rotated Sorted Array, where `nums` may contain duplicates. Would this affect the runtime complexity? How and why?

### Generated Test Case:
```
nums is rotated at pivot index 5 (0 = k  nums.length) so that the array is [nums[k], nums[k+1],..., nums[n-1], nums[1],..., nums[k-1]]] (0-indexed). This problem is similar to Search in Rotated Sorted
```

## Problem Description:
Given the `head` of a sorted linked list, delete all nodes that have duplicate numbers, leaving only distinct numbers from the original list. Return the linked list sorted as well.


Example 1:
Input: head = [1,2,3,3,4,4,5]
Output: [1,2,5]

Example 2:
Input: head = [1,1,1,2,3]
Output: [2,3]

Constraints:
The number of nodes in the list is in the range `[0, 300]`.

`-100 <= Node.val <= 100`
The list is guaranteed to be sorted in ascending order.

### Generated Test Case:
```
: Given the head of a sorted linked list, delete all nodes that have duplicate numbers, leaving only distinct numbers from the original list. Return the linked list sorted as well. Title: Remove Duplicates from Sorted List II Title: Remove Duplicates from Sorted List II Title: Remove Duplicates from Sorted List II Title: Remove Duplicates from Sorted List II. Title: Remove Duplicates
```

## Problem Description:
Given the `head` of a sorted linked list, delete all duplicates such that each element appears only once. Return the linked list sorted as well.


Example 1:
Input: head = [1,1,2]
Output: [1,2]

Example 2:
Input: head = [1,1,2,3,3]
Output: [1,2,3]

Constraints:
The number of nodes in the list is in the range `[0, 300]`.

`-100 <= Node.val <= 100`
The list is guaranteed to be sorted in ascending order.

### Generated Test Case:
```
: Given the head of a sorted linked list, delete all duplicates such that each element appears only once. Return the linked list sorted as well. Title: Remove Duplicates from Sorted List. Title: Remove Duplicates from Sorted List.
```

## Problem Description:
Given an array of integers `heights` representing the histogram's bar height where the width of each bar is `1`, return the area of the largest rectangle in the histogram.


Example 1:
Input: heights = [2,1,5,6,2,3]
Output: 10
Explanation: The above is a histogram where width of each bar is 1.

The largest rectangle is shown in the red area, which has an area = 10 units.


Example 2:
Input: heights = [2,4]
Output: 4

Constraints:
`1 <= heights.length <= 105`
`0 <= heights[i] <= 104`

### Generated Test Case:
```
: 1 = heights.length = 105 0 = heights[i] = 104. Title: Largest Rectangle in Histogram. Title: Largest Rectangle in Histogram.
```

## Problem Description:
Given a `rows x cols` binary `matrix` filled with `0`'s and `1`'s, find the largest rectangle containing only `1`'s and return its area.


Example 1:
Input: matrix = [["1","0","1","0","0"],["1","0","1","1","1"],["1","1","1","1","1"],["1","0","0","1","0"]]
Output: 6
Explanation: The maximal rectangle is shown in the above picture.


Example 2:
Input: matrix = []
Output: 0

Example 3:
Input: matrix = [["0"]]
Output: 0

Example 4:
Input: matrix = [["1"]]
Output: 1

Example 5:
Input: matrix = [["0","0"]]
Output: 0

Constraints:
`rows == matrix.length`
`cols == matrix[i].length`
`0 <= row, cols <= 200`
`matrix[i][j]` is `'0'` or `'1'`.

### Generated Test Case:
```
: rows == matrix.length cols == row, cols = 200 matrix[i][j] is '0' or '1'. Title: Maximal Rectangle: Maximal Rectangle: Maximal Rectangle: Maximal Rectangle: Maximal Rectangle: Maximal Rectangle: Maximal Rectangle: Maxi
```

## Problem Description:
Given the `head` of a linked list and a value `x`, partition it such that all nodes less than `x` come before nodes greater than or equal to `x`.

You should preserve the original relative order of the nodes in each of the two partitions.


Example 1:
Input: head = [1,4,3,2,5,2], x = 3
Output: [1,2,2,4,3,5]

Example 2:
Input: head = [2,1], x = 2
Output: [1,2]

Constraints:
The number of nodes in the list is in the range `[0, 200]`.

`-100 <= Node.val <= 100`
`-200 <= x <= 200`

### Generated Test Case:
```
: Given the head of a linked list and a value x, partition it so that all nodes less than x come before nodes greater than or equal to x. Title: Partition List: Partition List: Partition List: Partition List: Partition List: Partition List: Partition List: Partition List: Partition List: Partition List: Partition List: Partition List:
```

## Problem Description:
We can scramble a string s to get a string t using the following algorithm:
If the length of the string is 1, stop.

If the length of the string is > 1, do the following:
	
Split the string into two non-empty substrings at a random index, i.e., if the string is `s`, divide it to `x` and `y` where `s = x + y`.

Randomly decide to swap the two substrings or to keep them in the same order. i.e., after this step, `s` may become `s = x + y` or `s = y + x`.

Apply step 1 recursively on each of the two substrings `x` and `y`.

Given two strings `s1` and `s2` of the same length, return `true` if `s2` is a scrambled string of `s1`, otherwise, return `false`.


Example 1:
Input: s1 = "great", s2 = "rgeat"
Output: true
Explanation: One possible scenario applied on s1 is:
"great" --> "gr/eat" // divide at random index.

"gr/eat" --> "gr/eat" // random decision is not to swap the two substrings and keep them in order.

"gr/eat" --> "g/r / e/at" // apply the same algorithm recursively on both substrings. divide at ranom index each of them.

"g/r / e/at" --> "r/g / e/at" // random decision was to swap the first substring and to keep the second substring in the same order.

"r/g / e/at" --> "r/g / e/ a/t" // again apply the algorithm recursively, divide "at" to "a/t".

"r/g / e/ a/t" --> "r/g / e/ a/t" // random decision is to keep both substrings in the same order.

The algorithm stops now and the result string is "rgeat" which is s2.

As there is one possible scenario that led s1 to be scrambled to s2, we return true.


Example 2:
Input: s1 = "abcde", s2 = "caebd"
Output: false

Example 3:
Input: s1 = "a", s2 = "a"
Output: true

Constraints:
`s1.length == s2.length`
`1 <= s1.length <= 30`
`s1` and `s2` consist of lower-case English letters.

### Generated Test Case:
```
a string s to get a string t using the following algorithm: If the length of the string is 1, stop. If the length of the string is > 1, stop. If the length of the string is > 1, stop. If the length of the string is > 1, divide it into two non-empty substrings at a random index, i.e., if the string is s, divide it to x
```

## Problem Description:
Given two sorted integer arrays `nums1` and `nums2`, merge `nums2` into `nums1` as one sorted array.

The number of elements initialized in `nums1` and `nums2` are `m` and `n` respectively. You may assume that `nums1` has a size equal to `m + n` such that it has enough space to hold additional elements from `nums2`.


Example 1:
Input: nums1 = [1,2,3,0,0,0], m = 3, nums2 = [2,5,6], n = 3
Output: [1,2,2,3,5,6]

Example 2:
Input: nums1 = [1], m = 1, nums2 = [], n = 0
Output: [1]

Constraints:
`nums1.length == m + n`
`nums2.length == n`
`0 <= m, n <= 200`
`1 <= m + n <= 200`
`-109 <= nums1[i], nums2[i] <= 109`

### Generated Test Case:
```
nums1 and nums2, merge nums2 into nums1 as one sorted array. The number of elements initialized in nums1 and nums2 are m + n respectively. You may assume that nums1 has a size equal to m + n such that it has enough space to hold additional elements from
```

## Problem Description:
The gray code is a binary numeral system where two successive values differ in only one bit.

Given an integer `n` representing the total number of bits in the code, return any sequence of gray code.

A gray code sequence must begin with `0`.


Example 1:
Input: n = 2
Output: [0,1,3,2]
Explanation:
00 - 0
01 - 1
11 - 3
10 - 2
[0,2,3,1] is also a valid gray code sequence.

00 - 0
10 - 2
11 - 3
01 - 1

Example 2:
Input: n = 1
Output: [0,1]

Constraints:
`1 <= n <= 16`

### Generated Test Case:
```
: The gray code is a binary numeral system where two successive values differ in only one bit. The gray code is a binary numeral system where two successive values differ in only one bit. The gray code is a binary numeral system where two successive values differ in only one bit.
```

## Problem Description:
Given an integer array `nums` that may contain duplicates, return all possible subsets (the power set).

The solution set must not contain duplicate subsets. Return the solution in any order.


Example 1:
Input: nums = [1,2,2]
Output: [[],[1],[1,2],[1,2,2],[2],[2,2]]

Example 2:
Input: nums = [0]
Output: [[],[0]]

Constraints:
`1 <= nums.length <= 10`
`-10 <= nums[i] <= 10`

### Generated Test Case:
```
: Given an integer array nums that may contain duplicate subsets, return all possible subsets (the power set). The solution set must not contain duplicate subsets.length = 10 -10 = nums[i] = 10. Title: Subsets II.
```

## Problem Description:
A message containing letters from `A-Z` can be encoded into numbers using the following mapping:
'A' -> "1"
'B' -> "2"
...

'Z' -> "26"
To decode an encoded message, all the digits must be grouped then mapped back into letters using the reverse of the mapping above (there may be multiple ways). For example, `"11106"` can be mapped into:
`"AAJF"` with the grouping `(1 1 10 6)`
`"KJF"` with the grouping `(11 10 6)`
Note that the grouping `(1 11 06)` is invalid because `"06"` cannot be mapped into `'F'` since `"6"` is different from `"06"`.

Given a string `s` containing only digits, return the number of ways to decode it.

The answer is guaranteed to fit in a 32-bit integer.


Example 1:
Input: s = "12"
Output: 2
Explanation: "12" could be decoded as "AB" (1 2) or "L" (12).


Example 2:
Input: s = "226"
Output: 3
Explanation: "226" could be decoded as "BZ" (2 26), "VF" (22 6), or "BBF" (2 2 6).


Example 3:
Input: s = "0"
Output: 0
Explanation: There is no character that is mapped to a number starting with 0.

The only valid mappings with 0 are 'J' -> "10" and 'T' -> "20", neither of which start with 0.

Hence, there are no valid ways to decode this since all digits need to be mapped.


Example 4:
Input: s = "06"
Output: 0
Explanation: "06" cannot be mapped to "F" because of the leading zero ("6" is different from "06").


Constraints:
`1 <= s.length <= 100`
`s` contains only digits and may contain leading zero(s).

### Generated Test Case:
```
: "06" Output: 0 Explanation: "06" cannot be mapped to "F" because of the leading zero ("6" is different from "06"). Constraints: 1 = s.length = 100 s contains only digits and may contain leading zero(s). Title: Decode Ways: Decode Ways: Decode Ways: Decode Ways:
```

## Problem Description:
Given the `head` of a singly linked list and two integers `left` and `right` where `left <= right`, reverse the nodes of the list from position `left` to position `right`, and return the reversed list.


Example 1:
Input: head = [1,2,3,4,5], left = 2, right = 4
Output: [1,4,3,2,5]

Example 2:
Input: head = [5], left = 1, right = 1
Output: [5]

Constraints:
The number of nodes in the list is `n`.

`1 <= n <= 500`
`-500 <= Node.val <= 500`
`1 <= left <= right <= n`
Follow up: Could you do it in one pass?

### Generated Test Case:
```
: a singly linked list and two integers left and right where left = right, reverse the nodes of the list from position left to position right, and return the reversed list.
```

## Problem Description:
Given a string `s` containing only digits, return all possible valid IP addresses that can be obtained from `s`. You can return them in any order.

A valid IP address consists of exactly four integers, each integer is between `0` and `255`, separated by single dots and cannot have leading zeros. For example, "0.1.2.201" and "192.168.1.1" are valid IP addresses and "0.011.255.245", "192.168.1.312" and "192.168@1.1" are invalid IP addresses. 

Example 1:
Input: s = "25525511135"
Output: ["255.255.11.135","255.255.111.35"]

Example 2:
Input: s = "0000"
Output: ["0.0.0.0"]

Example 3:
Input: s = "1111"
Output: ["1.1.1.1"]

Example 4:
Input: s = "010010"
Output: ["0.10.0.10","0.100.1.0"]

Example 5:
Input: s = "101023"
Output: ["1.0.10.23","1.0.102.3","10.1.0.23","10.10.2.3","101.0.2.3"]

Constraints:
`0 <= s.length <= 3000`
`s` consists of digits only.

### Generated Test Case:
```
: Given a string s containing only digits, return all possible valid IP addresses that can be obtained from s. You can return them in any order. A valid IP address consists of exactly four integers, each integer is between 0 and 255, separated by single dots and cannot have leading zeros. For example, "0.1.2.201" and "192.168.1.1" are valid IP addresses
```

## Problem Description:
Given the `root` of a binary tree, return the inorder traversal of its nodes' values.


Example 1:
Input: root = [1,null,2,3]
Output: [1,3,2]

Example 2:
Input: root = []
Output: []

Example 3:
Input: root = [1]
Output: [1]

Example 4:
Input: root = [1,2]
Output: [2,1]

Example 5:
Input: root = [1,null,2]
Output: [1,2]

Constraints:
The number of nodes in the tree is in the range `[0, 100]`.

`-100 <= Node.val <= 100`
Follow up:
Recursive solution is trivial, could you do it iteratively?

### Generated Test Case:
```
: Given the root of a binary tree, return the inorder traversal of its nodes' values. Example 1: Input: root = [1,null,2,3] Output: [1,3,2] Example 2: Input: root = [1] Output: [1] Example 4: Input: root = [1,2] Output: [2,1] Example 5: Input: root = [1,2
```

## Problem Description:
Given an integer `n`, return all the structurally unique BST's (binary search trees), which has exactly `n` nodes of unique values from `1` to `n`. Return the answer in any order.


Example 1:
Input: n = 3
Output: [[1,null,2,null,3],[1,null,3,2],[2,1,3],[3,1,null,null,2],[3,2,null,1]]

Example 2:
Input: n = 1
Output: [[1]]

Constraints:
`1 <= n <= 8`

### Generated Test Case:
```
n = 8. Title: Unique Binary Search Trees II Title: Unique Binary Search Trees II Title: Unique Binary Search Trees II Title: Unique Binary Search Trees II Title: Unique Binary Search Trees II Title: Unique Binary Search Trees II Title: Unique Binary Search Trees II Title: Unique Binary Search Trees II Title: Unique Binary Search Trees II Title: Unique Binary Search Trees II Title: Unique Binary Search Trees II Title:
```

## Problem Description:
Given an integer `n`, return the number of structurally unique BST's (binary search trees) which has exactly `n` nodes of unique values from `1` to `n`.


Example 1:
Input: n = 3
Output: 5

Example 2:
Input: n = 1
Output: 1

Constraints:
`1 <= n <= 19`

### Generated Test Case:
```
: Given an integer n, return the number of structurally unique BST's (binary search trees) which has exactly n nodes of unique values from 1 to n. Title: Unique Binary Search Trees (binary search trees) which has exactly n nodes of unique values from 1 to n. Title: Unique Binary Search Trees (binary search trees)
```

## Problem Description:
Given strings `s1`, `s2`, and `s3`, find whether `s3` is formed by an interleaving of `s1` and `s2`.

An interleaving of two strings `s` and `t` is a configuration where they are divided into non-empty substrings such that:
`s = s1 + s2 + ... + sn`
`t = t1 + t2 + ... + tm`
`|n - m| <= 1`
The interleaving is `s1 + t1 + s2 + t2 + s3 + t3 + ...` or `t1 + s1 + t2 + s2 + t3 + s3 + ...`
Note: `a + b` is the concatenation of strings `a` and `b`.


Example 1:
Input: s1 = "aabcc", s2 = "dbbca", s3 = "aadbbcbcac"
Output: true

Example 2:
Input: s1 = "aabcc", s2 = "dbbca", s3 = "aadbbbaccc"
Output: false

Example 3:
Input: s1 = "", s2 = "", s3 = ""
Output: true

Constraints:
`0 <= s1.length, s2.length <= 100`
`0 <= s3.length <= 200`
`s1`, `s2`, and `s3` consist of lowercase English letters.

Follow up: Could you solve it using only `O(s2.length)` additional memory space?

### Generated Test Case:
```
s1 + s2 +... + sn t = t1 + t2 + s3 + t3 +... + tm |n - m| = 1 The interleaving is s1 + t1 + s2 + s3 + t3 +... or t1 + s2 +
```

## Problem Description:
Given the `root` of a binary tree, determine if it is a valid binary search tree (BST).

A valid BST is defined as follows:
The left subtree of a node contains only nodes with keys less than the node's key.

The right subtree of a node contains only nodes with keys greater than the node's key.

Both the left and right subtrees must also be binary search trees.


Example 1:
Input: root = [2,1,3]
Output: true

Example 2:
Input: root = [5,1,4,null,null,3,6]
Output: false
Explanation: The root node's value is 5 but its right child's value is 4.


Constraints:
The number of nodes in the tree is in the range `[1, 104]`.

`-231 <= Node.val <= 231 - 1`

### Generated Test Case:
```
:: root = [2,1,3] Output: true Example 2: Input: root = [5,1,4,null,null,3,6] Output: false Explanation: The root node's value is 5 but its right child's value is 4. Constraints: The number of nodes in the tree is in the range [1, 104]. -231 = Node
```

## Problem Description:
You are given the `root` of a binary search tree (BST), where exactly two nodes of the tree were swapped by mistake. Recover the tree without changing its structure.

Follow up: A solution using `O(n)` space is pretty straight forward. Could you devise a constant space solution?

Example 1:
Input: root = [1,3,null,null,2]
Output: [3,1,null,null,2]
Explanation: 3 cannot be a left child of 1 because 3 > 1. Swapping 1 and 3 makes the BST valid.


Example 2:
Input: root = [3,1,4,null,null,2]
Output: [2,1,4,null,null,3]
Explanation: 2 cannot be in the right subtree of 3 because 2 < 3. Swapping 2 and 3 makes the BST valid.


Constraints:
The number of nodes in the tree is in the range `[2, 1000]`.

`-231 <= Node.val <= 231 - 1`

### Generated Test Case:
```
: You are given the root of a binary search tree (BST) where exactly two nodes of the tree were swapped by mistake. Swapping 2 and 3 makes the BST valid. Constraints: The number of nodes in the tree is in the range [2, 1000].
```

## Problem Description:
Given the roots of two binary trees `p` and `q`, write a function to check if they are the same or not.

Two binary trees are considered the same if they are structurally identical, and the nodes have the same value.


Example 1:
Input: p = [1,2,3], q = [1,2,3]
Output: true

Example 2:
Input: p = [1,2], q = [1,null,2]
Output: false

Example 3:
Input: p = [1,2,1], q = [1,1,2]
Output: false

Constraints:
The number of nodes in both trees is in the range `[0, 100]`.

`-104 <= Node.val <= 104`

### Generated Test Case:
```
1: Input: p = [1,2,3], q = [1,2,3] Output: true Example 2: Input: p = [1,2,3], q = [1,2,3] Output: true Example 2: Input: p = [1,2,3], q = [1,null,2] Output: false Example 3: Input: p = [1,2,1], q = [
```

