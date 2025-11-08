# BusinessEstablishment

![BusinessEstablishment Diagram](../diagrams/Organization__BusinessEstablishment.dot.svg)

<a href="../../diagrams/Organization__BusinessEstablishment.dot.svg">Open interactive BusinessEstablishment diagram</a>

## Formalization for BusinessEstablishment

| Property | Constraint |
|----------|------------|
| contact::hasAddress | only contact::Address |
| spatialLoc::hasLocation | max 1 spatialLoc::Location |
| subClassOf | CityOrgOntologyThing |
| subClassOf | CityOrgOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [For Profit Organization (Organization)](Organization__ForProfitOrganization.md) | hasEstablishment |

