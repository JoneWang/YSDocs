# Library.ImportLibrary Method

Loads functions from another [`Library`](/api/csharp/yarn/library.md).


```csharp
public void ImportLibrary(Library otherLibrary)
```
## Remarks

If the other library contains a function with the same name as
one in this library, the function in the other library takes
precedence.


## Parameters
|Parameter|Description|
|:---|:---|
|[`Library`](/api/csharp/yarn/library.md) otherLibrary|The library to import functions from.|


<div class="class-metadata">

Parent: [`Library`](/api/csharp/yarn/library.md), Namespace: [`Yarn`](/api/csharp/yarn/README.md), Assembly: YarnSpinner.dll
</div>

## Source
Defined in [YarnSpinner/Library.cs](https://github.com/YarnSpinnerTool/YarnSpinner//blob/develop/YarnSpinner/Library.cs#L51), line 51.