# Actor.RandomBoolean method (1 of 2)

Returns a nondeterministic boolean choice, that can be controlled during analysis or testing.

```csharp
protected bool RandomBoolean()
```

## Return Value

The controlled nondeterministic choice.

## See Also

* class [Actor](../Actor.md)
* namespace [Microsoft.Coyote.Actors](../Actor.md)
* assembly [Microsoft.Coyote](../../Microsoft.Coyote.md)

---

# Actor.RandomBoolean method (2 of 2)

Returns a nondeterministic boolean choice, that can be controlled during analysis or testing. The value is used to generate a number in the range [0..maxValue), where 0 triggers true.

```csharp
protected bool RandomBoolean(int maxValue)
```

| parameter | description |
| --- | --- |
| maxValue | The max value. |

## Return Value

The controlled nondeterministic choice.

## See Also

* class [Actor](../Actor.md)
* namespace [Microsoft.Coyote.Actors](../Actor.md)
* assembly [Microsoft.Coyote](../../Microsoft.Coyote.md)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.Coyote.dll -->
