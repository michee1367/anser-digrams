# Legende 

## Entité administrative

- Anser.EntityAdministration : Entité administrative [Fait]
- Anser.EntityAdministration.Province : Province [Fait]
- Anser.EntityAdministration.Territory : Territoire [Fait]
- Anser.EntityAdministration.City : Ville [Fait]
- Anser.EntityAdministration.Locality : Localité [Fait]
- Anser.EntityAdministration.Sector : Secteur [Fait]

## Centrales existantes

- Anser.ExistingPlants : Centrales existantes [Fait]
- Anser.ExistingPlants.ExistingPlant.name : Nom du central [Fait]
- Anser.ExistingPlants.ExistingPlantType : Type du central (hydroélectrique, solaire, thermique…) [Fait]
- Anser.ExistingPlants.ExistingPlant.geom : Localisation du central(coordonnées GPS) [Fait]
- Anser.ExistingPlants.ExistingPlant.power : Puissance installée/ disponible [KW] [Fait]
- Anser.ExistingPlants.OwnerAndOrOSER : Propriétaire et/ou OSER [Fait]
- Anser.ExistingPlants.OwnerAndOrOSER.name : nom du Propriétaire et/ou OSER [Fait]
- Anser.ExistingPlants.OwnerAndOrOSER.isOwner() : message verification si l'instant est Propriétaire [Fait]
- Anser.ExistingPlants.OwnerAndOrOSER.isOSER() : message verification si l'instant est OSER [Fait]
- Anser.ExistingPlants.ExistingPlant.localities : liste des localités connectées [Fait]
- Anser.ExistingPlants.ExistingPlant.towns : liste des communes connectées [Fait]
- Anser.ExistingPlants.ExistingPlant.nbrOfhouseholds : Nombre de ménages connectés [Fait]
- Anser.ExistingPlants.ExistingPlant.powerOfhouseholds : Puissance ménages [KW] [Fait]
- Anser.ExistingPlants.ExistingPlant.powerForProductiveUsed : Puissance usage productif/ industriel [KW] [Fait]

## Lignes existantes

- Anser.ExistingPowerLines.PowerLine : Lignes existantes [Fait]
- Anser.ExistingPowerLines.PowerLine.tension : Tension de la ligne [Fait]
- Anser.ExistingPowerLines.PowerLine.geom : Donnée géographique [Fait]
- Anser.ExistingPowerLines.PowerLineType : type de la ligne (BT, MT, HT, THT) [Fait]
- Anser.ExistingPowerLines.PowerLineType.wording : denomination du type de la ligne [Fait]
- Anser.ExistingPowerLines.Nature : Nature de la ligne (CC, CA) [Fait]
- Anser.ExistingPowerLines.Nature.wording : denomination de la Nature de la ligne [Fait]

## Kits individuels

- Anser.IndividualSets.IndividualSet : Kit individuel [Fait]
- Anser.IndividualSets.IndividualSet.wording : Denomination du Kit individuel
- Anser.IndividualSets.IndividualSet.nbrhouseholdsConnected : Nombre des ménages connectés
- Anser.IndividualSets.IndividualSet.nbrhouseholdsConnected : Nombre des ménages connectés
- Anser.IndividualSets.IndividualSet.geom : Données géographique
- Anser.IndividualSets.IndividualSet.territories : Territoires connectés
- Anser.IndividualSets.IndividualSet.sectors : Secteurs connectés
- Anser.IndividualSets.IndividualSet.localities : localités connectés

## Potentiel hydroélectrique

- Anser.HydroelectricPotential.HydroelectricPotential : Potentiel hydroélectrique [Fait]
- Anser.HydroelectricPotential.siteName : Nom du site [Fait]
- Anser.HydroelectricPotential.geom : Données géographique [Fait]
- Anser.HydroelectricPotential.riverName : Nom de la rivière [Fait]
- Anser.HydroelectricPotential.dropHeight : Hauteur de chute [m] [Fait]
- Anser.HydroelectricPotential.usableFlow : Débit utilisable [m3/s] [Fait]
- Anser.HydroelectricPotential.usablePower : Puissance exploitable [KW] [Fait]
- Anser.HydroelectricPotential.connectableLocalities : Localités connectables [Fait]

