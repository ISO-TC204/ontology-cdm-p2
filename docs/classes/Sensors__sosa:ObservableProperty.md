# sosa:ObservableProperty

EXAMPLE: The height of a tree, the depth of a water body, or the temperature of a surface are examples of observable properties, while the value of a classic car is not (directly) observable but asserted.

![sosa:ObservableProperty Diagram](../diagrams/Sensors__sosa:ObservableProperty.dot.svg)

<a href="../../diagrams/Sensors__sosa:ObservableProperty.dot.svg">Open interactive sosa:ObservableProperty diagram</a>

## Formalization for sosa:ObservableProperty

| Property | Constraint |
|----------|------------|
| inverse sosa:observedProperty | only sosa:Observation |
| inverse sosa:observes | only sosa:Sensor |
| inverse ssn:isProxyFor | only ssn:Stimulus |
| subClassOf | ssn:Property |
| subClassOf | ssn:Property |

