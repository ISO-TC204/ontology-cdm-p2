# ssn:Deployment

EXAMPLE: For example, a temperature Sensor deployed on a wall, or a whole network of Sensors deployed for an Observation campaign.

![ssn:Deployment Diagram](../diagrams/Sensors__ssn:Deployment.dot.svg)

<a href="../../diagrams/Sensors__ssn:Deployment.dot.svg">Open interactive ssn:Deployment diagram</a>

## Formalization for ssn:Deployment

| Property | Constraint |
|----------|------------|
| inverse ssn:hasDeployment | only ssn:System |
| inverse ssn:inDeployment | only sosa:Platform |
| ssn:forProperty | only ssn:Property |
| subClassOf | sensorsThing |
| subClassOf | sensorsThing |

