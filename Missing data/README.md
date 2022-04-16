# Missing Data
- NA - missing value
- NULL - absence of anything

<details>
    <summary>NA</summary>

```
> x <- c(1, 2, NA, 3, NA, 4); x
[1]  1  2 NA  3 NA  4
> is.na(x)
[1] FALSE FALSE  TRUE FALSE  TRUE FALSE
> sum(x)
[1] NA
```

Sum of the vector elements excluding NA values
```
> sum(x, na.rm = TRUE)
[1] 10
```
</details>

<details>
    <summary>NULL</summary>

```
> y <- c(1, NULL, 2); y
[1] 1 2
> is.null(y)
[1] FALSE
> length(y)
[1] 2
```

</details>

<details>
    <summary>NaN, Inf</summary>

NaN and Inf values arise from arithmetic operations that are not defined
```
> 0/0
[1] NaN
> 1/0
[1] Inf
```
