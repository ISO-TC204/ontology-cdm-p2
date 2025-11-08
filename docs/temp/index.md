# ontology-cdm-p2

## Building Ontology

A Building is a structure with some location in the urban system. The location of the Building in space may change due to construction, but the Parcel/Lot of land it is located on cannot.
There may be many different types (subclasses) of buildings, such as House, Apartment Building, Office Building, and so on.


This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Building](classes/Building__Building.md)
- [Building Facility](classes/Building__BuildingFacility.md)
- [Building Function](classes/Building__BuildingFunction.md)
- [Building Ontology Thing](classes/Building__BuildingOntologyThing.md)
- [Building Unit](classes/Building__BuildingUnit.md)
- [Building Use](classes/Building__BuildingUse.md)
- [schema:Postal Address (Building)](classes/Building__schema:PostalAddress.md)
- [Schema Org Thing (Building)](classes/Building__SchemaOrgThing.md)

The formal definition of these patterns is available in [OWL Syntax](Building.owl).

## Bylaw Pattern

“Municipal by-laws are public regulatory laws which apply in a certain area. The main difference between a by-law and a law passed by a national/federal or regional/state body is that a by-law is made by a non-sovereign body, which derives its authority from another governing body, and can only be made on a limited range of matters. A local council or municipal government derives its power to pass laws through a law of the national or regional government which specifies what things the town or city may regulate through by-laws. It is therefore a form of delegated legislation.” (Wikipedia, 2020)
“A municipal by-law is no different than any other law of the land, and can be enforced with penalties, challenged in court and must comply with higher levels of law. Municipal bylaws are often enforceable through the public justice system, and offenders can be charged with a criminal offence for breach of a bylaw.” (Alberta, 2017)
The intent of the Bylaw ontology is to capture the major components of a city bylaw, such as dates, geographic areas of application, penalties, etc. It is not intended to provide a legal semantics with which to codify a particular bylaw. The following three types of bylaws are represented in the Bylaw Ontology (Alberta, 2017): 
1.	Main bylaws; 
2.	Amending bylaws, which reflect material changes, in principle or substance, to an existing bylaw; and 
3.	Revision bylaws, which reflect limited changes to an existing bylaw.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Amending Bylaw](classes/Bylaw__AmendingBylaw.md)
- [Bylaw](classes/Bylaw__Bylaw.md)
- [Bylaw Ontology Thing](classes/Bylaw__BylawOntologyThing.md)
- [Clause](classes/Bylaw__Clause.md)
- [Definition](classes/Bylaw__Definition.md)
- [Law](classes/Bylaw__Law.md)
- [Main Bylaw](classes/Bylaw__MainBylaw.md)
- [Revision Bylaw](classes/Bylaw__RevisionBylaw.md)
- [Schedule](classes/Bylaw__Schedule.md)

The formal definition of these patterns is available in [OWL Syntax](Bylaw.owl).

## City Organization Ontology

Added for organizational purposes, to identify properties defined in the iCity-Organization ontology.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [cdm Org:Business Establishment](classes/Organization__cdmOrg:BusinessEstablishment.md)
- [cdm Org:Business Id](classes/Organization__cdmOrg:BusinessId.md)
- [cdm Org:City Org Ontology Thing](classes/Organization__cdmOrg:CityOrgOntologyThing.md)
- [cdm Org:Compensation](classes/Organization__cdmOrg:Compensation.md)
- [cdm Org:Employment](classes/Organization__cdmOrg:Employment.md)
- [cdm Org:Employment Status](classes/Organization__cdmOrg:EmploymentStatus.md)
- [cdm Org:For Profit Organization](classes/Organization__cdmOrg:ForProfitOrganization.md)
- [cdm Org:Goal](classes/Organization__cdmOrg:Goal.md)
- [cdm Org:Government Organization](classes/Organization__cdmOrg:GovernmentOrganization.md)
- [cdm Org:Industry Type](classes/Organization__cdmOrg:IndustryType.md)
- [cdm Org:Non Profit Organization](classes/Organization__cdmOrg:NonProfitOrganization.md)
- [cdm Org:Occupation](classes/Organization__cdmOrg:Occupation.md)
- [cdm Org:Operation](classes/Organization__cdmOrg:Operation.md)
- [cdm Org:Organization](classes/Organization__cdmOrg:Organization.md)
- [cdm Org:Organization Agent](classes/Organization__cdmOrg:OrganizationAgent.md)
- [cdm Org:Role](classes/Organization__cdmOrg:Role.md)
- [cdm Org:Salary](classes/Organization__cdmOrg:Salary.md)
- [cdm Org:Wage](classes/Organization__cdmOrg:Wage.md)
- [city:Jurisdictional Area](classes/Organization__city:JurisdictionalArea.md)
- [city Service:Program](classes/Organization__cityService:Program.md)
- [city Units:Monetary Value](classes/Organization__cityUnits:MonetaryValue.md)
- [contact:/Address](classes/Organization__contact:/Address.md)
- [contact:/Phone Number](classes/Organization__contact:/PhoneNumber.md)
- [schema:Postal Address (Organization)](classes/Organization__schema:PostalAddress.md)

