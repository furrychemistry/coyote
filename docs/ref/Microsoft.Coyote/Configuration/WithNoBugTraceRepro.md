# Configuration.WithNoBugTraceRepro method

Updates the configuration with the ability to reproduce bug traces enabled or disabled. Disabling reproducibility allows skipping errors due to uncontrolled concurrency, for example when the program is only partially rewritten, or there is external concurrency that is not mocked, or when the program uses an API that is not yet supported.

```csharp
public Configuration WithNoBugTraceRepro(bool isDisabled = true)
```

| parameter | description |
| --- | --- |
| isDisabled | If true, then reproducing bug traces is disabled. |

## See Also

* class [Configuration](../Configuration.md)
* namespace [Microsoft.Coyote](../Configuration.md)
* assembly [Microsoft.Coyote](../../Microsoft.Coyote.md)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.Coyote.dll -->
