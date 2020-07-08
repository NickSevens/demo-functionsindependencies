# DEMO - Load Azure Functions from external dependencies

This code shows the loading of external dependencies as Azure Functions.

To accomplish this make sure to:

- Add `<FunctionsInDependencies>true</FunctionsInDependencies>` in the .csproj file
- Use the referenced assembly in the Azure Function app by calling _something_ in the assembly.
