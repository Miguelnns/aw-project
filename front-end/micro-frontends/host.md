# Host
## Context and Problem Statement
Creating the main body of the application and displaying a bottom bar navigation.
## Decision Drivers
* Promote reusability and simplicity while using the navigation in all screens.
* Ensure flexability by giving a blank canvas to work on another screens.
## Considered Options
1. Layers
2. Components
3. Workflow
## Decision Outcome
We decided to divide the system in layers because the system under
construction does not suggest an organization by data flow or control flow.
### Consequences
* Good: Enhances user experience by providing consistent navigation across all screens, reducing cognitive load.
* Bad: May limit flexibility in certain cases where unique navigation structures are required for specific screens; Could potentially lead to overcrowding of navigation elements if not carefully managed, affecting usability
