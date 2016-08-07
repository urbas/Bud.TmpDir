__Table of contents__

* [About](#about)


## About

Bud.TmpDir is a disposable class that creates a directory when instantiated, and deletes that directory when disposed.

Example of use:

```csharp
using (var tmpDir = new Bud.TmpDir()) {
  System.Console.WriteLine($"Temporary directory: {tmpDir.Path}");
}
```
