# PersonId

![PersonId Diagram](../diagrams/Person__PersonId.dot.svg)

<a href="../../diagrams/Person__PersonId.dot.svg">Open interactive PersonId diagram</a>

## Formalization for PersonId

| Property | Constraint |
|----------|------------|
| genericproperties::hasIdentifier | exactly 1 xsd::string |
| hasIDType | only IDType |
| issuedBy | max 1 agent::Agent |
| photoID | max 1 xsd::boolean |
| subClassOf | PersonOntologyThing |
| subClassOf | PersonOntologyThing |
| validityPeriod | max 1 time::Interval |

## Used by classes

| Class | Property |
|-------|----------|
| [Person (Person)](Person__Person.md) | hasPersonID |

