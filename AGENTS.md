```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure a consistent, maintainable, and robust codebase for our AI agents. Adherence to these principles is mandatory for all development activities.

## 1. DRY (Don't Repeat Yourself)

*   **Core Logic Reuse:**  All core logic, algorithms, and data structures should be encapsulated within reusable components or functions. Avoid duplicating code across multiple files.
*   **Abstraction:**  Create abstract classes or interfaces to represent common behaviors and data structures, promoting modularity.
*   **Standardized Components:**  Define standardized components with clearly defined responsibilities and inputs/outputs, minimizing variation.

## 2. KISS (Keep It Simple, Stupid)

*   **Simplicity over Complexity:** Favor straightforward, easily understood code over overly complex solutions.  Avoid unnecessary abstractions or convoluted logic.
*   **Minimal Dependencies:** Each file should have a single, well-defined purpose. Reduce dependency clutter.
*   **Readability:** Prioritize clear variable names, consistent indentation, and comments to enhance understanding.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class, module, or function should have one clear, well-defined responsibility.
*   **Open/Closed Principle:**  The system should be extensible – new functionality should be added without modifying existing code. Utilize interfaces for abstraction.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the system.
*   **Interface Segregation Principle:** Each interface should define only the methods that are actually used by the clients.
*   **Dependency Inversion Principle:**  High-level modules should be dependent on low-level modules, which in turn should depend on abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Unnecessary Code:**  Do not implement functionality that is not currently required.  Defer implementation until explicitly needed.
*   **Focus on Core Requirements:**  Prioritize implementing the essential features for the current goal.  Don't introduce features that aren't directly tied to the primary objective.

## 5. Code Quality & Structure

*   **File Size Limit:** Each file should maintain a maximum of 180 lines of code.
*   **Naming Conventions:** Follow consistent naming conventions (e.g., camelCase for functions, PascalCase for classes).
*   **Comments:**  Add concise, informative comments to explain complex logic, assumptions, and purpose where necessary.  Avoid redundant comments.
*   **Error Handling:**  Implement appropriate error handling and logging.  Don’t mask errors; log them appropriately.
*   **Data Structures:** Choose appropriate data structures (lists, dictionaries, etc.) for their specific use cases.
*   **Modular Design:**  Divide the codebase into logical modules or components, each responsible for a specific aspect of the AGENTS system.
*   **Unit Testing:** All code should be thoroughly unit tested.

## 6. Test Coverage

*   **Goal:**  Achieve 80% or higher test coverage.
*   **Types of Tests:**  Include unit tests, integration tests, and potentially system tests.
*   **Test Driven Development (TDD):**  Consider adopting TDD principles where appropriate for specific components.

## 7. Production-Ready Code

*   **Readability:** Prioritize code clarity and maintainability.
*   **Efficiency:**  Strive for efficient code.  Avoid unnecessary operations.
*   **Security:**  Consider security implications when writing code.
*   **Documentation:**  Document code clearly.
*   **Maintainability:** Ensure the code is easy to understand and modify in the future.

## 8.  Specific Requirements (Example - Adapt as Needed)

*   **Agent Initialization:**  Define a clear and modular process for agent initialization.
*   **Data Management:**  Implement a robust data management system.
*   **Communication Protocol:**  Clearly define communication protocol details.
*   **Configuration:** Implement a flexible configuration mechanism.


These guidelines are subject to change as the project evolves.  Updates will be documented and communicated to all team members.  All development must be productive and aligned with these principles.
```