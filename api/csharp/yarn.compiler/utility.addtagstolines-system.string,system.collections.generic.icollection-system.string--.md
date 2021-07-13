# Utility.AddTagsToLines Method

Given Yarn source code, adds line tags to the ends of all lines
that need one and do not already have one.


```csharp
public static string AddTagsToLines(string contents, ICollection<string> existingLineTags)
```
## Remarks
This method ensures that it does not generate line
tags that are already present in the file, or present in the
`existingLineTags` collection.

Line tags are added to any line of source code that contains
user-visible text: lines, options, and shortcut options.


## Parameters
|Parameter|Description|
|:---|:---|
|[`string`](https://docs.microsoft.com/dotnet/api/System.String) contents|The source code to add line tags to.|
|[`String}`](https://docs.microsoft.com/dotnet/api/System.Collections.Generic.ICollection{System.String}) existingLineTags|The collection of line tags already exist elsewhere in the source code; the newly added line tags will not be duplicates of any in this collection.|
## Return Type
[`string`](https://docs.microsoft.com/dotnet/api/System.String): The modified source code, with line tags
added.



<div class="class-metadata">

Parent: [`Utility`](/api/csharp/yarn.compiler/utility.md), Namespace: [`Yarn.Compiler`](/api/csharp/yarn.compiler/README.md), Assembly: YarnSpinner.Compiler.dll
</div>

## Source
Defined in [YarnSpinner.Compiler/Utility.cs](https://github.com/YarnSpinnerTool/YarnSpinner//blob/develop/YarnSpinner.Compiler/Utility.cs#L126), line 126.