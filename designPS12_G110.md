# Assignment 2 – PS02 - Product Rating 
## Summary of Problem statement

We have to write the total minimum price value for the given products. Initially started with Brute Force Approach i.e. Feasible solution and iteratively progressed to optimal solution and it is the only possible optimal solution

### Details on the code
🔦 Input file : `inputPS12.txt`
💻 SourceCode files : `ProductRating.py`
💻 To run the code: `python3 ProductRating.py`
💡 output file(generated) : `outputPS12.txt`

### Time Complexity
|  🚶 Feasible solution | 🚆 Greedy iteration1 solution  | ✈️ Greedy optimal solution |
|---|---|---|
| `3n`  | `2n`   | `n log n`  |

## 📶 Feasible solution Logic
Space Complexity: `3n`
> left2right list ==> Start from left index and calculate price of each rating by comparing its adjacement element
> right2left list ==> Start from right index and calculate price of each rating by comparing its adjacement element
> Sum(max(left2right[left], right2left[left]))


## ✈️ Optimal solution Logic (Greedy Technique)
Space Complexity: `3n
Two pointer approach and navigate list at each iteration from both sides
> left2right list ==> Start from left index and calculate price of each rating by comparing its adjacement element
> right2left list ==> Start from right index and calculate price of each rating by comparing its adjacement element
> When we are at midpoint of the list start computing max and response
> navigate through 1: midpoint and sumation of price
