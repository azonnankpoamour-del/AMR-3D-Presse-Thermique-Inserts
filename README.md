
# AMR-3D — Conception et réalisation d'une presse thermique pour inserts filetés

<p align="center">
  <img src="Images/AMR_PRESSE.jpg" width="75%" alt="Presse thermique AMR-3D - Version 1">
</p>

<h3 align="center">
  De la conception mécanique à la fabrication additive : développement d'une presse thermique dédiée à l'insertion d'inserts filetés.
</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Projet-AMR--3D-blue">
  <img src="https://img.shields.io/badge/V1-Fabriquée%20et%20testée-success">
  <img src="https://img.shields.io/badge/V2-En%20développement-orange">
  <img src="https://img.shields.io/badge/CAO-SOLIDWORKS%203DEXPERIENCE-red">
  <img src="https://img.shields.io/badge/Fabrication-PLA%2B-informational">
</p>

---

# 1. Présentation du projet

## 1.1. Contexte

Dans le domaine de la fabrication additive, les inserts filetés métalliques constituent une solution intéressante pour intégrer des assemblages vissés dans des pièces thermoplastiques.

Ils permettent notamment d'améliorer la résistance des zones de fixation et de rendre possibles les opérations répétées de montage et de démontage.

Cependant, leur installation nécessite une maîtrise du positionnement, de l'alignement, de la température et de la profondeur d'insertion.

Une opération réalisée manuellement peut entraîner différents défauts : inclinaison de l'insert, positionnement imprécis, profondeur irrégulière ou déformation locale de la pièce.

C'est à partir de cette problématique que j'ai imaginé et développé **AMR-3D**, un projet personnel de conception et de réalisation d'une presse thermique destinée à faciliter l'intégration d'inserts filetés dans les pièces issues de l'impression 3D.

## 1.2. Présentation de la solution

AMR-3D est un dispositif mécanique conçu pour guider le déplacement vertical d'un outil chauffant et faciliter l'insertion d'inserts filetés dans des composants thermoplastiques.

La première version repose sur une structure porteuse verticale, un système de guidage, un mécanisme de déplacement, un support pour l'outil chauffant et un socle destiné au positionnement de la pièce.

J'ai développé ce dispositif selon une démarche progressive allant de l'analyse du besoin à la conception CAO, puis à la fabrication additive, à l'assemblage et aux essais expérimentaux.

Le projet est organisé autour de deux versions :

- **AMR-3D V1 :** premier prototype entièrement conçu, fabriqué, assemblé et testé avec succès.
- **AMR-3D V2 :** évolution mécanique intégrant un étau de serrage réglable à la place du support fixe initial.

Mon objectif est de développer une solution compacte, fonctionnelle et évolutive, adaptée aux besoins de la fabrication additive.

## 1.3. Objectifs du projet

- Concevoir un dispositif mécanique dédié à l'insertion thermique.
- Développer un système de guidage vertical.
- Faciliter l'alignement entre l'outil chauffant et l'insert.
- Assurer la stabilité de la structure pendant l'utilisation.
- Concevoir des composants adaptés à la fabrication additive.
- Réaliser l'assemblage des différents éléments mécaniques.
- Vérifier expérimentalement le fonctionnement du prototype.
- Améliorer le maintien des pièces grâce à une nouvelle architecture mécanique.

---

# 2. Analyse du besoin et cahier des charges

## 2.1. Besoin identifié

Mon besoin initial était de concevoir un équipement permettant de faciliter l'installation d'inserts filetés en laiton dans des pièces thermoplastiques.

Je souhaitais développer un dispositif capable de maintenir une géométrie mécanique stable, de guider l'outil chauffant et de faciliter la maîtrise du déplacement pendant l'opération.

## 2.2. Fonctions principales

| Référence | Fonction |
|---|---|
| FP1 | Assurer la stabilité de la structure |
| FP2 | Guider le déplacement vertical de l'outil |
| FP3 | Faciliter l'application d'un effort axial |
| FP4 | Favoriser l'alignement de l'insert |
| FP5 | Permettre l'insertion thermique |
| FP6 | Maintenir la pièce à équiper |
| FP7 | Faciliter la répétition des opérations |

## 2.3. Contraintes techniques

