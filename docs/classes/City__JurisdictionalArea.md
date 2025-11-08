# JurisdictionalArea

![JurisdictionalArea Diagram](../diagrams/City__JurisdictionalArea.dot.svg)

<a href="../../diagrams/City__JurisdictionalArea.dot.svg">Open interactive JurisdictionalArea diagram</a>

## Specializations of JurisdictionalArea

| Class | Description |
|-------|-------------|
| [City (City)](City__City.md) |  |
| [City Administrative Area (City)](City__CityAdministrativeArea.md) |  |

## Formalization for JurisdictionalArea

| Property | Constraint |
|----------|------------|
| administrativeAreaOf | only JurisdictionalArea |
| bylaw::hasBylaw | only bylaw::Bylaw |
| genericproperties::hasName | max 1 xsd::string |
| hasGovernment | only organization::GovernmentOrganization |
| inverse administrativeAreaOf | only JurisdictionalArea |
| landUse::hasLandArea | only landUse::LandArea |
| landUse::residentPopulation | max 1 i72::Population |
| subClassOf | CityOntologyThing |
| subClassOf | CityOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Jurisdictional Area (City)](City__JurisdictionalArea.md) | administrativeArea |
| [Jurisdictional Area (City)](City__JurisdictionalArea.md) | administrativeAreaOf |

