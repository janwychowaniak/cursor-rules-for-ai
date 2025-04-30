## Project-Specific Rules for Cursor AI

### Rules for Architecture Considerations
- Consider and discuss system quality attributes (scalability, maintainability, testability) for all solutions.
- Propose appropriate design patterns relevant to the problem domain before implementation.
- Evaluate technical debt implications of proposed solutions.
- Consider deployment, monitoring, and operational aspects of solutions where relevant.
- Suggest refactoring opportunities when reviewing existing code structures.
- Recommend appropriate architecture styles (microservices, event-driven, etc.) based on project needs.

### Rules for Comprehensive Testing
- Write unit tests using pytest; mock external dependencies where necessary.
- Suggest appropriate testing strategies beyond unit tests when relevant (integration, property-based, performance testing).
- For data transformation code, recommend property-based testing to verify logical relationships between inputs and outputs.
- Consider suggesting end-to-end tests for critical user workflows.
- For complex systems, recommend integration testing that uses appropriate strategies (top-down, bottom-up, or sandwich approach).
- Suggest performance benchmarking for resource-intensive operations.

### Rules for Legacy Code
- For existing codebases, analyze code before suggesting changes, prioritizing high-impact improvements.
- Recommend setting up characterization tests before refactoring legacy code.
- Suggest incremental refactoring steps rather than complete rewrites when working with legacy code.
- Identify opportunities to extract common patterns from duplicated code.
- Suggest code improvements that enhance readability without changing behavior.
- Recommend techniques to safely modernize deprecated Python syntax and libraries.

### Rules for Project Structure
- Suggest appropriate project structures based on application type and complexity.
- Recommend logical organization of packages and modules to minimize coupling.
- Provide guidance on effective naming conventions for modules, packages, and project components.
- Suggest strategies for managing project dependencies and virtual environments.
- Recommend standard directory structures for different types of Python projects.
- Consider deployment and packaging concerns when suggesting project organization.
