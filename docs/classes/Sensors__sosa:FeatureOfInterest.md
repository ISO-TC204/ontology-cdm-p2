# sosa:FeatureOfInterest

EXAMPLE: When measuring the height of a tree, the height is the observed ObservableProperty, 20m may be the Result of the Observation, and the tree is the FeatureOfInterest. A window is a FeatureOfInterest for an automatic window control Actuator.

![sosa:FeatureOfInterest Diagram](../diagrams/Sensors__sosa:FeatureOfInterest.dot.svg)

<a href="../../diagrams/Sensors__sosa:FeatureOfInterest.dot.svg">Open interactive sosa:FeatureOfInterest diagram</a>

## Formalization for sosa:FeatureOfInterest

| Property | Constraint |
|----------|------------|
| inverse sosa:isSampleOf | only sosa:Sample |
| inverse ssn:isPropertyOf | only ssn:Property |
| inverse ssn:isPropertyOf | min 1 owl::Thing |
| subClassOf | sensorsThing |
| subClassOf | sensorsThing |

