# sosa:Observation

EXAMPLE: The activity of estimating the intensity of an Earthquake using the Mercalli intensity scale is an Observation as is measuring the moment magnitude, i.e., the energy released by said earthquake.

![sosa:Observation Diagram](../diagrams/Sensors__sosa:Observation.dot.svg)

<a href="../../diagrams/Sensors__sosa:Observation.dot.svg">Open interactive sosa:Observation diagram</a>

## Formalization for sosa:Observation

| Property | Constraint |
|----------|------------|
| inverse sosa:isFeatureOfInterestOf | only sosa:FeatureOfInterest |
| inverse sosa:isFeatureOfInterestOf | exactly 1 owl::Thing |
| inverse sosa:isResultOf | min 1 owl::Thing |
| inverse sosa:isResultOf | only sosa:Result |
| inverse sosa:madeObservation | exactly 1 owl::Thing |
| inverse sosa:madeObservation | only sosa:Sensor |
| sosa:observedProperty | only sosa:ObservableProperty |
| sosa:observedProperty | exactly 1 owl::Thing |
| sosa:phenomenonTime | exactly 1 owl::Thing |
| sosa:resultTime | exactly 1 xsd:dateTime |
| sosa:usedProcedure | only sosa:Procedure |
| ssn:wasOriginatedBy | only ssn:Stimulus |
| ssn:wasOriginatedBy | exactly 1 owl::Thing |
| subClassOf | sensorsThing |
| subClassOf | sensorsThing |

