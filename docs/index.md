# ontology-cdm-p2

## Building Ontology

A Building is a structure with some location in the urban system. The location of the Building in space may change due to construction, but the Parcel/Lot of land it is located on cannot.
There may be many different types (subclasses) of buildings, such as House, Apartment Building, Office Building, and so on.


This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Building (Building)](classes/Building__Building.md)
- [Building Facility (Building)](classes/Building__BuildingFacility.md)
- [Building Function (Building)](classes/Building__BuildingFunction.md)
- [Building Ontology Thing (Building)](classes/Building__BuildingOntologyThing.md)
- [Building Unit (Building)](classes/Building__BuildingUnit.md)
- [Building Use (Building)](classes/Building__BuildingUse.md)
- [Construction Status (Building)](classes/Building__ConstructionStatus.md)
- [Facility (Building)](classes/Building__Facility.md)
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

- [Amending Bylaw (Bylaw)](classes/Bylaw__AmendingBylaw.md)
- [Bylaw (Bylaw)](classes/Bylaw__Bylaw.md)
- [Bylaw Ontology Thing (Bylaw)](classes/Bylaw__BylawOntologyThing.md)
- [Clause (Bylaw)](classes/Bylaw__Clause.md)
- [Definition (Bylaw)](classes/Bylaw__Definition.md)
- [Law (Bylaw)](classes/Bylaw__Law.md)
- [Main Bylaw (Bylaw)](classes/Bylaw__MainBylaw.md)
- [Revision Bylaw (Bylaw)](classes/Bylaw__RevisionBylaw.md)
- [Schedule (Bylaw)](classes/Bylaw__Schedule.md)

The formal definition of these patterns is available in [OWL Syntax](Bylaw.owl).

## City Organization Ontology

Added for organizational purposes, to identify properties defined in the iCity-Organization ontology.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Business Establishment (Organization)](classes/Organization__BusinessEstablishment.md)
- [Business Id (Organization)](classes/Organization__BusinessId.md)
- [City Org Ontology Thing (Organization)](classes/Organization__CityOrgOntologyThing.md)
- [Compensation (Organization)](classes/Organization__Compensation.md)
- [Employment (Organization)](classes/Organization__Employment.md)
- [Employment Status (Organization)](classes/Organization__EmploymentStatus.md)
- [For Profit Organization (Organization)](classes/Organization__ForProfitOrganization.md)
- [Goal (Organization)](classes/Organization__Goal.md)
- [Government Organization (Organization)](classes/Organization__GovernmentOrganization.md)
- [Industry Type (Organization)](classes/Organization__IndustryType.md)
- [Non Profit Organization (Organization)](classes/Organization__NonProfitOrganization.md)
- [Occupation (Organization)](classes/Organization__Occupation.md)
- [Operation (Organization)](classes/Organization__Operation.md)
- [Organization (Organization)](classes/Organization__Organization.md)
- [Organization Agent (Organization)](classes/Organization__OrganizationAgent.md)
- [Role (Organization)](classes/Organization__Role.md)
- [Salary (Organization)](classes/Organization__Salary.md)
- [Wage (Organization)](classes/Organization__Wage.md)

The formal definition of these patterns is available in [OWL Syntax](Organization.owl).

## City Pattern

The City pattern captures basic information about the geospatial aspects of the city.  In particular it represents the different ways in which the city is administratively divided.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [City (City)](classes/City__City.md)
- [City Administrative Area (City)](classes/City__CityAdministrativeArea.md)
- [City Ontology Thing (City)](classes/City__CityOntologyThing.md)
- [Jurisdictional Area (City)](classes/City__JurisdictionalArea.md)

The formal definition of these patterns is available in [OWL Syntax](City.owl).

## City Resident Pattern

As different cities have different definitions of who is that city’s Resident, the City Resident Pattern must contain the properties required by each.  Central to all of the definitions is the concept of residing. Variously referred to as a home or domicile in which the resident spends significant amounts of time.  They may own it, rent it or just stay in it.  Legally, “reside means to dwell permanently or continuously. It expresses an idea that a person keeps or returns to a particular dwelling place as his fixed, settled, or legal abode. The meaning of reside implies a continuous arrangement” ; reside has both a temporal and spatial dimension. The city of Toronto’s definition of a city resident includes the concept of owning property or owning or operating a business in the city. For Beijing, nationality is a unique aspect.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [City Resident (CityResident)](classes/CityResident__CityResident.md)
- [City Resident Ontology Thing (CityResident)](classes/CityResident__CityResidentOntologyThing.md)
- [Controlled Entity (CityResident)](classes/CityResident__ControlledEntity.md)
- [Entity Operation (CityResident)](classes/CityResident__EntityOperation.md)
- [Entity Ownership (CityResident)](classes/CityResident__EntityOwnership.md)
- [Home Type (CityResident)](classes/CityResident__HomeType.md)
- [Residence (CityResident)](classes/CityResident__Residence.md)
- [Residential Relationship (CityResident)](classes/CityResident__ResidentialRelationship.md)

The formal definition of these patterns is available in [OWL Syntax](CityResident.owl).

