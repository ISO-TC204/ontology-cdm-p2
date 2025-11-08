# Input

![Input Diagram](../diagrams/CityService__Input.dot.svg)

<a href="../../diagrams/CityService__Input.dot.svg">Open interactive Input diagram</a>

## Formalization for Input

| Property | Constraint |
|----------|------------|
| genProp::hasDescription | only xsd::string |
| genProp::hasName | max 1 xsd::string |
| hasContributingStakeholder | only Stakeholder |
| iso21972::for_time_interval | only time::DateTimeInterval |
| subClassOf | CityServiceOntologyThing |
| subClassOf | CityServiceOntologyThing |
| subClassOf | resource::TerminalResourceState |

## Used by classes

| Class | Property |
|-------|----------|
| [Program (CityService)](CityService__Program.md) | hasInput |
| [Service (CityService)](CityService__Service.md) | hasInput |

