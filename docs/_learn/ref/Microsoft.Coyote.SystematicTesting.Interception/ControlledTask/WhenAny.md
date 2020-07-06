---
layout: reference
section: learn
title: WhenAny
permalink: /learn/ref/Microsoft.Coyote.SystematicTesting.Interception/ControlledTask/WhenAny
---
# ControlledTask.WhenAny method (1 of 4)

Creates a Task that will complete when any task in the specified enumerable collection have completed.

```csharp
public static Task<Task> WhenAny(IEnumerable<Task> tasks)
```

| parameter | description |
| --- | --- |
| tasks | The tasks to wait for completion. |

## See Also

* class [ControlledTask](../ControlledTaskType)
* namespace [Microsoft.Coyote.SystematicTesting.Interception](../ControlledTaskType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

---

# ControlledTask.WhenAny method (2 of 4)

Creates a Task that will complete when any task in the specified array have completed.

```csharp
public static Task<Task> WhenAny(params Task[] tasks)
```

| parameter | description |
| --- | --- |
| tasks | The tasks to wait for completion. |

## See Also

* class [ControlledTask](../ControlledTaskType)
* namespace [Microsoft.Coyote.SystematicTesting.Interception](../ControlledTaskType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

---

# ControlledTask.WhenAny&lt;TResult&gt; method (3 of 4)

Creates a Task that will complete when any task in the specified enumerable collection have completed.

```csharp
public static Task<Task<TResult>> WhenAny<TResult>(IEnumerable<Task<TResult>> tasks)
```

| parameter | description |
| --- | --- |
| tasks | The tasks to wait for completion. |

## See Also

* class [ControlledTask](../ControlledTaskType)
* namespace [Microsoft.Coyote.SystematicTesting.Interception](../ControlledTaskType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

---

# ControlledTask.WhenAny&lt;TResult&gt; method (4 of 4)

Creates a Task that will complete when any task in the specified array have completed.

```csharp
public static Task<Task<TResult>> WhenAny<TResult>(params Task<TResult>[] tasks)
```

| parameter | description |
| --- | --- |
| tasks | The tasks to wait for completion. |

## See Also

* class [ControlledTask](../ControlledTaskType)
* namespace [Microsoft.Coyote.SystematicTesting.Interception](../ControlledTaskType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.Coyote.dll -->