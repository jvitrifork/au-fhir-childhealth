**NCDHC Hearing Screen Observation Profile**

This profile sets minimum expectations for the [Observation] resource to record, search and fetch Hearing screen result of the baby patient. It identifies which core elements, extensions, vocabularies and value sets **SHALL** be present in the resource when using this profile. The profile is at draft stage and under review by the Child Health Working Group. 

**Example Usage Scenarios:**

The following are example usage scenarios for the National Child Digital Health interactions
profile:

-   Query for Hearing Screen result of the baby patient
-   Record Hearing Screen result of the baby patient

##### Mandatory Data Elements and Terminology


The following data-elements are mandatory (i.e data MUST be present). These are presented below in a simple human-readable explanation. Profile specific guidance and examples are provided as well.  The [**Formal Profile Definition**](#profile) below provides the  formal summary, definitions, and  terminology requirements.  

**Each Observation must have:**

1.  a status  
1.  a SNOMED code (indicating what was recorded)
1.  a subject ([Patient])
1.  a time (indicating when the details were recorded)
1.	a performer (detailing who has recorded the details)


**Profile specific implementation guidance:**

* To be added




#### Examples

- [Hearing Screen Observation](ncdhc-observation-hearingscreen-normal-example.html)

[Observation]: http://hl7.org/fhir/observation.html
[extensible]: http://hl7.org/fhir/terminologies.html#extensible
[General Guidance Section]: definitions.html
[Patient]: http://build.fhir.org/ig/hl7au/au-fhir-childhealth/StructureDefinition-ncdhc-patient-baby.html