## Potentiel solaire et éolien

- Anser.SolarAndWindPotential.SolarPotential : Potentiel solaire [Fait]
- Anser.SolarAndWindPotential.SolarPotential.solarRadiation  : Rayonnement solaire [KWh/m2/jour] [Fait]
- Anser.SolarAndWindPotential.SolarPotential.geom  : Données géographique [Fait]
- Anser.SolarAndWindPotential.WindPotential : Potentiel éolien [Fait]
- Anser.SolarAndWindPotential.WindPotential.windSpeed : Vitesse du vent [m/s] [Fait]
- Anser.SolarAndWindPotential.WindPotential.geom  : Données géographique [Fait]

## Adduction en eau potable

- Anser.DrinkingWaterSupply.DistributionNetwork : Disponibilité d’eau potable (réseau de distribution) [Fait]
- Anser.SolarAndWindPotential.DistributionNetwork.geom  : Données géographique [Fait]
- Anser.SolarAndWindPotential.DistributionNetwork.wording  : Dénomination [Fait]
- Anser.DrinkingWaterSupply.Fountain : Point de desserte en eau potable (fontaines) [Fait]
- Anser.SolarAndWindPotential.Fountain.geom  : Données géographique [Fait]
- Anser.SolarAndWindPotential.Fountain.wording  : Dénomination [Fait]

## Santé

- Anser.Health.HealthZone : Zone de santé [Fait]
- Anser.Health.HealthZone.name : Nom Zone de santé [Fait]
- Anser.Health.HealthZone.population : population de la Zone de santé [Fait]
- Anser.Health.HealthZone.geom : Données géographique [Fait]
- Anser.Health.HealthInstitution : Etablissement de santé [Fait]
- Anser.Health.HealthInstitution.name : Nom Etablissement de santé [Fait]
- Anser.Health.HealthInstitution.geom : Données géographique [Fait]
- Anser.Health.HealthInstitutionCategory : Catégory Etablissement de santé (Hôpital, dispensaire, centre de santé) [Fait]
- Anser.Health.HealthInstitutionCategory.name : Nom Catégory  Etablissement de santé [Fait]
- Anser.Health.HealthInstitutionService : Service  Etablissement de santé (maternité, chirurgie, morgue…) [Fait]
- Anser.Health.HealthInstitutionService.name : Nom Service  Etablissement de santé [Fait]
- Anser.Health.HealthInstitution.accommodationCapacity : Capacité d’accueil de l’établissement [nombre de personnes] [Fait]
- Anser.Health.HealthInstitution.estimatedConsumption : Consommation estimée lorsqu’existante [Fait]

## Éducation

- Anser.Education.EducationInstitution : établissement [Fait]
- Anser.Education.EducationInstitution.name : Nom de l’établissement [Fait]
- Anser.Education.EducationInstitutionCategory : Catégorie (préscolaire, primaire, secondaire, professionnel,
universitaire) [Fait]
- Anser.Education.EducationInstitutionCategory.name : Nom de la Catégorie [Fait]
- Anser.Education.EducationInstitution.accommodationCapacity : Capacité d’accueil de l’établissement [Fait]
- Anser.Education.EducationInstitution.estimatedConsumption : Consommation estimée lorsqu’existante [Fait]
- Anser.Health.EducationInstitution.geom : Données géographique [Fait]


## Lieux de culte

- Anser.PlacesOfWorship.PlaceOfWorship : Lieux de culte [Fait]
- Anser.PlacesOfWorship.PlaceOfWorship.name : Nom du lieu [Fait]
- Anser.PlacesOfWorship.PlacesOfWorshipInstitution. accommodationCapacity : Capacité d’accueil de l’établissement [Fait] 
- Anser.PlacesOfWorship.PlaceOfWorship.estimatedConsumption : Consommation estimée lorsqu’existante [Fait]
- Anser.Health.PlaceOfWorship.geom : Données géographique [Fait]

## Télécommunication

