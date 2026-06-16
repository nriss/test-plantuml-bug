# Usager test - Test PlantUML/GraphViz compatibility v0.1.0

## Logical Model: Usager test 

 
Modèle logique minimal pour le test PlantUML 

**Usages:**

* This Logical Model is not used by any profiles in this Specification

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/resource/test.plantuml.bug|current/StructureDefinition/StructureDefinition-TestUsager.json)

### Formal Views of Profile Content

 [Description Differentials, Snapshots, and other representations](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](../StructureDefinition-TestUsager.csv), [Excel](../StructureDefinition-TestUsager.xlsx) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "TestUsager",
  "url" : "https://example.com/ig/test-plantuml-bug/StructureDefinition/TestUsager",
  "version" : "0.1.0",
  "name" : "TestUsager",
  "title" : "Usager test",
  "status" : "draft",
  "date" : "2026-06-16T15:00:36+00:00",
  "description" : "Modèle logique minimal pour le test PlantUML",
  "jurisdiction" : [{
    "coding" : [{
      "system" : "urn:iso:std:iso:3166",
      "code" : "FR",
      "display" : "France (la)"
    }]
  }],
  "fhirVersion" : "4.0.1",
  "kind" : "logical",
  "abstract" : false,
  "type" : "https://example.com/ig/test-plantuml-bug/StructureDefinition/TestUsager",
  "baseDefinition" : "http://hl7.org/fhir/StructureDefinition/Base",
  "derivation" : "specialization",
  "differential" : {
    "element" : [{
      "id" : "TestUsager",
      "path" : "TestUsager",
      "short" : "Usager test",
      "definition" : "Modèle logique minimal pour le test PlantUML"
    },
    {
      "id" : "TestUsager.identifiant",
      "path" : "TestUsager.identifiant",
      "short" : "Identifiant",
      "definition" : "Identifiant",
      "min" : 1,
      "max" : "1",
      "type" : [{
        "code" : "Identifier"
      }]
    },
    {
      "id" : "TestUsager.nom",
      "path" : "TestUsager.nom",
      "short" : "Nom",
      "definition" : "Nom",
      "min" : 1,
      "max" : "1",
      "type" : [{
        "code" : "string"
      }]
    }]
  }
}

```
