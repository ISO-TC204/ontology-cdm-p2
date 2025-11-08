# sosa:Procedure

NOTE: Many observations may be created via the same Procedure, the same way as many tables are assembled using the same instructions (as information objects, not their concrete realization).

EXAMPLE: The measured wind speed differs depending on the height of the sensor above the surface, e.g., due to friction. Consequently, procedures for measuring wind speed define a standard height for anemometers above ground, typically 10m for meteorological measures and 2m in Agrometeorology. This definition of height, sensor placement, and so forth are defined by the Procedure.

![sosa:Procedure Diagram](../diagrams/Sensors__sosa:Procedure.dot.svg)

<a href="../../diagrams/Sensors__sosa:Procedure.dot.svg">Open interactive sosa:Procedure diagram</a>

## Formalization for sosa:Procedure

| Property | Constraint |
|----------|------------|
| inverse ssn:implements | only ssn:System |
| ssn:hasInput | only ssn:Input |
| ssn:hasOutput | only ssn:Output |
| subClassOf | sensorsThing |
| subClassOf | sensorsThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Input](Sensors__Input.md) | Ncabef535767243458ea177feef7b73a2 |
| [Output](Sensors__Output.md) | N601e4c2bab174e60878c6c7b40e34aff |

