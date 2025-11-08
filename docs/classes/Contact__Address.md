# Address

![Address Diagram](../diagrams/Contact__Address.dot.svg)

<a href="../../diagrams/Contact__Address.dot.svg">Open interactive Address diagram</a>

## Specializations of Address

| Class | Description |
|-------|-------------|
| [Cottage Address](Contact__Cottage Address.md) |  |
| [Home Address](Contact__Home Address.md) |  |
| [Work Address](Contact__Work Address.md) |  |

## Formalization for Address

| Property | Constraint |
|----------|------------|
| hasAddressType | only AddressType |
| hasBuilding | max 1 xsd::string |
| hasCity | max 1 city::City |
| hasCitySection | max 1 xsd::string |
| hasCountry | max 1 Country |
| hasPostalBox | max 1 xsd::string |
| hasPostalCode | max 1 xsd::string |
| hasProvince | max 1 State |
| hasStreet | max 1 xsd::string |
| hasStreetDirection | max 1 StreetDirection |
| hasStreetNumber | max 1 xsd::string |
| hasStreetType | max 1 StreetType |
| hasUnitNumber | max 1 xsd::string |
| maxStreetNumber | max 1 xsd::string |
| minStreetNumber | max 1 xsd::nonNegativeInteger |
| spatialLoc::hasLocation | max 1 spatialLoc::Location |
| subClassOf | ContactThing |
| subClassOf | ContactThing |
| wgs84::lat | max 1 xsd::decimal |
| wgs84::long | max 1 xsd::decimal |