- Encombrement réduit.
- Rigidité de la structure.
- Stabilité du socle.
- Précision du guidage vertical.
- Compatibilité géométrique des composants.
- Facilité d'assemblage.
- Accessibilité de la zone de travail.
- Résistance des pièces imprimées aux sollicitations mécaniques.
- Prise en compte des contraintes thermiques à proximité de l'outil chauffant.

---

# 3. Conception mécanique et modélisation CAO

## 3.1. Environnement de conception

J'ai réalisé la conception tridimensionnelle de mon dispositif avec **SOLIDWORKS sur la plateforme 3DEXPERIENCE**.

Cet environnement de conception assistée par ordinateur (CAO) m'a permis de développer les différentes géométries des composants, de définir leur architecture mécanique et de préparer les éléments destinés à la fabrication additive.

J'ai travaillé sur la conception des éléments structurels, des composants de liaison, du système de guidage et des différentes pièces nécessaires à l'assemblage.

## 3.2. Étapes de conception

### CAO1 — Première étape de conception

![CAO1](Images/CAO1.png)

### CAO2 — Développement de la modélisation

![CAO2](Images/CAO2.png)

### CAO3 — Conception des composants mécaniques

![CAO3](Images/CAO3.png)

### CAO4 — Évolution de la conception

![CAO4](Images/CAO4.png)

---

# 4. Dimensionnement mécanique

Le dimensionnement mécanique a constitué une étape importante dans le développement de mon dispositif. J'ai porté une attention particulière à la résistance des composants, à la rigidité de la structure et à la stabilité générale de l'ensemble.

L'objectif est de garantir un fonctionnement mécanique cohérent, notamment lors de l'application de l'effort nécessaire à l'insertion des inserts filetés.

## 4.1. Dimensionnement du socle

Le socle constitue la base de la presse. Il supporte les différents éléments du dispositif et assure la liaison avec la surface de travail.

J'ai pris en compte les sollicitations susceptibles d'être transmises au socle pendant l'utilisation, notamment les efforts verticaux appliqués au niveau de la zone d'insertion.

Les principaux critères étudiés sont :

- La résistance à la flexion sous l'effet des efforts transmis par la structure.
- La résistance à la compression au niveau des zones de fixation.
- La rigidité globale afin de limiter les déformations.
- La stabilité de la presse pendant les opérations.
- La résistance des interfaces de liaison avec le montant vertical.

## 4.2. Dimensionnement du bras vertical

Le bras vertical constitue l'élément porteur principal de la presse.

Il assure le maintien du mécanisme supérieur et transmet les efforts vers le socle.

Sa conception doit permettre de limiter les déformations pendant les opérations d'insertion.

J'ai notamment pris en compte :

- La résistance à la flexion sous l'effet des efforts appliqués.
- La résistance à la compression.
- La rigidité de la section.
- La stabilité de l'ensemble.
- La qualité de la liaison entre le bras et le socle.

## 4.3. Dimensionnement du système de guidage

Le système de guidage joue un rôle essentiel dans le fonctionnement de la presse.

Il permet de contrôler le déplacement vertical du support de l'outil chauffant et de favoriser l'alignement avec l'insert.

J'ai porté une attention particulière à :

- La limitation des jeux fonctionnels.
- La réduction des déplacements latéraux.
- La rigidité des éléments de guidage.
- La régularité du déplacement.
- La limitation des frottements parasites.

## 4.4. Dimensionnement des fixations et des liaisons

Les différentes liaisons mécaniques assurent la cohésion de l'ensemble.

J'ai pris en compte la résistance des zones de fixation, les efforts transmis entre les composants et la nécessité de conserver un assemblage stable pendant l'utilisation.

Les zones de fixation doivent notamment résister aux sollicitations mécaniques répétées.

## 4.5. Choix du matériau

J'ai retenu le PLA+ pour la fabrication des composants imprimés.

Ce matériau présente plusieurs avantages pour le prototypage mécanique :

- Facilité de mise en œuvre.
- Bonne qualité dimensionnelle.
- Disponibilité.
- Facilité de modification et de remplacement des composants.
- Adaptation à la fabrication de géométries personnalisées.

