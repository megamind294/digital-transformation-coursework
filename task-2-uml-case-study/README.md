# Task 2 — UML / Process-Modelling Reconstruction

Recovered course notes indicate Task 2 involved a longer Digital Transformation analysis supported by UML/model diagrams. The original essay and diagrams are not available, so this folder contains a **new portfolio reconstruction** that demonstrates the same modelling skills without claiming to reproduce the submitted work.

## Fictional case: ServiceHub

ServiceHub is a fictional service company whose customer requests currently arrive by email and telephone. Staff manually copy details into spreadsheets, route work between departments, and update customers individually. This creates duplicate entry, inconsistent status information, slow hand-offs, and limited management visibility.

### Transformation objective

Introduce a self-service request platform that:

- captures requests through a structured digital form;
- validates required data before submission;
- automatically routes work to the responsible team;
- exposes request status to customers;
- records an auditable history of status changes;
- sends notifications at key stages;
- provides operational reporting for management.

## Actors

- **Customer** — submits and tracks requests.
- **Service Agent** — reviews, updates, and resolves assigned requests.
- **Team Manager** — monitors workload and performance.
- **Notification Service** — delivers status notifications.
- **Identity Provider** — authenticates users.

## Business value

The proposed workflow reduces manual re-entry, standardizes intake, improves transparency, and creates structured process data that can support performance analysis. The transformation also creates new requirements for access control, data protection, service reliability, training, and governance.

The accompanying `diagrams.md` uses Mermaid to express several UML-style views of the reconstructed case.
