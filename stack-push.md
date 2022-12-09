---
title: void Push(T x)
parent: Public Methods
grand_parent: Stack&lt;T&gt;
layout: page
---

# `void Push(T x)`

### Adds an element of type T to the stack.

## Exceptions:
- None.

## Example:

```cs
Stack<int> a = new Stack<int>();
a.Push(5);
// element is now in the stack, so now we can pop it.
Console.WriteLine(a.Pop()); // 5
```