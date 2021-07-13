# Library Class

A collection of functions that can be called from Yarn programs.


```csharp
public class Library
```
## Remarks

You do not create instances of this class yourself. The [`Dialogue`](/api/csharp/yarn/dialogue.md) class creates one of its own, which you can
access via the [`Library`](/api/csharp/yarn/dialogue.library.md) property.




## Methods
|Name|Description|
|:---|:---|
|[DeregisterFunction(String)](/api/csharp/yarn/library.deregisterfunction-system.string-.md)| Removes a function from the Library. |
|[FunctionExists(String)](/api/csharp/yarn/library.functionexists-system.string-.md)| Gets a value indicating whether this [`Library`](/api/csharp/yarn/library.md) contains a function named `name`. |
|[GetFunction(String)](/api/csharp/yarn/library.getfunction-system.string-.md)| Returns a [`Delegate`](https://docs.microsoft.com/dotnet/api/System.Delegate) with a given name. |
|[ImportLibrary(Library)](/api/csharp/yarn/library.importlibrary-library-.md)| Loads functions from another [`Library`](/api/csharp/yarn/library.md). |
|[RegisterFunction(String, Delegate)](/api/csharp/yarn/library.registerfunction-system.string,system.delegate-.md)||
|[RegisterFunction<TResult>(String, Func<TResult>)](/api/csharp/yarn/library.registerfunction--1-system.string,system.func---0--.md)| Registers a new function that returns a value, which can be called from a Yarn program. |
|[RegisterFunction<T1, TResult>(String, Func<T1, TResult>)](/api/csharp/yarn/library.registerfunction--2-system.string,system.func---0,--1--.md)||
|[RegisterFunction<T1, T2, TResult>(String, Func<T1, T2, TResult>)](/api/csharp/yarn/library.registerfunction--3-system.string,system.func---0,--1,--2--.md)||
|[RegisterFunction<T1, T2, T3, TResult>(String, Func<T1, T2, T3, TResult>)](/api/csharp/yarn/library.registerfunction--4-system.string,system.func---0,--1,--2,--3--.md)||
|[RegisterFunction<T1, T2, T3, T4, TResult>(String, Func<T1, T2, T3, T4, TResult>)](/api/csharp/yarn/library.registerfunction--5-system.string,system.func---0,--1,--2,--3,--4--.md)||
|[RegisterFunction<T1, T2, T3, T4, T5, TResult>(String, Func<T1, T2, T3, T4, T5, TResult>)](/api/csharp/yarn/library.registerfunction--6-system.string,system.func---0,--1,--2,--3,--4,--5--.md)||
## See Also
* [`Dialogue`](/api/csharp/yarn/dialogue.md): 
Co-ordinates the execution of Yarn programs.

<div class="class-metadata">

Namespace: [`Yarn`](/api/csharp/yarn/README.md), Assembly: YarnSpinner.dll
</div>

## Source
Defined in [YarnSpinner/Library.cs](https://github.com/YarnSpinnerTool/YarnSpinner//blob/develop/YarnSpinner/Library.cs#L16), line 16.