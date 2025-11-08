# sosa:Actuator

EXAMPLE: A window actuator for automatic window control, i.e., opening or closing the window.

![sosa:Actuator Diagram](../diagrams/Sensors__sosa:Actuator.dot.svg)

<a href="../../diagrams/Sensors__sosa:Actuator.dot.svg">Open interactive sosa:Actuator diagram</a>

## Formalization for sosa:Actuator

| Property | Constraint |
|----------|------------|
| inverse sosa:madeByActuator | only sosa:Actuation |
| ssn:forProperty | only sosa:ActuatableProperty |
| ssn:implements | min 1 owl::Thing |
| subClassOf | ssn:System |
| subClassOf | ssn:System |