- Anser.Telecommunication.TelecommunicationOperator : Opérateur de télécommunication [Fait]
- Anser.Telecommunication.TelecommunicationOperator.name : Nom de l'Opérateur de télécommunication [Fait]
- Anser.Telecommunication.TelecommunicationNetworkAccessPoint : Point d'accès au réseau de télécommunication [Fait]
- Anser.Telecommunication.TelecommunicationNetworkAccessPoint.geom : Données géographique [Fait]
- Anser.Telecommunication.TelecommunicationNetworkAccessPoint. hasAccessToInternetServices() : Message pour demander s'il y a Données géographique accès aux services Internet [Fait]


- Anser.Telecommunication.TelecommunicationNetworkAccessPoint.telephoneNetworkQuality : Qualité du réseau téléphonique [Fait]

- Anser.Telecommunication.TelecommunicationNetworkAccessPoint.internetNetworkQuality : Qualité du réseau internet [Fait]

- Anser.PlacesOfWorship.TelecommunicationNetworkAccessPoint.estimatedConsumption : Consommation estimée lorsqu’existante [Fait]

- Anser.Telecommunication.MobileSubscriberBase : Parc des abonnés mobiles [Fait]
- Anser.Telecommunication.MobileSubscriberBase.geom : Données géographique [Fait]

## Voies de communication

- Anser.WaysOfCommunication.WayOfCommunication : Voies de communication [Fait]
- Anser.WaysOfCommunication.WayOfCommunicationType : Type de voie (route, voie ferrée, voie fluviale, voie aérienne) [Fait]
- Anser.WaysOfCommunication.WayOfCommunicationType.name : Nom du type de voie [Fait]
- Anser.WaysOfCommunication.WayOfCommunication.length : Longueur Voies de communication [Fait]
- Anser.WaysOfCommunication.ModeOfTransport : Mode de transport ou véhicules d’usage (navigabilité, voiture et type
de voiture, train, baleinière, avion…) [Fait]
- Anser.WaysOfCommunication.ModeOfTransport.name : Nom Mode de transport ou véhicules d’usage [Fait]

- Anser.WaysOfCommunication.WayOfCommunication.tonnage : Tonnage [Fait]
- Anser.WaysOfCommunication.WayOfCommunication.geom : Données géographique [Fait]

- Anser.WaysOfCommunication.AccessibleSection : Tronçon accessible ou fonctionnel
- Anser.WaysOfCommunication.AccessibleSection.wording : Dénomination Tronçon accessible ou fonctionnel [Fait]
- Anser.WaysOfCommunication.AccessibleSection.geom : Données géographique [Fait]

- Anser.WaysOfCommunication.RoadSurface : Revêtement de la route (latéritique, sablonneux, bitume, béton) [Fait]

- Anser.WaysOfCommunication.RoadSurface.wording : Dénomination Revêtement de la route [Fait]

- Anser.WaysOfCommunication.WayOfCommunication.localities : Principales localités desservies [Fait]

## Économie locale 

- Anser.LocalEconomy.EconomicActivity : Activité économique [Fait]
- Anser.LocalEconomy.EconomicActivityType : Type Activité  économique (agriculture, pêche, artisanat, exploitation
minière…) [Fait]

- Anser.LocalEconomy.EconomicActivityType.wording : Dénomination du Type Activité économique [Fait]

- Anser.LocalEconomy.EconomicActivity.currentProduction : Production actuelle [quantité en kg,tonne…] [Fait]

- Anser.LocalEconomy.EconomicActivity.potentialProduction : Production potentielle [quantité en kg,tonne…] [Fait]

- Anser.LocalEconomy.Equipment : Équipements disponibles (moulins, décortiqueuses, etc.) [Fait]

- Anser.LocalEconomy.EconomicActivity.geom : Données géographique [Fait]

- Anser.LocalEconomy.Equipment.wording : Dénomination Équipements disponibles

- Anser.LocalEconomy.ConsumptionCenter : Centres de consommation pour l’évacuation des produits [Fait]

- Anser.LocalEconomy.ConsumptionCenter.wording : Dénomination Centres de consommation pour l’évacuation des produits [Fait]

