# Package Source Mapping

Use this to control which packages come from what repository

https://docs.microsoft.com/en-us/nuget/consume-packages/package-source-mapping

# Traversal (SDK Build)

This is a more flexible way of specifying what to build than a solution file.
Makes more sense given the shift to VS Code and the fact that VS Code doesn't use solution files.

https://github.com/microsoft/MSBuildSdks/tree/main/src/Traversal

# SlnGen

This is a `dotnet` tool that will generate a solution file with all the dependencies of a set of projects.

This is the type of tool that I've written (and rewritten).

I does not yet do "inverse solutions".

https://github.com/jeffkl/SlnGen
