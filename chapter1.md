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
# Answer goes here
# Make sure to match the comments with your sample code
# to help students see the differences from solution
# to given.
```

`@sct`

```{r}
# Update this to something more informative.
success_msg("Some praise! Then reinforce a learning objective from the exercise.")
```
