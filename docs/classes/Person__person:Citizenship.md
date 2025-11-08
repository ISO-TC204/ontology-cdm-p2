# person:Citizenship

![person:Citizenship Diagram](../diagrams/Person__person:Citizenship.dot.svg)

<a href="../../diagrams/Person__person:Citizenship.dot.svg">Open interactive person:Citizenship diagram</a>

## Formalization for person:Citizenship

| Property | Constraint |
|----------|------------|
| person:forCountry | max 1 contact:/Country |
| person:validityPeriod | max 1 time::ProperInterval |
| subClassOf | person:PersonOntologyThing |
| subClassOf | person:PersonOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [person:Person](Person__person:Person.md) | person:citizenOf |

