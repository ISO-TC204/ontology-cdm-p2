# sosa:Platform

EXAMPLE: A post, buoy, vehicle, ship, aircraft, satellite, cell-phone, human or animal may act as platforms for (technical or biological) sensors or actuators.

![sosa:Platform Diagram](../diagrams/Sensors__sosa:Platform.dot.svg)

<a href="../../diagrams/Sensors__sosa:Platform.dot.svg">Open interactive sosa:Platform diagram</a>

## Formalization for sosa:Platform

| Property | Constraint |
|----------|------------|
| inverse sosa:isHostedBy | only ssn:System |
| ssn:inDeployment | only ssn:Deployment |
| subClassOf | sensorsThing |
| subClassOf | sensorsThing |

