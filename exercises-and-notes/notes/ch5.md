# Strictness and laziness

`non-strictness` aka `laziness`

## 5.1 Strict and non-strict functions

zero arg function

`thunk`

`lazy` keyword


## 5.2 An extended example: lazy lists

`lazy lists` or `streams`

### 5.2.1 Memoizing streams and avoiding re-computation

assign thunk to lazy val and use lazy val so it only gets evaluated once

### 5.2.2 Helper functions for inspecting streams

## 5.3 Separating program description from evaluation

`separation of concerns`

separate the `description of computations` from `actually running them`

`incremental` nature

## 5.4 Infinite streams and co-recursion

`infinite streams`

careful on `stack-safe` or `never terminate`


scanRight can not use unfold because it has no concept of intermediate result on interface?

## 5.5 Summary

efficiency with FP

improve modularity by separating the description of an expression from the how-and-when of its evaluation