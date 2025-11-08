# Citizenship

![Citizenship Diagram](../diagrams/Person__Citizenship.dot.svg)

<a href="../../diagrams/Person__Citizenship.dot.svg">Open interactive Citizenship diagram</a>

## Formalization for Citizenship

| Property | Constraint |
|----------|------------|
| forCountry | max 1 contact::Country |
| subClassOf | PersonOntologyThing |
| subClassOf | PersonOntologyThing |
| validityPeriod | max 1 time::ProperInterval |

## Used by classes

| Class | Property |
|-------|----------|
| [Person (Person)](Person__Person.md) | citizenOf |