## City Service Pattern

Cities provide a variety of services to residents and businesses, including health and social services. The city service ontology, is based on the Canadian Government Reference Model (CGRM). See Wiseman, R. (2015). Canadian Governments Reference Models. In Service Systems Science (pp. 109-128). Springer, Tokyo.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Catchment Area Type (CityService)](classes/CityService__CatchmentAreaType.md)
- [City Service Ontology Thing (CityService)](classes/CityService__CityServiceOntologyThing.md)
- [Impact Direction (CityService)](classes/CityService__ImpactDirection.md)
- [Importance (CityService)](classes/CityService__Importance.md)
- [Input (CityService)](classes/CityService__Input.md)
- [Outcome (CityService)](classes/CityService__Outcome.md)
- [Output (CityService)](classes/CityService__Output.md)
- [Program (CityService)](classes/CityService__Program.md)
- [Service (CityService)](classes/CityService__Service.md)
- [Stakeholder (CityService)](classes/CityService__Stakeholder.md)

The formal definition of these patterns is available in [OWL Syntax](CityService.owl).

## Code Pattern

The Code Pattern provides a structure to address the challenge of value enumeration with a general approach. In city data there are many classes of things that are intended to be instantiated using a set list of values (e.g., classification systems), however these values may change based on application or context. 
The Code Pattern introduces a generic set of classes and properties that can be used to extend such classes to define various classification systems in an integrated way.
Instead of enumerating value sets for classes, values can be defined with an associated Code that specifies additional metadata about the value and its origins.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Code (Code)](classes/Code__Code.md)
- [Code Ontology Thing (Code)](classes/Code__CodeOntologyThing.md)

The formal definition of these patterns is available in [OWL Syntax](Code.owl).

## Contact Pattern

Properties that define the hours of operation of the contact.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Address (Contact)](classes/Contact__Address.md)
- [Address Type](classes/Contact__Address Type.md)
- [Contact Thing (Contact)](classes/Contact__ContactThing.md)
- [Cottage Address](classes/Contact__Cottage Address.md)
- [Country (Contact)](classes/Contact__Country.md)
- [Fax Telephone Number](classes/Contact__Fax Telephone Number.md)
- [Home Address](classes/Contact__Home Address.md)
- [Home Telephone Number](classes/Contact__Home Telephone Number.md)
- [Hours Of Operation (Contact)](classes/Contact__HoursOfOperation.md)
- [Mobile Telephone Number](classes/Contact__Mobile Telephone Number.md)
- [Phone Number](classes/Contact__Phone Number.md)
- [Phone Type](classes/Contact__Phone Type.md)
- [Schema Org Thing (Contact)](classes/Contact__SchemaOrgThing.md)
- [State (Contact)](classes/Contact__State.md)
- [Street Direction](classes/Contact__Street Direction.md)
- [Street Type](classes/Contact__Street Type.md)
- [Toll  Free Telephone Number](classes/Contact__Toll  Free Telephone Number.md)
- [Work Address](classes/Contact__Work Address.md)
- [Work Telephone Number](classes/Contact__Work Telephone Number.md)

The formal definition of these patterns is available in [OWL Syntax](Contact.owl).

## Contract Pattern

A contract is a legal document that specifies some agreement(s) between two or more parties. The aim of the Contract Ontology is not to formalize the semantics of all possible involved legal concepts, but rather to enable to representation of the general structure and contents of a particular contract. The Contract Ontology adopts the definition of Contract specified in the Financial Business Ontology (FIBO) [8] specified at: https://spec.edmcouncil.org/fibo/ontology/FND/Agreements/Contracts/ with a key modification that a Contract is defined as a type of Document and is distinct from an Agreement (not a subclass, as specified in FIBO).

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Condition Precedent (Contract)](classes/Contract__ConditionPrecedent.md)
- [Contract (Contract)](classes/Contract__Contract.md)
- [Contract Ontology Thing (Contract)](classes/Contract__ContractOntologyThing.md)
- [Contractual Commitment (Contract)](classes/Contract__ContractualCommitment.md)
- [Contractual Definition (Contract)](classes/Contract__ContractualDefinition.md)
- [Contractual Element (Contract)](classes/Contract__ContractualElement.md)
- [Non Binding Term (Contract)](classes/Contract__NonBindingTerm.md)
- [Representation (Contract)](classes/Contract__Representation.md)
- [Warranty (Contract)](classes/Contract__Warranty.md)

The formal definition of these patterns is available in [OWL Syntax](Contract.owl).

## Household Pattern

The Household ontology defines the classes: Household, Family, and DwellingUnit. These definitions serve as a basis which may be extended for more specific applications such as a surveys and simulations.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Household (Household)](classes/Household__Household.md)
- [Household Ontology Thing (Household)](classes/Household__HouseholdOntologyThing.md)

The formal definition of these patterns is available in [OWL Syntax](Household.owl).

## Infrastructure Pattern

