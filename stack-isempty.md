---
title: bool IsEmpty()
parent: Public Methods
grand_parent: Stack&lt;T&gt;
layout: page
---

# `bool IsEmpty()`

### Returns wether or not the stack is empty.

## Exceptions:
- None.

## Example:

```cs
Stack<int> a = new Stack<int>();
Console.WriteLine(a.IsEmpty()); // True
a.Push(5);
Console.WriteLine(a.IsEmpty()); // False
```