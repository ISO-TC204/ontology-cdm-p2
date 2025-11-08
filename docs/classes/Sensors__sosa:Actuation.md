# sosa:Actuation

EXAMPLE: The activity of automatically closing a window if the temperature in a room drops below 20 degree Celsius. The activity is the Actuation and the device that closes the window is the Actuator. The Procedure is the rule, plan, or specification that defines the conditions that triggers the Actuation, here a drop in temperature. 

![sosa:Actuation Diagram](../diagrams/Sensors__sosa:Actuation.dot.svg)

<a href="../../diagrams/Sensors__sosa:Actuation.dot.svg">Open interactive sosa:Actuation diagram</a>

## Formalization for sosa:Actuation

| Property | Constraint |
|----------|------------|
| inverse sosa:isActedOnBy | min 1 owl::Thing |
| inverse sosa:isActedOnBy | only sosa:ActuatableProperty |
| inverse sosa:isFeatureOfInterestOf | only sosa:FeatureOfInterest |
| inverse sosa:isFeatureOfInterestOf | exactly 1 owl::Thing |
| inverse sosa:isResultOf | only sosa:Result |
| inverse sosa:isResultOf | min 1 owl::Thing |
| sosa:madeByActuator | exactly 1 owl::Thing |
| sosa:madeByActuator | only sosa:Actuator |
| sosa:resultTime | exactly 1 xsd:dateTime |
| sosa:usedProcedure | only sosa:Procedure |
| subClassOf | sensorsThing |
| subClassOf | sensorsThing |

