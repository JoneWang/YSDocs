# OptionsHandler Delegate

Represents the method that is called when the Dialogue delivers an
[`OptionSet`](/api/csharp/yarn/optionset.md).


```csharp
public delegate void OptionsHandler(OptionSet options);
```

## Parameters
|Parameter|Description|
|:---|:---|
|[`OptionSet`](/api/csharp/yarn/optionset.md) options|The [`OptionSet`](/api/csharp/yarn/optionset.md) that has been delivered.|


## See Also
* [`LineHandler`](/api/csharp/yarn/linehandler.md): 
Represents the method that is called when the Dialogue delivers a
[`Line`](/api/csharp/yarn/line.md).

* [`CommandHandler`](/api/csharp/yarn/commandhandler.md): 
Represents the method that is called when the Dialogue delivers a
[`Command`](/api/csharp/yarn/command.md).

* [`NodeStartHandler`](/api/csharp/yarn/nodestarthandler.md): 
Represents the method that is called when the Dialogue begins
executing a node.

* [`NodeCompleteHandler`](/api/csharp/yarn/nodecompletehandler.md): 
Represents the method that is called when the Dialogue reaches the
end of a node.

* [`DialogueCompleteHandler`](/api/csharp/yarn/dialoguecompletehandler.md): 
Represents the method that is called when the dialogue has reached
its end, and no more code remains to be run.

<div class="class-metadata">

Namespace: [`Yarn`](/api/csharp/yarn/README.md), Assembly: YarnSpinner.dll
</div>

## Source
Defined in [YarnSpinner/Dialogue.cs](https://github.com/YarnSpinnerTool/YarnSpinner//blob/develop/YarnSpinner/Dialogue.cs#L313), line 313.