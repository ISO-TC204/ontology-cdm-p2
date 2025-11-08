# InfrastructureElement

![InfrastructureElement Diagram](../diagrams/Infrastructure__InfrastructureElement.dot.svg)

<a href="../../diagrams/Infrastructure__InfrastructureElement.dot.svg">Open interactive InfrastructureElement diagram</a>

## Formalization for InfrastructureElement

| Property | Constraint |
|----------|------------|
| contact::hasAddress | only contact::Address |
| genProp::hasDescription | only xsd::string |
| genProp::hasIdentifier | only xsd::string |
| genProp::hasName | only xsd::string |
| i72::hasValue | only cityUnits::MonetaryValue |
| partwhole::hasProperPart | only InfrastructureElement |
| spatialLoc::hasLocation | only spatialLoc::Location |
| subClassOf | InfrastructureOntologyThing |
| subClassOf | InfrastructureOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Infrastructure Element (Infrastructure)](Infrastructure__InfrastructureElement.md) | partwhole::hasProperPart |

