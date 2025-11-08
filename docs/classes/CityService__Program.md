# Program

![Program Diagram](../diagrams/CityService__Program.dot.svg)

<a href="../../diagrams/CityService__Program.dot.svg">Open interactive Program diagram</a>

## Formalization for Program

| Property | Constraint |
|----------|------------|
| genProp::hasDescription | max 1 xsd::string |
| genProp::hasName | max 1 xsd::string |
| hasBeneficialStakeholder | only Stakeholder |
| hasContributingStakeholder | only Stakeholder |
| hasInput | only Input |
| hasOutcome | only Outcome |
| hasOutput | only Output |
| hasService | only Service |
| subClassOf | CityServiceOntologyThing |
| subClassOf | CityServiceOntologyThing |
| subClassOf | activity::Activity |

