# cdmOrg:Organization

![cdmOrg:Organization Diagram](../diagrams/Organization__cdmOrg:Organization.dot.svg)

<a href="../../diagrams/Organization__cdmOrg:Organization.dot.svg">Open interactive cdmOrg:Organization diagram</a>

## Specializations of cdmOrg:Organization

| Class | Description |
|-------|-------------|
| [cdm Org:For Profit Organization](Organization__cdmOrg:ForProfitOrganization.md) |  |
| [cdm Org:Government Organization](Organization__cdmOrg:GovernmentOrganization.md) |  |
| [cdm Org:Non Profit Organization](Organization__cdmOrg:NonProfitOrganization.md) |  |

## Formalization for cdmOrg:Organization

| Property | Constraint |
|----------|------------|
| cdmOrg:hasGoal | only cdmOrg:Goal |
| cdmOrg:operatingHours | only cdmOrg:Operation |
| cdmOrg:orgAddress | only contact:/Address |
| contact:/hasTelephone | only contact:/PhoneNumber |
| spatialLoc:hasLocation | only spatialLoc:Location |
| subClassOf | cdmOrg:CityOrgOntologyThing |
| subClassOf | cdmOrg:CityOrgOntologyThing |
| subClassOf | cdmOrgStruct:Organization |

## Used by classes

| Class | Property |
|-------|----------|
| [cdm Org:Employment](Organization__cdmOrg:Employment.md) | cdmOrg:employedBy |
| [cdm Org:Organization Agent](Organization__cdmOrg:OrganizationAgent.md) | org:memberOf |

