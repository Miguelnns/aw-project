# Account
## Context and Problem Statement
Developing the authentication module and displaying account details within the application.
## Decision Drivers
* Prioritize security and user authenticatoin throughout the application.
* Ensure easy access to and management of account details for users.
## Considered Options
1. Layers
2. Components
3. Workflow
## Decision Outcome
We decided to divide the system in layers because the system under
construction does not suggest an organization by data flow or control flow.
### Consequences
* Good: Simplifies the user experience by providing a unified interface for authentication and account management; Enhances security by tightly integrating authentication with account details, reducing potencial vulnerabilities.
* Bad: Increaces complexity in development and maintenance due to the integration of multiple funcionalities within the same frontend service; May limit flexibility in certain authentication or account management features if tightly coupled with other parts of the application.

