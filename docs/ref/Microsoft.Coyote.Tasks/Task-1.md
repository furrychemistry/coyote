# Task&lt;TResult&gt; class

Represents an asynchronous operation that can return a value. Each [`Task`](Task-1.md) is a thin wrapper over Task and each call simply invokes the wrapped task. During testing, a [`Task`](Task.md) is controlled by the runtime and systematically interleaved with other asynchronous operations to find bugs.

```csharp
public class Task<TResult> : Task
```

| parameter | description |
| --- | --- |
| TResult | The type of the produced result. |

## Public Members

| name | description |
| --- | --- |
| [Result](Task-1/Result.md) { get; } | Gets the result value of this task. |
| [UncontrolledTask](Task-1/UncontrolledTask.md) { get; } | The uncontrolled Task that is wrapped inside this controlled [`Task`](Task-1.md). |
| [ConfigureAwait](Task-1/ConfigureAwait.md)(…) | Configures an awaiter used to await this task. |
| [GetAwaiter](Task-1/GetAwaiter.md)() | Gets an awaiter for this awaitable. |

## See Also

* class [Task](Task.md)
* namespace [Microsoft.Coyote.Tasks](../Microsoft.Coyote.TasksNamespace.md)
* assembly [Microsoft.Coyote](../Microsoft.Coyote.md)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.Coyote.dll -->