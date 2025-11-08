# Service

![Service Diagram](../diagrams/CityService__Service.dot.svg)

<a href="../../diagrams/CityService__Service.dot.svg">Open interactive Service diagram</a>

## Formalization for Service

| Property | Constraint |
|----------|------------|
| genProp::hasDescription | max 1 xsd::string |
| genProp::hasName | max 1 xsd::string |
| hasBeneficialStakeholder | only Stakeholder |
| hasContributingStakeholder | only Stakeholder |
| hasInput | only Input |
| hasOutcome | only Outcome |
| hasOutput | only Output |
| subClassOf | CityServiceOntologyThing |
| subClassOf | CityServiceOntologyThing |
| subClassOf | activity::Activity |

## Used by classes

| Class | Property |
|-------|----------|
| [Program (CityService)](CityService__Program.md) | hasService |