The formal definition of these patterns is available in [OWL Syntax](Organization.owl).

## City Pattern

The City pattern captures basic information about the geospatial aspects of the city.  In particular it represents the different ways in which the city is administratively divided.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [bylaw:Bylaw](classes/City__bylaw:Bylaw.md)
- [City](classes/City__City.md)
- [City Administrative Area](classes/City__CityAdministrativeArea.md)
- [City Ontology Thing](classes/City__CityOntologyThing.md)
- [i72:City](classes/City__i72:City.md)
- [i72:Population (City)](classes/City__i72:Population.md)
- [Jurisdictional Area](classes/City__JurisdictionalArea.md)

The formal definition of these patterns is available in [OWL Syntax](City.owl).

## City Resident Pattern

As different cities have different definitions of who is that city’s Resident, the City Resident Pattern must contain the properties required by each.  Central to all of the definitions is the concept of residing. Variously referred to as a home or domicile in which the resident spends significant amounts of time.  They may own it, rent it or just stay in it.  Legally, “reside means to dwell permanently or continuously. It expresses an idea that a person keeps or returns to a particular dwelling place as his fixed, settled, or legal abode. The meaning of reside implies a continuous arrangement” ; reside has both a temporal and spatial dimension. The city of Toronto’s definition of a city resident includes the concept of owning property or owning or operating a business in the city. For Beijing, nationality is a unique aspect.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [City Resident](classes/CityResident__CityResident.md)
- [City Resident Ontology Thing](classes/CityResident__CityResidentOntologyThing.md)
- [Controlled Entity](classes/CityResident__ControlledEntity.md)
- [Entity Operation](classes/CityResident__EntityOperation.md)
- [Entity Ownership](classes/CityResident__EntityOwnership.md)
- [Home Type](classes/CityResident__HomeType.md)
- [Residence](classes/CityResident__Residence.md)
- [Residential Relationship](classes/CityResident__ResidentialRelationship.md)

The formal definition of these patterns is available in [OWL Syntax](CityResident.owl).

## City Service Pattern

Cities provide a variety of services to residents and businesses, including health and social services. The city service ontology, is based on the Canadian Government Reference Model (CGRM). See Wiseman, R. (2015). Canadian Governments Reference Models. In Service Systems Science (pp. 109-128). Springer, Tokyo.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Catchment Area Type](classes/CityService__CatchmentAreaType.md)
- [City Service Ontology Thing](classes/CityService__CityServiceOntologyThing.md)
- [Impact Direction](classes/CityService__ImpactDirection.md)
- [Importance](classes/CityService__Importance.md)
- [Input](classes/CityService__Input.md)
- [Outcome](classes/CityService__Outcome.md)
- [Output](classes/CityService__Output.md)
- [Program](classes/CityService__Program.md)
- [Service](classes/CityService__Service.md)
- [Stakeholder](classes/CityService__Stakeholder.md)

The formal definition of these patterns is available in [OWL Syntax](CityService.owl).

## Code Pattern

The Code Pattern provides a structure to address the challenge of value enumeration with a general approach. In city data there are many classes of things that are intended to be instantiated using a set list of values (e.g., classification systems), however these values may change based on application or context. 
The Code Pattern introduces a generic set of classes and properties that can be used to extend such classes to define various classification systems in an integrated way.
Instead of enumerating value sets for classes, values can be defined with an associated Code that specifies additional metadata about the value and its origins.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [cdm Org Struct:Organization](classes/Code__cdmOrgStruct:Organization.md)
- [Code](classes/Code__Code.md)
- [Code Ontology Thing](classes/Code__CodeOntologyThing.md)

The formal definition of these patterns is available in [OWL Syntax](Code.owl).

## Contact Pattern

