---
  title: "R basics"
  description: ""
---

## using R as a calculator

```yaml
type: NormalExercise 
lang: r
xp: 100 
skills: 1
key: adebd63aff   
```


At the most basic level, R can be used just like a calculator.  All manner of mathematical operations are possible.


`@instructions`
- Run the code in the script window on the right by clicking the "Submit Answer" button 
- Ctrl + Shift + Enter also works

- Inspect the resulting output in the console window in the bottom-right

`@hint`
- Here is the hint for this setup problem. 
- It should get students 50% of the way to the correct answer.
- So don't provide the answer, but don't just reiterate the instructions.
- Typically one hint per instruction is a sensible amount.

`@pre_exercise_code`

```{r}
# Load datasets and packages here.
```

`@sample_code`

```{r}
# Addition, subtraction, multiplication, and division
5 + 5

3 - 7

4 * 0.5

6 / 4

# Exponentiation
3 ^ 3

# R obeys order of operations
(-7)^2 + 4 - 6 * 2 + -2^3
```

`@solution`

```{r}
# Addition, subtraction, multiplication, and division
5 + 5

3 - 7

4 * 0.5

6 / 4

# Exponentiation
3 ^ 3

# R obeys order of operations
(-7)^2 + 4 - 6 * 2 + -2^3
```

`@sct`

```{r}
keepoff <- "Don't mess with the code that is already here"
test_student_typed("# Addition, subtraction, multiplication, and division", incorrect_msg = keepoff)
test_output_contains("5 + 5", incorrect_msg = keepoff)
test_output_contains("3 - 7", incorrect_msg = keepoff)
test_output_contains("4 * 0.5", incorrect_msg = keepoff)
test_output_contains("6 / 4", incorrect_msg = keepoff)
test_student_typed("# Exponentiation")
test_output_contains("3 ^ 3")
test_student_typed("# R obeys order of operations")
test_output_contains("(-7)^2 + 4 - 6 * 2 + -2^3")
success_msg("Congratulations! A journey of a thousand lines of code begins with a single step (or command?)")
```
