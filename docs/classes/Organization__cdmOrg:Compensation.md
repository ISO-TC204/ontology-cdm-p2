# cdmOrg:Compensation

![cdmOrg:Compensation Diagram](../diagrams/Organization__cdmOrg:Compensation.dot.svg)

<a href="../../diagrams/Organization__cdmOrg:Compensation.dot.svg">Open interactive cdmOrg:Compensation diagram</a>

## Specializations of cdmOrg:Compensation

| Class | Description |
|-------|-------------|
| [cdm Org:Salary](Organization__cdmOrg:Salary.md) |  |
| [cdm Org:Wage](Organization__cdmOrg:Wage.md) |  |

## Formalization for cdmOrg:Compensation

| Property | Constraint |
|----------|------------|
| cdmOrg:hasPay | max 1 cityUnits:MonetaryValue |
| subClassOf | cdmOrg:CityOrgOntologyThing |
| subClassOf | cdmOrg:CityOrgOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [cdm Org:Employment](Organization__cdmOrg:Employment.md) | cdmOrg:hasCompensation |

