```
add_numbers <- function(a, b) {
  result <- a + b
  return(result)
}
```
### Call it
add_numbers(3, 5)
### Output: 8
Or
```
add_numbers <- function(a, b) a + b
```
We don’t always need to write return(), R automatically returns the last evaluated expression in a function.
