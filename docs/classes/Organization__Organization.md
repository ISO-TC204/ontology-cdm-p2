# Organization

![Organization Diagram](../diagrams/Organization__Organization.dot.svg)

<a href="../../diagrams/Organization__Organization.dot.svg">Open interactive Organization diagram</a>

## Specializations of Organization

| Class | Description |
|-------|-------------|
| [For Profit Organization (Organization)](Organization__ForProfitOrganization.md) |  |
| [Government Organization (Organization)](Organization__GovernmentOrganization.md) |  |
| [Non Profit Organization (Organization)](Organization__NonProfitOrganization.md) |  |

## Formalization for Organization

| Property | Constraint |
|----------|------------|
| contact::hasTelephone | only contact::PhoneNumber |
| hasGoal | only Goal |
| operatingHours | only Operation |
| orgAddress | only contact::Address |
| spatialLoc::hasLocation | only spatialLoc::Location |
| subClassOf | CityOrgOntologyThing |
| subClassOf | cdmOrgStruct::Organization |
| subClassOf | CityOrgOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Employment (Organization)](Organization__Employment.md) | employedBy |
| [Organization Agent (Organization)](Organization__OrganizationAgent.md) | org::memberOf |