La proximité de l'outil chauffant impose cependant de prendre en compte les effets de la température sur les composants imprimés.

## 4.6. Critères mécaniques pris en compte

| Critère | Objectif |
|---|---|
| Résistance à la flexion | Limiter les déformations des éléments porteurs |
| Résistance à la compression | Éviter l'écrasement des zones sollicitées |
| Rigidité | Maintenir la géométrie du dispositif |
| Stabilité | Éviter les déplacements de la structure |
| Résistance des fixations | Assurer la cohésion de l'assemblage |
| Tenue thermique | Limiter les déformations dues à la chaleur |

---

# 5. Fabrication additive

## 5.1. Technologie utilisée

J'ai choisi la fabrication additive par dépôt de matière fondue (FDM/FFF) pour réaliser les différents composants de mon dispositif.

Cette technologie m'a permis de fabriquer des géométries personnalisées, de réduire les opérations d'usinage et de faciliter les modifications successives du prototype.

## 5.2. Équipements et paramètres d'impression

J'ai utilisé une imprimante **ELEGOO Centauri Carbon** pour fabriquer les composants de la première version.

Les paramètres retenus sont les suivants :

| Paramètre | Valeur |
|---|---|
| Imprimante 3D | ELEGOO Centauri Carbon |
| Technologie | FDM / FFF |
| Matériau | PLA+ |
| Hauteur de couche | 0,20 mm |
| Diamètre de buse | 0,4 mm |
| Taux de remplissage | 20 % |
| Nombre de parois | 4 |
| Épaisseur théorique des parois | 1,6 mm |
| Temps total d'impression retenu | 20 heures |

Le choix de quatre parois permet de renforcer les enveloppes périphériques des composants, tandis que le remplissage de 20 % contribue à limiter la consommation de matière et la durée de fabrication.

## 5.3. Préparation des fichiers de fabrication

Après la conception des composants, j'ai préparé les modèles tridimensionnels dans un logiciel de tranchage avant leur fabrication.

Cette étape comprend l'orientation des pièces, la définition des paramètres d'impression et la génération des trajectoires de fabrication.

### P1 — Préparation des pièces

![P1](Images/P1.png)

### P2 — Paramétrage de fabrication

![P2](Images/P2.png)

### P3 — Préparation des composants

![P3](Images/P3.png)

### P4 — Vérification des trajectoires

![P4](Images/P4.png)

### P5 — Préparation finale avant impression

![P5](Images/P5.png)

---

# 6. Assemblage mécanique

## 6.1. Démarche d'assemblage

Après la fabrication des différents composants, j'ai procédé à l'assemblage du prototype.

Cette opération a consisté à intégrer les éléments structurels, le système de guidage, le mécanisme de réglage et le support de l'outil chauffant.

J'ai porté une attention particulière à la compatibilité des interfaces, à l'alignement des composants et à la liberté de déplacement du mécanisme.

## 6.2. Documentation photographique

### I1 — Assemblage : étape 1

![I1](Images/I1.png)

### I2 — Assemblage : étape 2

![I2](Images/I2.png)

### I3 — Assemblage : étape 3

![I3](Images/I3.png)

### I4 — Assemblage : étape 4

![I4](Images/I4.png)

### I5 — Présentation du dispositif assemblé

![I5](Images/I5.png)

---

# 7. AMR-3D V1 — Premier prototype fabriqué et testé

<p align="center">
  <img src="Images/AMR_PRESSE.jpg" width="75%" alt="AMR-3D V1">
</p>

**Statut : fabriquée, assemblée et testée avec succès.**

## 7.1. Présentation de la V1

La première version d'AMR-3D correspond au prototype initial que j'ai développé à partir de mon travail de conception mécanique et de modélisation CAO.

Cette version repose sur une structure verticale intégrant un système de guidage, un mécanisme de déplacement, un support pour l'outil chauffant et un socle destiné à recevoir la pièce à équiper.

Le dispositif permet de guider l'outil vers l'insert et de réaliser l'opération d'insertion thermique.

## 7.2. Architecture fonctionnelle

Les principaux éléments de cette version sont :

- Un socle assurant le support de l'ensemble.
- Un bras vertical constituant la structure porteuse.
- Un système de guidage.
- Un mécanisme de déplacement.
- Un support pour l'outil chauffant.
- Un système de réglage mécanique.

