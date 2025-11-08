# cdmOrg:Employment

![cdmOrg:Employment Diagram](../diagrams/Organization__cdmOrg:Employment.dot.svg)

<a href="../../diagrams/Organization__cdmOrg:Employment.dot.svg">Open interactive cdmOrg:Employment diagram</a>

## Formalization for cdmOrg:Employment

| Property | Constraint |
|----------|------------|
| cdmOrg:employedAs | only cdmOrg:Occupation |
| cdmOrg:employedBy | some cdmOrg:Organization |
| cdmOrg:hasCompensation | some cdmOrg:Compensation |
| cdmOrg:hasEmploymentStatus | only cdmOrg:EmploymentStatus |
| subClassOf | cdmOrg:CityOrgOntologyThing |
| subClassOf | cdmOrg:CityOrgOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [cdm Org:Organization Agent](Organization__cdmOrg:OrganizationAgent.md) | cdmOrg:hasEmployment |

