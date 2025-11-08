# sosa:Sensor

EXAMPLE: Accelerometers, gyroscopes, barometers, magnetometers, and so forth are Sensors that are typically mounted on a modern smart phone (which acts as Platform). Other examples of sensors include the human eyes.

![sosa:Sensor Diagram](../diagrams/Sensors__sosa:Sensor.dot.svg)

<a href="../../diagrams/Sensors__sosa:Sensor.dot.svg">Open interactive sosa:Sensor diagram</a>

## Formalization for sosa:Sensor

| Property | Constraint |
|----------|------------|
| sosa:madeObservation | only sosa:Observation |
| sosa:observes | only sosa:ObservableProperty |
| ssn:detects | only ssn:Stimulus |
| ssn:implements | min 1 owl::Thing |
| subClassOf | ssn:System |
| subClassOf | ssn:System |