Properties that define the hours of operation of the contact.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Address](classes/Contact__Address.md)
- [Address Type](classes/Contact__AddressType.md)
- [Cell Number](classes/Contact__CellNumber.md)
- [city:City](classes/Contact__city:City.md)
- [Contact Thing](classes/Contact__ContactThing.md)
- [Cottage Address](classes/Contact__CottageAddress.md)
- [Country](classes/Contact__Country.md)
- [Fax Number](classes/Contact__FaxNumber.md)
- [Home Address](classes/Contact__HomeAddress.md)
- [Home Number](classes/Contact__HomeNumber.md)
- [Hours Of Operation](classes/Contact__HoursOfOperation.md)
- [Phone Number](classes/Contact__PhoneNumber.md)
- [Phone Type](classes/Contact__PhoneType.md)
- [schema:Geo Coordinates](classes/Contact__schema:GeoCoordinates.md)
- [Schema Org Thing (Contact)](classes/Contact__SchemaOrgThing.md)
- [State](classes/Contact__State.md)
- [Street Direction](classes/Contact__StreetDirection.md)
- [Street Type](classes/Contact__StreetType.md)
- [Toll Free Number](classes/Contact__TollFreeNumber.md)
- [Work Address](classes/Contact__WorkAddress.md)
- [Work Number](classes/Contact__WorkNumber.md)

The formal definition of these patterns is available in [OWL Syntax](Contact.owl).

## Contract Pattern

A contract is a legal document that specifies some agreement(s) between two or more parties. The aim of the Contract Ontology is not to formalize the semantics of all possible involved legal concepts, but rather to enable to representation of the general structure and contents of a particular contract. The Contract Ontology adopts the definition of Contract specified in the Financial Business Ontology (FIBO) [8] specified at: https://spec.edmcouncil.org/fibo/ontology/FND/Agreements/Contracts/ with a key modification that a Contract is defined as a type of Document and is distinct from an Agreement (not a subclass, as specified in FIBO).

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Condition Precedent](classes/Contract__ConditionPrecedent.md)
- [Contract](classes/Contract__Contract.md)
- [Contract Ontology Thing](classes/Contract__ContractOntologyThing.md)
- [Contractual Commitment](classes/Contract__ContractualCommitment.md)
- [Contractual Definition](classes/Contract__ContractualDefinition.md)
- [Contractual Element](classes/Contract__ContractualElement.md)
- [Non Binding Term](classes/Contract__NonBindingTerm.md)
- [Representation](classes/Contract__Representation.md)
- [Warranty](classes/Contract__Warranty.md)

The formal definition of these patterns is available in [OWL Syntax](Contract.owl).

## Household Pattern

The Household ontology defines the classes: Household, Family, and DwellingUnit. These definitions serve as a basis which may be extended for more specific applications such as a surveys and simulations.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [city Resident:Residence](classes/Household__cityResident:Residence.md)
- [Household](classes/Household__Household.md)
- [Household Ontology Thing](classes/Household__HouseholdOntologyThing.md)
- [schema:Postal Address (Household)](classes/Household__schema:PostalAddress.md)

The formal definition of these patterns is available in [OWL Syntax](Household.owl).

## Infrastructure Pattern

The Infrastructure pattern defines the concepts needed to capture various types of city infrastructure, such as buildings and roads. The Infrastructure pattern reuses the Spatial Location pattern (from ISO 5087-1) in order to capture the location of these infrastructure elements.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Infrastructure Element](classes/Infrastructure__InfrastructureElement.md)
- [Infrastructure Ontology Thing](classes/Infrastructure__InfrastructureOntologyThing.md)

The formal definition of these patterns is available in [OWL Syntax](Infrastructure.owl).

## Land Use Ontology

The Land Use Pattern captures concepts related to land use and cover over time. 
Land Use Classifications provide a means of describing the land cover/use in a standard way. Various classification systems are used to identify types of land use. Currently, we include LBCS, CLUMP, and AAFC.
The ontology reuses and extends the Land Based Classification Standards (LBCS) Ontology  presented by (Montenegro, Gomes, Urbano, and Duarte, 2011) for this purpose.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [city Units:Area](classes/LandUse__cityUnits:Area.md)
- [Employed Population](classes/LandUse__EmployedPopulation.md)
- [i72:Feature](classes/LandUse__i72:Feature.md)
- [i72:Population (LandUse)](classes/LandUse__i72:Population.md)
- [Land Area](classes/LandUse__LandArea.md)
- [Land Use Classification](classes/LandUse__LandUseClassification.md)
- [Land Use Ontology Thing](classes/LandUse__LandUseOntologyThing.md)
- [Parcel](classes/LandUse__Parcel.md)
- [Resident Population](classes/LandUse__ResidentPopulation.md)
- [Traffic Zone](classes/LandUse__TrafficZone.md)