- Anser.LocalEconomy.ConsumptionCenter.geom : Données géographique [Fait]

- Anser.LocalEconomy.EconomicActivity.estimatedConsumption : Consommation estimée lorsqu’existante [Fait]


## Projets

- Anser.Projects.Project : Projet [Fait]
- Anser.Projects.Project.wording : Denomination du Projet [Fait]

- Anser.Projects.ProjectType : Type du Projet (hydroélectrique, solaire, extension…) [Fait]

- Anser.Projects.ProjectType.wording : Denomination du type de Projet [Fait]

- Anser.Projects.Project.plannedPowerForHouseholds : Puissance planifiée pour ménages [KW] [Fait]

- Anser.Projects.Project.plannedPowerForProductive : Puissance planifiée pour usage productif/ industriel [KW] [Fait]

- Anser.Projects.Project.geom : Données géographique [Fait]

- Anser.Projects.Project.localities : Localités connectées [Fait]

- Anser.Projects.Project.nbrHouseholds : nombre de ménages connectés [Fait]
- Anser.Projects.ProjectState : État du projet  (non lancé, lancé, réceptionné provisoirement ou définitivement, concession attribuée ) [Fait]

- Anser.Projects.ProjectState.wording : Denomination État du projet [Fait] 

- Anser.Projects.Line : lignes associées [Fait]
- Anser.Projects.Line.geom : Données géographique [Fait]
- Anser.Projects.Line.wording : Denomination lignes associées [Fait]


- Anser.Projects.Substations : sous-stations associées [Fait]
- Anser.Projects.Substations.geom : Données géographique [Fait] 
- Anser.Projects.Substations.wording : Denomination sous-stations associées [Fait]

- Anser.Projects.Transformers : transformateurs [Fait]
- Anser.Projects.Transformers.geom : Données géographique [Fait]
- Anser.Projects.Transformers.wording : Denomination transformateurs [Fait]
- Anser.Projects.Project.ownerAndOrOSER : Propriétaire et/ou OSER [Fait]


- Anser.Projects.Project.nbrHouseholds : nombre de ménages connectés [Fait]
- Anser.Projects.ProgressStatus : Statut d’avancement (études, contractualisation, réalisation en cours – avec échéances associées lorsque disponibles) [Fait]
- Anser.Projects.ProgressStatus.wording : Denomination [Fait]

## Données multisectorielles

- Anser.MultiSectorData.SME : PME (incubateurs des PME)
- Anser.MultiSectorData.SME.wording : Dénomination PME 
- Anser.MultiSectorData.SME.geom : Données géographique
- Anser.MultiSectorData.SME.estimatedConsumption : Consommation estimée lorsqu’existante

- Anser.MultiSectorData.FishingAreas : Zones de pêche
- Anser.MultiSectorData.FishingAreas.wording : Dénomination Zones de pêche 
- Anser.MultiSectorData.FishingAreas.estimatedConsumption : Consommation estimée lorsqu’existante
- Anser.MultiSectorData.FishingAreas.geom : Données géographique

- Anser.MultiSectorData.Industry : Industrie (ZES)
- Anser.MultiSectorData.Industry.wording : Dénomination Industrie 
- Anser.MultiSectorData.Industry.estimatedConsumption : Consommation estimée lorsqu’existante
- Anser.MultiSectorData.Industry.geom : Données géographique

- Anser.MultiSectorData.ICCN : ICCN 
- Anser.MultiSectorData.ICCN.wording : Dénomination ICCN 
- Anser.MultiSectorData.ICCN.estimatedConsumption : Consommation estimée lorsqu’existante
- Anser.MultiSectorData.ICCN.geom : Données géographique

- Anser.MultiSectorData.MiningAreas : Zones minières 
- Anser.MultiSectorData.MiningAreas.wording : Dénomination Zones minières 
- Anser.MultiSectorData.MiningAreas.estimatedConsumption : Consommation estimée lorsqu’existante
- Anser.MultiSectorData.MiningAreas.geom : Données géographique
Mining areas







