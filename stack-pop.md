---
title: void Pop()
parent: Public Methods
grand_parent: Stack&lt;T&gt;
layout: page
---

# `void Pop()`

### Pops an element, removing it from the stack and returns it.

## Exceptions:
- **NullReferenceException**<br>When calling this function from an empty stack.

## Example:

```cs
Stack<int> a = new Stack<int>();
a.Push(5);
Console.WriteLine(a.Pop()); // 5
Console.WriteLine(a.IsEmpty()); // True (no elements in the stack, since 5 was removed.)
```