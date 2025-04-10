# `CppWinRT.Sdk`

`CppWinRT.Sdk` is an MSBuild SDK that enables build for [C++/WinRT](https://github.com/Microsoft/CppWinRT) via the .NET SDK's new SDK-style projects feature.

A C++/WinRT project built with `CppWinRT.Sdk` might look as simple as this:
```xml
<Project Sdk="Riverside.Build.CppWinRT.Sdk">
</Project>
```