## 7.3. Résultats obtenus

La réalisation de cette première version m'a permis :

- De concrétiser l'architecture mécanique initialement proposée.
- De fabriquer les différents composants par impression 3D.
- De vérifier le fonctionnement du guidage vertical.
- De réaliser l'intégration de l'outil chauffant.
- D'effectuer les opérations d'insertion thermique.
- De valider expérimentalement le fonctionnement du concept.

## 7.4. Retour d'expérience

La fabrication et les premiers essais m'ont permis d'identifier une possibilité d'amélioration concernant le maintien des pièces.

Le support initial permet de positionner les composants, mais ne dispose pas d'un véritable mécanisme de serrage réglable.

J'ai donc envisagé l'intégration d'un étau afin d'améliorer le maintien des pièces et de faciliter l'adaptation à différentes géométries.

Cette réflexion constitue le point de départ du développement de la deuxième version.

---

# 8. Essais expérimentaux et validation fonctionnelle

## 8.1. Objectif des essais

Après l'assemblage du prototype, j'ai réalisé une série d'essais expérimentaux afin de vérifier son fonctionnement réel et sa capacité à effectuer l'insertion thermique d'inserts filetés en laiton.

J'ai notamment observé le positionnement de l'insert, l'alignement de l'outil chauffant, le déplacement du mécanisme et le résultat de l'insertion.

## 8.2. Protocole expérimental

La procédure d'essai comprend les opérations suivantes :

1. Préparation de la pièce thermoplastique.
2. Positionnement de l'insert dans son logement.
3. Installation de la pièce sur le support.
4. Alignement de l'outil chauffant.
5. Mise en température de l'outil.
6. Descente progressive du mécanisme.
7. Réalisation de l'insertion thermique.
8. Vérification du résultat obtenu.

## 8.3. Inserts utilisés

Pour les premiers essais, j'ai utilisé des inserts filetés en laiton M3 × 4 × 5 mm.

| Caractéristique | Valeur |
|---|---|
| Matériau | Laiton |
| Filetage intérieur | M3 |
| Diamètre extérieur nominal | 4 mm |
| Longueur nominale | 5 mm |
| Vis compatible | M3 × 5 mm |

## 8.4. Documentation photographique des essais

### T1 — Première phase des essais

![T1](Images/T1.png)

### T2 — Positionnement de l'insert

![T2](Images/T2.png)

### T3 — Début de l'insertion thermique

![T3](Images/T3.png)

### T4 — Déroulement de l'opération

![T4](Images/T4.png)

### T5 — Poursuite des essais

![T5](Images/T5.png)

### T6 — Vérification du résultat

![T6](Images/T6.png)

### T7 — Résultat final des essais

![T7](Images/T7.png)

## 8.5. Bilan expérimental

Les essais réalisés ont été concluants.

J'ai pu constater le bon fonctionnement du dispositif et effectuer les opérations d'insertion thermique prévues avec les inserts filetés en laiton M3.

Cette première validation expérimentale confirme la faisabilité de la solution mécanique que j'ai développée.

Elle constitue également une base de travail pour les prochaines améliorations du dispositif.

---

# 9. AMR-3D V2 — Évolution avec intégration d'un étau de serrage

<p align="center">
  <img src="https://img.shields.io/badge/AMR--3D-V2%20à%20venir-orange">
</p>

**Statut : prochaine évolution du projet.**

## 9.1. Origine de cette évolution

À la suite de la fabrication et de la validation expérimentale de la première version, j'ai engagé une réflexion sur les possibilités d'amélioration de l'architecture mécanique.

L'une des évolutions les plus intéressantes concerne le système de maintien de la pièce.

La V1 utilise un support fixe pour positionner les composants à équiper. Pour aller plus loin, j'ai choisi d'orienter la deuxième version vers l'intégration d'un étau de serrage réglable directement sur le socle.

## 9.2. Principe de la nouvelle architecture

Le principe de la V2 consiste à remplacer le support fixe actuel par un système d'étau permettant de maintenir la pièce entre deux surfaces de serrage.

