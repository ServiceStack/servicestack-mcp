# ServiceStack MCP Guidelines

## Build & Testing Commands
- Build: `dotnet build`
- Run: `dotnet run`
- Test all: `dotnet test`
- Test single: `dotnet test --filter "FullyQualifiedName=Namespace.TestClass.TestMethod"`
- Format code: `dotnet format`

## Code Style Guidelines
- Follow C# naming conventions: PascalCase for types and methods, camelCase for fields and variables
- Use nullable reference types and handle nulls appropriately
- Prefer async/await over Task continuations
- Organize imports alphabetically with System.* imports first
- Keep methods focused with single responsibility
- Use ServiceStack's Error Handling pattern (throw typed exceptions)
- Document public API with XML comments
- Write integration and unit tests for new features

## Repository Structure
- Organize services and features in domain-specific folders
- Keep models and interfaces in separate files
- Follow ServiceStack's recommended project organization