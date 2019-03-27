# BuildApp class

Represents the command-line application for the build.

```csharp
public sealed class BuildApp
```

## Public Members

| name | description |
| --- | --- |
| [Targets](BuildApp/Targets.md) { get; } | The targets previously added to the build via [`Target`](BuildApp/Target.md). |
| [AddFlag](BuildApp/AddFlag.md)(…) | Adds support for a no-value command-line flag. |
| [AddOption](BuildApp/AddOption.md)(…) | Adds support for a single-value command-line option. |
| [Target](BuildApp/Target.md)(…) | Creates a build target. |

## See Also

* namespace [Faithlife.Build](../Faithlife.Build.md)
* [BuildApp.cs](https://github.com/Faithlife/RepoName/tree/master/src/Faithlife.Build/BuildApp.cs)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Build.dll -->