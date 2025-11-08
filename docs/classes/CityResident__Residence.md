# Residence

![Residence Diagram](../diagrams/CityResident__Residence.dot.svg)

<a href="../../diagrams/CityResident__Residence.dot.svg">Open interactive Residence diagram</a>

## Formalization for Residence

| Property | Constraint |
|----------|------------|
| contact::hasAddress | max 1 contact::Address |
| forCity | max 1 iso21972::City |
| hasHomeType | max 1 HomeType |
| hasResidentialRelationship | exactly 1 ResidentialRelationship |
| subClassOf | CityResidentOntologyThing |
| subClassOf | CityResidentOntologyThing |
| time::hasTime | max 1 time::ProperInterval |

## Used by classes

| Class | Property |
|-------|----------|
| [City Resident (CityResident)](CityResident__CityResident.md) | hasResidence |

