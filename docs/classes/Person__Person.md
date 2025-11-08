# Person

![Person Diagram](../diagrams/Person__Person.dot.svg)

<a href="../../diagrams/Person__Person.dot.svg">Open interactive Person diagram</a>

## Formalization for Person

| Property | Constraint |
|----------|------------|
| alias | only PersonName |
| birthDate | max 1 time::Instant |
| birthplace | max 1 contact::Address |
| children | only Person |
| citizenOf | only Citizenship |
| contact::email | only xsd::string |
| contact::hasAddress | only contact::Address |
| contact::hasTelephone | only contact::PhoneNumber |
| deathDate | max 1 time::Instant |
| deathPlace | max 1 contact::Address |
| hasEducation | only Education |
| hasGenderIdentity | only Gender |
| hasPersonID | only PersonId |
| hasSkill | only Skill |
| income | only cityUnits::MonetaryValue |
| name | max 1 PersonName |
| parent | only Person |
| sex | max 1 Sex |
| spouse | only Person |
| subClassOf | PersonOntologyThing |
| subClassOf | PersonOntologyThing |
| subClassOf | agent::Agent |

## Used by classes

| Class | Property |
|-------|----------|
| [Person (Person)](Person__Person.md) | children |
| [Person (Person)](Person__Person.md) | parent |
| [Person (Person)](Person__Person.md) | spouse |

