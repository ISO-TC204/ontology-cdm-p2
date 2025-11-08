# cdmOrg:BusinessEstablishment

![cdmOrg:BusinessEstablishment Diagram](../diagrams/Organization__cdmOrg:BusinessEstablishment.dot.svg)

<a href="../../diagrams/Organization__cdmOrg:BusinessEstablishment.dot.svg">Open interactive cdmOrg:BusinessEstablishment diagram</a>

## Formalization for cdmOrg:BusinessEstablishment

| Property | Constraint |
|----------|------------|
| contact:hasAddress | only contact:/Address |
| spatialLoc:hasLocation | max 1 spatialLoc:Location |
| subClassOf | cdmOrg:CityOrgOntologyThing |
| subClassOf | cdmOrg:CityOrgOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [cdm Org:For Profit Organization](Organization__cdmOrg:ForProfitOrganization.md) | cdmOrg:hasEstablishment |

