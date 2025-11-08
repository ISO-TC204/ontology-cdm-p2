# Household

![Household Diagram](../diagrams/Household__Household.dot.svg)

<a href="../../diagrams/Household__Household.dot.svg">Open interactive Household diagram</a>

## Formalization for Household

| Property | Constraint |
|----------|------------|
| cdmOrg::hasMember | only person::Person |
| householdOccupies | max 1 cityResident::Residence |
| subClassOf | HouseholdOntologyThing |
| subClassOf | HouseholdOntologyThing |
| time::hasTime | only time::ProperInterval |

