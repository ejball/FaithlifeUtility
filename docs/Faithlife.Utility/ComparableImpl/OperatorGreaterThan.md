# ComparableImpl.OperatorGreaterThan&lt;T&gt; method

Standard implementation of the greater than operator.

```csharp
public static bool OperatorGreaterThan<T>(T left, T right)
    where T : class, IComparable<T>
```

| parameter | description |
| --- | --- |
| left | The left item. |
| right | The right item. |

## Return Value

True if the left is greater than the right.

## See Also

* class [ComparableImpl](../ComparableImpl.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->