The formal definition of these patterns is available in [OWL Syntax](LandUse.owl).

## Person Ontology

Ontology to capture concepts related to Persons.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [contact:Phone Number](classes/Person__contact:PhoneNumber.md)
- [person:Citizenship](classes/Person__person:Citizenship.md)
- [person:Education](classes/Person__person:Education.md)
- [person:Gender](classes/Person__person:Gender.md)
- [person:ID Type](classes/Person__person:IDType.md)
- [person:Person](classes/Person__person:Person.md)
- [person:Person Id](classes/Person__person:PersonId.md)
- [person:Person Name](classes/Person__person:PersonName.md)
- [person:Person Ontology Thing](classes/Person__person:PersonOntologyThing.md)
- [person:Qualification](classes/Person__person:Qualification.md)
- [person:Schema Org Thing](classes/Person__person:SchemaOrgThing.md)
- [person:Sex](classes/Person__person:Sex.md)
- [person:Skill](classes/Person__person:Skill.md)

The formal definition of these patterns is available in [OWL Syntax](Person.owl).

## SSN Ontology

Ontology to capture concepts related to sensors and their observations. Directly reuses the SSN Ontology; adds classes and properties for organization of terms.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [foaf:Agent](classes/Sensors__foaf:Agent.md)
- [sensors Thing](classes/Sensors__sensorsThing.md)
- [sosa:Actuatable Property](classes/Sensors__sosa:ActuatableProperty.md)
- [sosa:Actuation](classes/Sensors__sosa:Actuation.md)
- [sosa:Actuator](classes/Sensors__sosa:Actuator.md)
- [sosa:Feature Of Interest](classes/Sensors__sosa:FeatureOfInterest.md)
- [sosa:Observable Property](classes/Sensors__sosa:ObservableProperty.md)
- [sosa:Observation](classes/Sensors__sosa:Observation.md)
- [sosa:Platform](classes/Sensors__sosa:Platform.md)
- [sosa:Procedure](classes/Sensors__sosa:Procedure.md)
- [sosa:Result](classes/Sensors__sosa:Result.md)
- [sosa:Sample](classes/Sensors__sosa:Sample.md)
- [sosa:Sampler](classes/Sensors__sosa:Sampler.md)
- [sosa:Sampling](classes/Sensors__sosa:Sampling.md)
- [sosa:Sensor](classes/Sensors__sosa:Sensor.md)
- [ssn:Deployment](classes/Sensors__ssn:Deployment.md)
- [ssn:Input](classes/Sensors__ssn:Input.md)
- [ssn:Output](classes/Sensors__ssn:Output.md)
- [ssn:Property](classes/Sensors__ssn:Property.md)
- [ssn:Stimulus](classes/Sensors__ssn:Stimulus.md)
- [ssn:System](classes/Sensors__ssn:System.md)
- [time:Temporal Entity](classes/Sensors__time:TemporalEntity.md)
- [voaf:Vocabulary](classes/Sensors__voaf:Vocabulary.md)

The formal definition of these patterns is available in [OWL Syntax](Sensors.owl).

## Transportation Infrastructure Pattern

The Transportation Infrastructure pattern defines the concepts that are relevant in describing the physical transportation infrastructure and their characteristics. This includes the concepts of a Road, Bridge, and Tunnel. The Infrastructure Pattern is reused here, as these transportation structures are all defined as types of (subclasses) Infrastructure Elements.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Bridge](classes/TransportationInfrastructure__Bridge.md)
- [Bridge Segment](classes/TransportationInfrastructure__BridgeSegment.md)
- [Rail Line](classes/TransportationInfrastructure__RailLine.md)
- [Rail Line Segment](classes/TransportationInfrastructure__RailLineSegment.md)
- [Road](classes/TransportationInfrastructure__Road.md)
- [Road Segment](classes/TransportationInfrastructure__RoadSegment.md)
- [Transportation Infrastructure Ontology Thing](classes/TransportationInfrastructure__TransportationInfrastructureOntologyThing.md)
- [Tunnel](classes/TransportationInfrastructure__Tunnel.md)
- [Tunnel Segment](classes/TransportationInfrastructure__TunnelSegment.md)

The formal definition of these patterns is available in [OWL Syntax](TransportationInfrastructure.owl).

