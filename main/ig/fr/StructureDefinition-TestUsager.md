# Usager test - Test PlantUML/GraphViz compatibility v0.1.0

## Modèle logique: Usager test 

 
Modèle logique minimal pour le test PlantUML 

**Utilisations:**

* Ce Modèle logique n'est utilisé par aucun autre profil dans ce guide d'implémentation

Vous pouvez également vérifier [les usages dans le FHIR IG Statistics](https://packages2.fhir.org/xig/test.plantuml.bug|current/StructureDefinition/TestUsager)

### Vues formelles du contenu du profil

 [Description des profils, des différentiels, des instantanés et de leurs représentations](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

*  [Tableau différentiel (differential)](#tabs-diff) 
*  [Tableau récapitulatif (snapshot)](#tabs-snap) 
*  [Statistiques/Références](#tabs-summ) 
*  [Tous](#tabs-all) 

Cette structure est dérivée de [Base](http://build.fhir.org/types.html#Base) 

Cette structure est dérivée de [Base](http://build.fhir.org/types.html#Base) 

** Résumé **

Obligatoire : 0 élément(2 éléments obligatoire(s) imbriqué(s))

 **Vue différentielle** 

Cette structure est dérivée de [Base](http://build.fhir.org/types.html#Base) 

 **Vue d'ensembleView** 

Cette structure est dérivée de [Base](http://build.fhir.org/types.html#Base) 

** Résumé **

Obligatoire : 0 élément(2 éléments obligatoire(s) imbriqué(s))

 

Autres représentations du profil : [CSV](../StructureDefinition-TestUsager.csv), [Excel](../StructureDefinition-TestUsager.xlsx) 



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
  "date" : "2026-06-16T15:00:27+00:00",
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
