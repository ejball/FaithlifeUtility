# FileUtility.TryMove method

Attempts to move the specified file to a new location, returning `true` if successful.

```csharp
public static bool TryMove(string sourceFileName, string destinationFileName)
```

| parameter | description |
| --- | --- |
| sourceFileName | The name of the file to move. |
| destinationFileName | The new path for the file. |

## Return Value

`true` if the file was successfully moved, otherwise `false`.

## Remarks

*destinationFileName* must not exist.

## See Also

* class [FileUtility](../FileUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->
