# sqrtx-binary-search
# 🔢 Sqrt(x) using Binary Search

This project provides an efficient solution to compute the **square root of a non-negative integer** using the **Binary Search algorithm**.

---

## 🚀 Problem Statement

Given a non-negative integer `x`, compute and return the **square root of x**.

- The result should be **rounded down** to the nearest integer.
- Do **not use built-in functions** like `sqrt()` or `pow()`.

---

## 🧠 Approach

We use **Binary Search** to efficiently find the square root:

1. Search range: `1` to `x`
2. Find middle element `mid`
3. Compare:
   - If `mid * mid == x` → return `mid`
   - If `mid * mid < x` → move right and store answer
   - If `mid * mid > x` → move left
4. Return the stored answer (floor value)


        return ans;
    }
};
