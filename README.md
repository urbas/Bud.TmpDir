[![Build status](https://ci.appveyor.com/api/projects/status/au3barw578jkvj28/branch/master?svg=true)](https://ci.appveyor.com/project/urbas/bud-tmpdir/branch/master)  [![NuGet](https://img.shields.io/nuget/v/Bud.TmpDir.svg)](https://www.nuget.org/packages/Bud.TmpDir/)


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
