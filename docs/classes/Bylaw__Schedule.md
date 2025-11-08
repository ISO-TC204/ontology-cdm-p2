# Schedule

![Schedule Diagram](../diagrams/Bylaw__Schedule.dot.svg)

<a href="../../diagrams/Bylaw__Schedule.dot.svg">Open interactive Schedule diagram</a>

## Formalization for Schedule

| Property | Constraint |
|----------|------------|
| genProp::hasDescription | max 1 xsd::string |
| genProp::hasIdentifier | max 1 xsd::string |
| genProp::hasName | max 1 xsd::string |
| hasClause | only Clause |
| partwhole::properPartOf | exactly 1 Law |
| subClassOf | BylawOntologyThing |
| subClassOf | BylawOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Law (Bylaw)](Bylaw__Law.md) | hasSchedule |

