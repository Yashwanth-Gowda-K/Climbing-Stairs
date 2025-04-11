 Climbing Stairs

## Problem Statement

You are climbing a staircase. It takes `n` steps to reach the top.  
Each time you can either climb **1 or 2 steps**.  
In how many distinct ways can you climb to the top?

---

## 🧠 Intuition

This is a classic **Dynamic Programming** problem.  
To reach step `n`, you can:
- Take 1 step from step `n-1`
- OR take 2 steps from step `n-2`

So the total number of ways to reach step `n` is:
ways(n) = ways(n-1) + ways(n-2)
