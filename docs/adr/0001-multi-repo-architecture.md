ADR-0001 — Use a multi-repository architecture

Status
Accepted

Context
EcoScout contains reusable CV logic, robot-specific
integration, and cloud/application infrastructure.

Decision
Separate the project into:
- eco-vision
- eco-edge
- eco-platform

Consequences
Positive:
- clear ownership boundaries
- independent releases
- eco-vision can be reused outside ROS
- easier testing

Negative:
- version coordination between repositories
- slightly more CI/CD overhead
