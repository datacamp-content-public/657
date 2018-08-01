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
- If you keep getting an error message click the reset button and try submitting again

`@pre_exercise_code`

```{r}

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
ex() %>% check_code(regex = "# Addition, subtraction, multiplication, and division", missing_msg = keepoff, append = TRUE)
ex() %>% check_code(regex = "# Exponentiation", missing_msg = keepoff, append = TRUE)
ex() %>% check_code(regex = "# R obeys order of operations", missing_msg = keepoff, append = TRUE)
ex() %>% check_output(5+5, missing_msg = keepoff, append = TRUE)
ex() %>% check_output(3-7, missing_msg = keepoff, append = TRUE)
ex() %>% check_output(4*.5, missing_msg = keepoff, append = TRUE)
ex() %>% check_output(6/4, missing_msg = keepoff, append = TRUE)
ex() %>% check_output(3^3, missing_msg = keepoff, append = TRUE)
ex() %>% check_output((-7)^2+4-6*2+-2^3, missing_msg = keepoff, append = TRUE)
success_msg("Congratulations! A journey of a thousand lines of code begins with a single step (or command?)")
```
