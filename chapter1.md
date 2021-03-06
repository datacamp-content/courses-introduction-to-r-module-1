---
title: 'Basic Coding'
description: "1. R Arithmetic\n2. R objects\n3. R packages\n4. Importing/exporting data sets"
free_preview: true
---

## Example coding exercise

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

In the editor on the right you should type R code to solve the exercises. When you hit the 'Submit Answer' button, every line of code is interpreted and executed by R and you get a message whether or not your code was correct. The output of your R code is shown in the console in the lower right corner.

R makes use of the # sign to add comments, so that you and others can understand what the R code is about. Just like Twitter! Comments are not run as R code, so they will not influence your result. For example, Calculate 3 + 4 in the editor on the right is a comment.

You can also execute R commands straight in the console. This is a good way to experiment with R code, as your submission is not checked for correctness.

`@instructions`
In the editor on the right there is already some sample code. Can you see which lines are actual R code and which are comments?
Add a line of code that calculates the sum of 6 and 12, and hit the 'Submit Answer' button.

`@hint`
Type 2 + 2 in the editor in the top right.  Then select run code to ensure the answer is 4 and your syntax is correct.

`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}
# Calculate 3 + 4
3 + 4

# Calculate 6 + 12
6+12
```

`@solution`
```{r}
18
```

`@sct`
```{r}
ex() %>% check_expr("6+12") %>% check_result() %>% check_equal()
success_msg("Good Job!")
```
