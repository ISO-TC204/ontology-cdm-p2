# Employment

![Employment Diagram](../diagrams/Organization__Employment.dot.svg)

<a href="../../diagrams/Organization__Employment.dot.svg">Open interactive Employment diagram</a>

## Formalization for Employment

| Property | Constraint |
|----------|------------|
| employedAs | only Occupation |
| employedBy | some Organization |
| hasCompensation | some Compensation |
| hasEmploymentStatus | only EmploymentStatus |
| subClassOf | CityOrgOntologyThing |
| subClassOf | CityOrgOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Organization Agent (Organization)](Organization__OrganizationAgent.md) | hasEmployment |

