# person:Person

![person:Person Diagram](../diagrams/Person__person:Person.dot.svg)

<a href="../../diagrams/Person__person:Person.dot.svg">Open interactive person:Person diagram</a>

## Formalization for person:Person

| Property | Constraint |
|----------|------------|
| contact:email | only xsd:string |
| contact:hasAddress | only contact:Address |
| contact:hasTelephone | only contact:PhoneNumber |
| person:alias | only person:PersonName |
| person:birthDate | max 1 time::Instant |
| person:birthplace | max 1 contact:/Address |
| person:children | only person:Person |
| person:citizenOf | only person:Citizenship |
| person:deathDate | max 1 time::Instant |
| person:deathPlace | max 1 contact:Address |
| person:hasEducation | only person:Education |
| person:hasGenderIdentity | only person:Gender |
| person:hasPersonID | only person:PersonId |
| person:hasSkill | only person:Skill |
| person:income | only cityUnits:MonetaryValue |
| person:name | max 1 person:PersonName |
| person:parent | only person:Person |
| person:sex | max 1 person:Sex |
| person:spouse | only person:Person |
| subClassOf | person:PersonOntologyThing |
| subClassOf | person:PersonOntologyThing |
| subClassOf | agent:Agent |

## Used by classes

| Class | Property |
|-------|----------|
| [person:Person](Person__person:Person.md) | person:children |
| [person:Person](Person__person:Person.md) | person:parent |
| [person:Person](Person__person:Person.md) | person:spouse |

