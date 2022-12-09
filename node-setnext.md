---
title: void SetNext()
layout: page
parent: Public Methods
grand_parent: Node&lt;T&gt;
---

# `void SetNext()`

### Sets the next `Node<T>` for this instance.

## Exceptions:
- None.

## Example:

```cs
Node<int> c = new Node<int>(7);
Node<int> b = new Node<int>(5);
Node<int> a = new Node<int>(6, b);
Console.WriteLine(a.GetValue()); // 6
Console.WriteLine(a.GetNext().GetValue()); // 5
a.SetNext(c);
Console.WriteLine(a.GetNext().GetValue()); // 7
```

----
