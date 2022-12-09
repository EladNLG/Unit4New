---
title: void Top()
parent: Public Methods
grand_parent: Stack&lt;T&gt;
layout: page
---

# `void Top()`

### Returns the element at the top of the stack without removing it.

## Exceptions:
- **NullReferenceException**<br>When calling this function from an empty stack.

## Example:

```cs
Stack<int> a = new Stack<int>();
a.Push(5);
Console.WriteLine(a.Top()); // 5
Console.WriteLine(a.IsEmpty()); // False (we haven't removed '5' from the stack)
```