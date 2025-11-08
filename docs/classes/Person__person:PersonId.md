# person:PersonId

![person:PersonId Diagram](../diagrams/Person__person:PersonId.dot.svg)

<a href="../../diagrams/Person__person:PersonId.dot.svg">Open interactive person:PersonId diagram</a>

## Formalization for person:PersonId

| Property | Constraint |
|----------|------------|
| genProp:hasIdentifier | exactly 1 xsd:string |
| person:hasIDType | only person:IDType |
| person:issuedBy | max 1 agent:Agent |
| person:photoID | max 1 xsd:boolean |
| person:validityPeriod | max 1 time::Interval |
| subClassOf | person:PersonOntologyThing |
| subClassOf | person:PersonOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [person:Person](Person__person:Person.md) | person:hasPersonID |

