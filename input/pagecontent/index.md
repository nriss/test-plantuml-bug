### Test PlantUML/GraphViz

Reproduction du bug de compatibilité PlantUML/GraphViz dans le contexte FHIR IG Publisher.
Diagrammes copiés à l'identique depuis [IG-fhir-medicosocial-transfert-donnees-dui](https://github.com/ansforge/IG-fhir-medicosocial-transfert-donnees-dui).

#### Représentation globale (objet + hidden arrows)

{% include representation_globale.svg %}

#### Identification et coordonnées

{% include bloc_identification_coordonnees.svg %}

#### Autorisations administratives

{% include bloc_autorisations_administratives.svg %}

#### Droits sociaux et de santé

{% include bloc_droits_sociaux_sante.svg %}

#### Environnement et ressources

{% include bloc_environnement_ressources.svg %}

#### Séjours

{% include bloc_sejours.svg %}

#### Évaluation

{% include bloc_evaluation-grille.svg %}

#### Projet personnalisé

{% include bloc_projet_personnalise.svg %}

### Mapping fonctionnel FHIR

#### Mapping Usager

{% include mapping_TDDUIPatient.svg %}
{% include mapping_TDDUIPatientINS.svg %}

#### Mapping PeriodeScolaire

{% include mapping_TDDUIObservationPeriodeScolaire.svg %}

#### Mapping ProjetVie

{% include mapping_TDDUIGoalProjetVie.svg %}

#### Mapping Contact

{% include mapping_TDDUIRelatedPersonContact.svg %}

#### Mapping Entité Juridique

{% include mapping_TDDUIOrganization.svg %}

#### Mapping Professionnel

{% include mapping_TDDUIPractitioner.svg %}
{% include mapping_TDDUIPractitionerRole.svg %}

#### Mapping Sejour

{% include mapping_TDDUIEncounterSejour.svg %}

#### Mapping Evènement

{% include mapping_TDDUIEncounterEvenement.svg %}

#### Mapping Transport

{% include mapping_TDDUITaskTransportProfessionnel.svg %}
{% include mapping_TDDUITaskTransportUsager.svg %}

#### Mapping Evaluation

{% include mapping_TDDUIQuestionnaireResponse.svg %}

#### Vue globale Projet Personnalisé

{% include mapping_TDDUIProjetPersonnalise.svg %}

#### Mapping Projet Personnalisé

{% include mapping_TDDUICarePlanProjetPerso.svg %}

#### Mapping Accord

{% include mapping_TDDUIConsentAccord.svg %}

#### Mapping Besoin

{% include mapping_TDDUIServiceRequestBesoin.svg %}

#### Mapping Objectif

{% include mapping_TDDUIGoalObjectif.svg %}

#### Mapping MoyenRessource

{% include mapping_TDDUITaskMoyenRessource.svg %}

#### Mapping Action

{% include mapping_TDDUITaskAction.svg %}

#### Mapping Prestation

{% include mapping_TDDUITaskPrestation.svg %}

#### Mapping Attente

{% include mapping_TDDUIGoalAttente.svg %}

#### Mapping Bilan

{% include mapping_TDDUITaskBilan.svg %}
