# Include generated code in C# project

In MSBuild, files created during the execution phase of the build are not included in compilation, because they didn't exist during the evaluation phase. This repository contains a sample project that demonstrates how to work around this limitation and include generated code in a C# project.

```bash
dotnet build && dotnet run --no-build --project src/IncludeGeneratedCode.BaseCase
```
