---
title: Node&lt;T&gt; GetNext()
layout: page
parent: Public Methods
grand_parent: Node&lt;T&gt;
---

# `Node<T> GetNext()`

### Returns the next `Node<T>`. **May return `null`.**

## Exceptions:
- None.

## Example:

```cs
Node<int> b = new Node<int>(5);
Node<int> a = new Node<int>(6, b);
Console.WriteLine(a.GetValue()); // 6
Console.WriteLine(a.GetNext().GetValue()); // 5
Console.WriteLine(a.GetNext().GetNext() == null); // True
```

----
