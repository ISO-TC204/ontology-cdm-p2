# Outcome

![Outcome Diagram](../diagrams/CityService__Outcome.dot.svg)

<a href="../../diagrams/CityService__Outcome.dot.svg">Open interactive Outcome diagram</a>

## Formalization for Outcome

| Property | Constraint |
|----------|------------|
| fromPerspectiveOf | exactly 1 Stakeholder |
| genProp::hasDescription | max 1 xsd::string |
| hasBeneficialStakeholder | exactly 1 Stakeholder |
| hasImportance | max 1 Importance |
| hasIndicator | only iso21972::Indicator |
| intendedImpact | max 1 ImpactDirection |
| subClassOf | CityServiceOntologyThing |
| subClassOf | CityServiceOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Program (CityService)](CityService__Program.md) | hasOutcome |
| [Service (CityService)](CityService__Service.md) | hasOutcome |

