# Phone Number

![Phone Number Diagram](../diagrams/Contact__Phone Number.dot.svg)

<a href="../../diagrams/Contact__Phone Number.dot.svg">Open interactive Phone Number diagram</a>

## Specializations of Phone Number

| Class | Description |
|-------|-------------|
| [Fax Telephone Number](Contact__Fax Telephone Number.md) |  |
| [Home Telephone Number](Contact__Home Telephone Number.md) |  |
| [Mobile Telephone Number](Contact__Mobile Telephone Number.md) |  |
| [Toll  Free Telephone Number](Contact__Toll  Free Telephone Number.md) |  |
| [Work Telephone Number](Contact__Work Telephone Number.md) |  |

## Formalization for Phone Number

| Property | Constraint |
|----------|------------|
| hasAreaCode | exactly 1 xsd::nonNegativeInteger |
| hasCountryCode | exactly 1 xsd::nonNegativeInteger |
| hasPhoneNumber | exactly 1 xsd::nonNegativeInteger |
| hasPhoneType | exactly 1 PhoneType |
| subClassOf | ContactThing |
| subClassOf | ContactThing |

