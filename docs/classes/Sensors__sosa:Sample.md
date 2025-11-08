# sosa:Sample

NOTE: A transient sample, such as a ships-track or flight-line, might be identified and described, but is unlikely to be revisited exactly.

EXAMPLE: A 'station' is essentially an identifiable locality where a sensor system or Procedure may be deployed and an observation made. In the context of the observation model, it connotes the 'world in the vicinity of the station', so the observed properties relate to the physical medium at the station, and not to any physical artifact such as a mooring, buoy, benchmark, monument, well, etc.

![sosa:Sample Diagram](../diagrams/Sensors__sosa:Sample.dot.svg)

<a href="../../diagrams/Sensors__sosa:Sample.dot.svg">Open interactive sosa:Sample diagram</a>

## Formalization for sosa:Sample

| Property | Constraint |
|----------|------------|
| sosa:isResultOf | only sosa:Sampling |
| sosa:isResultOf | min 1 owl::Thing |
| sosa:isSampleOf | only sosa:FeatureOfInterest |
| sosa:isSampleOf | min 1 owl::Thing |
| subClassOf | sosa:Result |
| subClassOf | sosa:FeatureOfInterest |
| subClassOf | sosa:Result |
| subClassOf | sosa:FeatureOfInterest |

