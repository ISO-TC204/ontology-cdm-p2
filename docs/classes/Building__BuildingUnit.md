# BuildingUnit

![BuildingUnit Diagram](../diagrams/Building__BuildingUnit.dot.svg)

<a href="../../diagrams/Building__BuildingUnit.dot.svg">Open interactive BuildingUnit diagram</a>

## Formalization for BuildingUnit

| Property | Constraint |
|----------|------------|
| buildingFacility | only Facility |
| change::existsAt | exactly 1 time::TemporalEntity |
| contact::hasAddress | only contact::Address |
| floorToCeilingHeight | only cityUnits::Length |
| hasRent | only cityUnits::MonetaryValue |
| numberOfBedrooms | only xsd::nonNegativeInteger |
| numberOfRooms | only xsd::nonNegativeInteger |
| partwhole::hasValue | only cityUnits::MonetaryValue |
| subClassOf | BuildingOntologyThing |
| subClassOf | BuildingOntologyThing |
| subClassOf | change::Manifestation |
| subClassOf | infrastructure::InfrastructureElement |
| unitInBuilding | exactly 1 Building |
| unitSize | only cityUnits::Area |

## Used by classes

| Class | Property |
|-------|----------|
| [Building (Building)](Building__Building.md) | hasBuildingUnit |

