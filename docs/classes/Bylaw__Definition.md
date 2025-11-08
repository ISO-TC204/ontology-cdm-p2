# Definition

![Definition Diagram](../diagrams/Bylaw__Definition.dot.svg)

<a href="../../diagrams/Bylaw__Definition.dot.svg">Open interactive Definition diagram</a>

## Formalization for Definition

| Property | Constraint |
|----------|------------|
| genProp::hasDescription | max 1 xsd::string |
| genProp::hasName | max 1 xsd::string |
| partwhole::properPartOf | exactly 1 Law |
| subClassOf | BylawOntologyThing |
| subClassOf | BylawOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Law (Bylaw)](Bylaw__Law.md) | hasDefinition |

