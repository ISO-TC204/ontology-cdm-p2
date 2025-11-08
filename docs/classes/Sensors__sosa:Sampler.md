# sosa:Sampler

EXAMPLE: A ball mill, diamond drill, hammer, hypodermic syringe and needle, image Sensor or a soil auger can all act as sampling devices (i.e., be Samplers). However, sometimes the distinction between the Sampler and the Sensor is not evident, as they are packaged as a unit. A Sampler need not be a physical device.

![sosa:Sampler Diagram](../diagrams/Sensors__sosa:Sampler.dot.svg)

<a href="../../diagrams/Sensors__sosa:Sampler.dot.svg">Open interactive sosa:Sampler diagram</a>

## Formalization for sosa:Sampler

| Property | Constraint |
|----------|------------|
| sosa:madeSampling | only sosa:Sampling |
| ssn:implements | min 1 owl::Thing |
| subClassOf | ssn:System |
| subClassOf | ssn:System |