Le déplacement du mors mobile sera commandé par une vis de manœuvre, afin d'adapter l'ouverture à différentes dimensions de pièces.

Cette solution permettra d'améliorer le maintien de la pièce avant et pendant l'insertion thermique.

## 9.3. Objectifs de la V2

- Intégrer un système de serrage réglable.
- Améliorer le maintien des pièces.
- Limiter les déplacements involontaires pendant l'insertion.
- Faciliter le positionnement des composants.
- Permettre l'adaptation à différentes dimensions de pièces.
- Améliorer la répétabilité des opérations.
- Renforcer la polyvalence du dispositif.

## 9.4. Éléments mécaniques envisagés

| Élément | Fonction |
|---|---|
| Corps de l'étau | Supporter le mécanisme de serrage |
| Mors fixe | Constituer une surface de référence |
| Mors mobile | Assurer le serrage de la pièce |
| Vis de manœuvre | Commander le déplacement du mors mobile |
| Guidage du mors | Assurer un déplacement contrôlé |
| Fixation au socle | Assurer la liaison mécanique |
| Surfaces de contact | Répartir l'effort de serrage |

## 9.5. Améliorations attendues

L'intégration de cet étau me permettra de faire évoluer le dispositif d'un simple support de positionnement vers un véritable système de maintien mécanique réglable.

Cette évolution vise à apporter une meilleure stabilité de la pièce, à faciliter les opérations successives et à élargir les possibilités d'utilisation de la presse.

La V2 représente ainsi une évolution fonctionnelle de l'architecture mécanique, directement issue des observations réalisées lors des essais de la première version.

---

# 10. Comparaison entre les deux versions

| Critère | AMR-3D V1 | AMR-3D V2 |
|---|---|---|
| Support de pièce | Support fixe | Étau réglable |
| Maintien | Positionnement sur le socle | Serrage mécanique |
| Guidage vertical | Intégré | Conservé |
| Outil chauffant | Intégré | Conservé |
| Adaptabilité | Selon le support | Selon l'ouverture de l'étau |
| Fabrication | Réalisée | À venir |
| Validation | Essais réalisés | À venir |

---

# 11. Perspectives de développement

Au-delà de l'intégration de l'étau, plusieurs améliorations pourront être envisagées :

- Intégration d'un système de régulation thermique plus précis.
- Optimisation de la rigidité de la structure.
- Amélioration de la précision du guidage vertical.
- Développement d'un système de réglage de profondeur.
- Conception de mors interchangeables.
- Adaptation à plusieurs dimensions d'inserts.
- Mesure de l'effort d'insertion.
- Évaluation quantitative de la répétabilité.

---

# 12. Démonstration vidéo

Je prévois également de présenter une démonstration vidéo du fonctionnement de la première version.

Cette démonstration permettra de découvrir le mécanisme de déplacement, le fonctionnement général de la presse et les opérations d'insertion thermique réalisées.

**Vidéo de démonstration : à venir.**

---

# 13. Conclusion

À travers AMR-3D, j'ai souhaité transformer un besoin technique concret en une solution mécanique fonctionnelle.

De l'analyse du besoin à la modélisation CAO, en passant par la fabrication additive, l'assemblage et les essais expérimentaux, j'ai mené les différentes étapes nécessaires à la réalisation de mon premier prototype.

La V1, désormais fabriquée et testée avec succès, m'a permis de confirmer la faisabilité du concept et d'identifier de nouvelles possibilités d'amélioration.

La V2, dont le développement est prévu prochainement, intégrera un étau de serrage réglable destiné à améliorer le maintien des pièces et à rendre le dispositif plus polyvalent.

Ce projet illustre ma démarche personnelle : concevoir, expérimenter, analyser les résultats et faire évoluer une solution technique pour améliorer ses performances et ses fonctionnalités.

Il mobilise plusieurs compétences en génie mécanique, notamment la conception mécanique, la modélisation CAO, la fabrication additive, l'assemblage, le prototypage et la validation expérimentale.

---

<p align="center">
  <strong>AMR-3D — Concevoir. Fabriquer. Tester. Améliorer.</strong>
</p>

<p align="center">
  Conception, modélisation, fabrication et développement :<br>
  <strong>Amour Tamègnon AZONNAKPO</strong>
</p>
