# sosa:Sampling

EXAMPLE: Selecting a subset of a population.

![sosa:Sampling Diagram](../diagrams/Sensors__sosa:Sampling.dot.svg)

<a href="../../diagrams/Sensors__sosa:Sampling.dot.svg">Open interactive sosa:Sampling diagram</a>

## Formalization for sosa:Sampling

| Property | Constraint |
|----------|------------|
| inverse sosa:isFeatureOfInterestOf | only sosa:FeatureOfInterest |
| inverse sosa:isFeatureOfInterestOf | exactly 1 owl::Thing |
| inverse sosa:isResultOf | only sosa:Sample |
| inverse sosa:isResultOf | min 1 owl::Thing |
| inverse sosa:madeSampling | only sosa:Sampler |
| inverse sosa:madeSampling | exactly 1 owl::Thing |
| sosa:resultTime | exactly 1 xsd:dateTime |
| sosa:usedProcedure | only sosa:Procedure |
| subClassOf | sensorsThing |
| subClassOf | sensorsThing |

