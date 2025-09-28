# Research

## Testing Framework

- **Decision**: Use xUnit as the primary testing framework.
- **Rationale**: xUnit is a modern, flexible, and widely-used testing framework for .NET. It is the default choice for many .NET projects and is well-supported by the community.
- **Alternatives considered**: MSTest, NUnit.

## Performance Goals

- **Decision**: Defer setting specific performance goals until after initial implementation and performance testing.
- **Rationale**: It is difficult to set realistic performance goals without a baseline. The initial focus will be on correctness and functionality.

## Constraints

- **Decision**: No specific constraints identified at this time.
- **Rationale**: The project is a greenfield project with no known constraints.

## Scale/Scope

- **Decision**: The initial scope is for a single user managing their personal finances. The system should be designed to scale to a small number of users in the future.
- **Rationale**: This is a personal budgeting application, so the initial scale is small. The architecture should allow for future growth if needed.
