# Role

![Role Diagram](../diagrams/Organization__Role.dot.svg)

<a href="../../diagrams/Organization__Role.dot.svg">Open interactive Role diagram</a>

## Formalization for Role

| Property | Constraint |
|----------|------------|
| hasGoal | only Goal |
| hasProcess | only activity::Activity |
| hasResource | only resource1::Resource |
| subClassOf | CityOrgOntologyThing |
| subClassOf | org::Role |
| subClassOf | CityOrgOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Organization Agent (Organization)](Organization__OrganizationAgent.md) | playsRole |