The Infrastructure pattern defines the concepts needed to capture various types of city infrastructure, such as buildings and roads. The Infrastructure pattern reuses the Spatial Location pattern (from ISO 5087-1) in order to capture the location of these infrastructure elements.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Infrastructure Element (Infrastructure)](classes/Infrastructure__InfrastructureElement.md)
- [Infrastructure Ontology Thing (Infrastructure)](classes/Infrastructure__InfrastructureOntologyThing.md)

The formal definition of these patterns is available in [OWL Syntax](Infrastructure.owl).

## Land Use Ontology

The Land Use Pattern captures concepts related to land use and cover over time. 
Land Use Classifications provide a means of describing the land cover/use in a standard way. Various classification systems are used to identify types of land use. Currently, we include LBCS, CLUMP, and AAFC.
The ontology reuses and extends the Land Based Classification Standards (LBCS) Ontology  presented by (Montenegro, Gomes, Urbano, and Duarte, 2011) for this purpose.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Employed Population (LandUse)](classes/LandUse__EmployedPopulation.md)
- [Land Area (LandUse)](classes/LandUse__LandArea.md)
- [Land Use Classification (LandUse)](classes/LandUse__LandUseClassification.md)
- [Land Use Ontology Thing (LandUse)](classes/LandUse__LandUseOntologyThing.md)
- [Parcel (LandUse)](classes/LandUse__Parcel.md)
- [Resident Population (LandUse)](classes/LandUse__ResidentPopulation.md)
- [Traffic Zone (LandUse)](classes/LandUse__TrafficZone.md)

The formal definition of these patterns is available in [OWL Syntax](LandUse.owl).

## Person Ontology

Ontology to capture concepts related to Persons.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Citizenship (Person)](classes/Person__Citizenship.md)
- [Education (Person)](classes/Person__Education.md)
- [Gender (Person)](classes/Person__Gender.md)
- [ID Type (Person)](classes/Person__IDType.md)
- [Person (Person)](classes/Person__Person.md)
- [Person Id (Person)](classes/Person__PersonId.md)
- [Person Name (Person)](classes/Person__PersonName.md)
- [Person Ontology Thing (Person)](classes/Person__PersonOntologyThing.md)
- [Qualification (Person)](classes/Person__Qualification.md)
- [Schema Org Thing (Person)](classes/Person__SchemaOrgThing.md)
- [Sex (Person)](classes/Person__Sex.md)
- [Skill (Person)](classes/Person__Skill.md)

The formal definition of these patterns is available in [OWL Syntax](Person.owl).

## SSN Ontology

Ontology to capture concepts related to sensors and their observations. Directly reuses the SSN Ontology; adds classes and properties for organization of terms.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [sensors Thing (Sensors)](classes/Sensors__sensorsThing.md)

The formal definition of these patterns is available in [OWL Syntax](Sensors.owl).

## Transportation Infrastructure Pattern

The Transportation Infrastructure pattern defines the concepts that are relevant in describing the physical transportation infrastructure and their characteristics. This includes the concepts of a Road, Bridge, and Tunnel. The Infrastructure Pattern is reused here, as these transportation structures are all defined as types of (subclasses) Infrastructure Elements.

This ontology consists of the following patterns:


The ontology also contains the following classes that are not assigned to any pattern:

- [Bridge (TransportationInfrastructure)](classes/TransportationInfrastructure__Bridge.md)
- [Bridge Segment (TransportationInfrastructure)](classes/TransportationInfrastructure__BridgeSegment.md)
- [Rail Line (TransportationInfrastructure)](classes/TransportationInfrastructure__RailLine.md)
- [Rail Line Segment (TransportationInfrastructure)](classes/TransportationInfrastructure__RailLineSegment.md)
- [Rail Link (TransportationInfrastructure)](classes/TransportationInfrastructure__RailLink.md)
- [Rail Segment (TransportationInfrastructure)](classes/TransportationInfrastructure__RailSegment.md)
- [Road (TransportationInfrastructure)](classes/TransportationInfrastructure__Road.md)
- [Road Link (TransportationInfrastructure)](classes/TransportationInfrastructure__RoadLink.md)
- [Road Network Type (TransportationInfrastructure)](classes/TransportationInfrastructure__RoadNetworkType.md)
- [Road Segment (TransportationInfrastructure)](classes/TransportationInfrastructure__RoadSegment.md)
- [Transportation Infrastructure Ontology Thing (TransportationInfrastructure)](classes/TransportationInfrastructure__TransportationInfrastructureOntologyThing.md)
- [Travelled Way (TransportationInfrastructure)](classes/TransportationInfrastructure__TravelledWay.md)
- [Travelled Way Link (TransportationInfrastructure)](classes/TransportationInfrastructure__TravelledWayLink.md)
- [Travelled Way Segment (TransportationInfrastructure)](classes/TransportationInfrastructure__TravelledWaySegment.md)
- [Tunnel (TransportationInfrastructure)](classes/TransportationInfrastructure__Tunnel.md)
- [Tunnel Segment (TransportationInfrastructure)](classes/TransportationInfrastructure__TunnelSegment.md)

The formal definition of these patterns is available in [OWL Syntax](TransportationInfrastructure.owl).

