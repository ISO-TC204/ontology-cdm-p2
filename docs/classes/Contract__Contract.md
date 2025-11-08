# Contract

![Contract Diagram](../diagrams/Contract__Contract.dot.svg)

<a href="../../diagrams/Contract__Contract.dot.svg">Open interactive Contract diagram</a>

## Formalization for Contract

| Property | Constraint |
|----------|------------|
| executedOn | only time::TemporalEntity |
| hasContractualElement | some ContractualElement |
| hasParty | min 2 (cdmOrg::Organization or person::Person) |
| hasSignatory | min 2 person::Person |
| isValidFor | only time::Interval |
| specifiesAgreement | some agreement::Agreement |
| subClassOf | ContractOntologyThing |
| subClassOf | ContractOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Contractual Element (Contract)](Contract__ContractualElement.md) | Nfbabd1f2777f4cb68bfd7b81e6feec0a |

