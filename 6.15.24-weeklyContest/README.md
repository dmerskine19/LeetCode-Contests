# LeetCode Competition Solutions

## Overview

LeetCode Weekly Contest 401 - 6/15/2024

## Problems

1. **Problem 1:** [Problem Title 1](#problem-1-title)
2. **Problem 2:** [Problem Title 2](#problem-2-title)
3. **Problem 3:** [Problem Title 3](#problem-3-title)

---

### Problem 1: Count Pairs That Form a Complete Day I

_Given an integer array hours representing times in hours, return an integer denoting the number of pairs i, j where i < j and hours[i] + hours[j] forms a complete day._

_A complete day is defined as a time duration that is an exact multiple of 24 hours. - 1 day is 24 hours, 2 days is 48 hours, 3 days is 72 hours._

<u>Example 1:</u>

```
Input: hours = [12,12,30,24,24]
Output: 2
```

```
Explanation:
The pairs of indices that form a complete day are (0, 1) and (3, 4).
```

<u>Example 2:</u>

```
Input: hours = [72,48,24,3]
Output: 3
```

```
The pairs of indices that form a complete day are (0, 1), (0, 2), and (1, 2).
```

```
Constraints:

1 <= hours.length <= 100
1 <= hours[i] <= 109
```

#### Solution

`src/main/java/com/example/solutions/Solution1.java`

---

### Problem 2: Count Pairs That Form a Complete Day II

_Given an integer array hours representing times in hours, return an integer denoting the number of pairs i, j where i < j and hours[i] + hours[j] forms a complete day._

_A complete day is defined as a time duration that is an exact multiple of 24 hours. - 1 day is 24 hours, 2 days is 48 hours, 3 days is 72 hours_

<u>Example 1:</u>

```
Input: hours = [12,12,30,24,24]
Output: 2
```

```
Explanation: The pairs of indices that form a complete day are (0, 1) and (3, 4).
```

<u>Example 2:</u>

```
Input: hours = [72,48,24,3]
Output: 3
```

`Explanation: The pairs of indices that form a complete day are (0, 1), (0, 2), and (1, 2).`

```
Constraints:

1 <= hours.length <= 5 * 105
1 <= hours[i] <= 109
```

#### Solution

`src/main/java/com/example/solutions/Solution2.java`

---

### Problem 3: Maximum Total Damage With Spell Casting

\*A magician has various spells.

You are given an array power, where each element represents the damage of a spell. Multiple spells can have the same damage value.

It is a known fact that if a magician decides to cast a spell with a damage of power[i], they cannot cast any spell with a damage of power[i] - 2, power[i] - 1, power[i] + 1, or power[i] + 2.

Each spell can be cast only once.\*

_Return the maximum possible total damage that a magician can cast._

<u>Example 1:</u>

```Input: power = [1,1,3,4]
Output: 6
```

`Explanation: The maximum possible damage of 6 is produced by casting spells 0, 1, 3 with damage 1, 1, 4.`

<u>Example 2:</u>

```
Input: power = [7,1,6,6]
Output: 13
```

`Explanation: The maximum possible damage of 13 is produced by casting spells 1, 2, 3 with damage 1, 6, 6.`

```Constraints:

1 <= power.length <= 105
1 <= power[i] <= 109
```

#### Solution

`src/main/java/com/example/solutions/Solution3.java`

---