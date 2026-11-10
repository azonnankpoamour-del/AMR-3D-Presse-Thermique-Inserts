# AMR-3D | Conception et développement d'une presse thermique pour inserts filetés

**Conception mécanique · Modélisation CAO · Fabrication additive · Assemblage · Prototypage · Validation expérimentale**

<p align="center">
  <img src="Images/AMR_PRESSE.jpg" width="75%" alt="AMR-3D - Première version de la presse thermique">
</p>

<p align="center">
  <strong>De l'idée à la réalisation : concevoir une solution mécanique pour maîtriser l'insertion thermique des inserts filetés.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Projet-AMR--3D-blue">
  <img src="https://img.shields.io/badge/Version%201-Fabriquée%20et%20testée-success">
  <img src="https://img.shields.io/badge/Version%202-En%20développement-orange">
  <img src="https://img.shields.io/badge/CAO-SOLIDWORKS%203DEXPERIENCE-red">
</p>

---

# 1. Présentation générale du projet

## 1.1. Contexte et problématique

Dans le domaine de la fabrication additive, l'intégration d'inserts filetés métalliques dans les pièces thermoplastiques constitue une solution particulièrement intéressante pour renforcer les zones de fixation et permettre des opérations de montage et de démontage répétées.

Cependant, leur installation nécessite une certaine maîtrise du positionnement, de l'alignement, de la température et de la profondeur d'insertion.

Une insertion réalisée manuellement peut entraîner différents défauts : inclinaison de l'insert, positionnement imprécis, profondeur irrégulière ou déformation locale de la pièce.

C'est dans cette perspective qu'a été développé **AMR-3D**, un projet personnel consacré à la conception et à la réalisation d'une presse thermique destinée à faciliter l'intégration d'inserts filetés dans des composants issus de l'impression 3D.

## 1.2. Présentation de la solution

AMR-3D repose sur une architecture mécanique intégrant une structure porteuse, un système de guidage vertical, un mécanisme de déplacement, un support pour l'outil chauffant et un socle destiné au positionnement des pièces.

Le principe consiste à guider le déplacement de l'outil chauffant afin de faciliter l'alignement avec l'insert et d'accompagner son intégration dans la matière thermoplastique.

Le projet suit une démarche de développement évolutive organisée autour de deux versions :

- **AMR-3D V1 :** premier prototype entièrement conçu, fabriqué, assemblé et testé.
- **AMR-3D V2 :** évolution mécanique intégrant un étau de serrage réglable pour améliorer le maintien des pièces.

L'objectif est de développer progressivement un équipement compact, fonctionnel et adaptable à différentes applications de fabrication additive.

## 1.3. Objectifs techniques

- Concevoir un dispositif mécanique dédié à l'insertion thermique.
- Développer un système de guidage vertical.
- Faciliter l'alignement entre l'outil chauffant et l'insert.
- Assurer la stabilité de la structure.
- Concevoir des composants adaptés à la fabrication additive.
- Réaliser l'assemblage des différents éléments mécaniques.
- Valider expérimentalement le fonctionnement du premier prototype.
- Améliorer le maintien des pièces grâce à une seconde architecture mécanique.

---

# 2. Analyse du besoin et cahier des charges

## 2.1. Besoin identifié

Le besoin consiste à disposer d'un équipement permettant de faciliter l'installation d'inserts filetés en laiton dans des pièces thermoplastiques.

Le dispositif doit permettre de positionner la pièce, de guider l'outil chauffant et de contrôler progressivement son déplacement pendant l'opération.

## 2.2. Fonctions principales

| Référence | Fonction attendue |
|---|---|
| FP1 | Assurer la stabilité de la structure |
| FP2 | Guider le déplacement vertical de l'outil |
| FP3 | Faciliter l'application d'un effort axial |
| FP4 | Favoriser l'alignement de l'insert |
| FP5 | Permettre le transfert thermique nécessaire à l'insertion |
| FP6 | Maintenir la pièce à équiper |
| FP7 | Faciliter la répétition des opérations d'insertion |

## 2.3. Contraintes de conception

- Encombrement réduit.
- Rigidité de la structure.
- Stabilité du socle.
- Précision du guidage.
- Compatibilité géométrique des composants.
- Facilité d'assemblage.
- Accessibilité de la zone de travail.
- Sécurité de l'opérateur.

---

# 3. Conception mécanique et modélisation CAO

## 3.1. Environnement de conception

La conception tridimensionnelle du dispositif a été réalisée avec **SOLIDWORKS sur la plateforme 3DEXPERIENCE**.

Cet environnement de conception assistée par ordinateur (CAO) a permis de développer les différentes géométries des composants, de définir leur architecture mécanique et de préparer les éléments destinés à la fabrication additive.

Le travail a porté sur la conception des éléments structurels, des composants de liaison, du système de guidage et des pièces nécessaires à l'assemblage du dispositif.

## 3.2. Documentation de la conception

### CAO1 — Première étape de conception

![CAO1](Images/CAO1.png)

### CAO2 — Développement de la modélisation

![CAO2](Images/CAO2.png)

### CAO3 — Conception des composants

![CAO3](Images/CAO3.png)

### CAO4 — Évolution de la conception

![CAO4](Images/CAO4.png)

---

# 4. Dimensionnement et caractéristiques géométriques

Le dimensionnement constitue une étape essentielle dans le développement du dispositif. Il permet de vérifier la cohérence des dimensions, la compatibilité des composants et leur aptitude à supporter les sollicitations rencontrées pendant le fonctionnement.

## 4.1. Dimensions relevées sur les modèles CAO

Les dimensions suivantes ont été relevées à partir des captures de modélisation et des fichiers présentés.

### Composant 1 — Support

| Paramètre | Dimension |
|---|---:|
| Longueur | 140 mm |
| Largeur | 100 mm |
| Hauteur | 40 mm |

**Encombrement relevé : 140 × 100 × 40 mm.**

### Composant 2 — PR1

| Paramètre | Dimension |
|---|---:|
| Longueur | 217 mm |
| Largeur | 53,4 mm |
| Hauteur | 99,8 mm |

**Encombrement relevé : 217 × 53,4 × 99,8 mm.**

### Vue d'ensemble des composants

La vue éclatée présente également un encombrement coté de :

**208 × 202 × 47,6 mm.**

Ces dimensions correspondent à la disposition représentée sur la capture de la vue éclatée. Elles ne doivent pas être considérées comme les dimensions définitives d'une pièce individuelle ou de l'ensemble assemblé sans vérification supplémentaire.

*Remarque : ces dimensions sont des relevés visuels des captures CAO. Leur validation définitive doit être effectuée dans SOLIDWORKS 3DEXPERIENCE à l'aide des outils de mesure.*

## 4.2. Caractéristiques des inserts utilisés

Les premiers essais ont été réalisés avec des inserts filetés en laiton de référence M3 × 4 × 5 mm.

| Caractéristique | Valeur |
|---|---:|
| Matériau | Laiton |
| Filetage intérieur | M3 |
| Diamètre extérieur nominal | 4 mm |
| Longueur nominale | 5 mm |
| Vis compatible | M3 × 5 mm |

Le diamètre du logement doit être défini à partir des dimensions réelles de la partie moletée de l'insert et des recommandations du fabricant.

## 4.3. Vérifications mécaniques

Les principales vérifications à considérer sont :

- La résistance mécanique du montant vertical.
- La rigidité du système de guidage.
- La stabilité du socle.
- La limitation des déplacements latéraux.
- La précision de positionnement de l'outil chauffant.
- La résistance des composants imprimés aux efforts appliqués.

Des calculs analytiques et des simulations numériques pourront compléter ces vérifications à partir des matériaux, des dimensions définitives et des efforts mesurés.

---

# 5. Préparation et fabrication additive

## 5.1. Procédé de fabrication

Les composants mécaniques ont été fabriqués par impression 3D selon le procédé de dépôt de matière fondue (FDM/FFF).

Cette technologie permet de produire des géométries personnalisées, de limiter les opérations d'usinage et de faciliter les modifications successives du prototype.

## 5.2. Préparation des fichiers de fabrication

Les modèles tridimensionnels ont été préparés dans un logiciel de tranchage (slicer) avant leur fabrication.

Cette étape comprend notamment l'orientation des pièces, la définition des paramètres d'impression et la génération des trajectoires de fabrication.

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

## 5.3. Paramètres de fabrication

| Paramètre | Valeur |
|---|---|
| Technologie | FDM/FFF |
| Imprimante | À renseigner |
| Matière | À renseigner |
| Hauteur de couche | À renseigner |
| Diamètre de buse | À renseigner |
| Taux de remplissage | À renseigner |
| Nombre de parois | À renseigner |
| Temps d'impression | À renseigner |

---

# 6. Assemblage mécanique

## 6.1. Démarche d'assemblage

Après la fabrication des différents composants, une phase d'assemblage a permis de constituer le prototype.

Cette opération a consisté à intégrer les éléments structurels, le système de guidage, le mécanisme de réglage et le support de l'outil chauffant.

Une attention particulière a été portée à la compatibilité des interfaces, à l'alignement des composants et à la liberté de déplacement du mécanisme.

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
  <img src="Images/AMR_PRESSE.jpg" width="75%" alt="Prototype AMR-3D V1">
</p>

**État d'avancement : version fabriquée, assemblée et testée.**

## 7.1. Présentation de la première version

La première version d'AMR-3D correspond au prototype initial développé à partir du travail de conception mécanique et de modélisation CAO.

Cette version repose sur une structure verticale intégrant un système de guidage, un mécanisme de déplacement, un support pour l'outil chauffant et un socle destiné à recevoir la pièce à équiper.

Le dispositif permet à l'opérateur de guider l'outil vers l'insert et de réaliser l'opération d'insertion thermique.

## 7.2. Architecture fonctionnelle

Les principaux éléments sont :

- Une structure porteuse verticale.
- Un socle de support.
- Un système de guidage.
- Un mécanisme de déplacement.
- Un support pour l'outil chauffant.
- Un système de réglage mécanique.

## 7.3. Objectifs atteints

La réalisation de cette première version a permis :

- De concrétiser l'architecture mécanique initialement proposée.
- De fabriquer les différents composants par impression 3D.
- De vérifier le fonctionnement du guidage vertical.
- De réaliser l'intégration de l'outil chauffant.
- De procéder aux opérations d'insertion thermique.
- De confirmer expérimentalement la faisabilité du concept.

## 7.4. Limite identifiée

Le support initial permet de positionner la pièce, mais ne dispose pas d'un véritable mécanisme de serrage réglable.

L'intégration d'un étau permettrait d'améliorer le maintien de pièces présentant différentes géométries et de limiter leurs déplacements pendant les opérations d'insertion.

Cette observation constitue le point de départ de la deuxième version.

---

# 8. Essais expérimentaux et validation fonctionnelle de la V1

## 8.1. Objectif des essais

Les essais expérimentaux ont été réalisés afin de vérifier le fonctionnement réel du prototype et sa capacité à effectuer l'insertion thermique d'inserts filetés en laiton.

Les observations ont notamment porté sur le positionnement de l'insert, l'alignement de l'outil chauffant, le déplacement du mécanisme et le résultat de l'insertion.

## 8.2. Protocole expérimental

La procédure comprend les opérations suivantes :

1. Préparation de la pièce thermoplastique.
2. Positionnement de l'insert dans son logement.
3. Installation de la pièce sur le support.
4. Alignement de l'outil chauffant.
5. Mise en température de l'outil.
6. Descente progressive du mécanisme.
7. Réalisation de l'insertion thermique.
8. Vérification du résultat obtenu.

## 8.3. Documentation photographique des essais

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

## 8.4. Résultats obtenus

Les essais réalisés ont permis de constater le bon fonctionnement du dispositif.

Le prototype a permis d'effectuer les opérations d'insertion thermique prévues avec les inserts filetés en laiton M3.

Cette première validation expérimentale confirme la faisabilité de la solution mécanique développée.

Des essais complémentaires pourront permettre de quantifier la répétabilité, la profondeur d'insertion, la précision de positionnement et la tenue mécanique des inserts.

---

# 9. AMR-3D V2 — Évolution avec intégration d'un étau de serrage

<p align="center">
  <strong>PROCHAINE ÉVOLUTION DU PROJET</strong>
</p>

**État d'avancement : développement prévu prochainement.**

## 9.1. Origine de cette évolution

À la suite de la fabrication et de la validation expérimentale de la première version, une réflexion sur l'amélioration de l'architecture mécanique a permis d'identifier une possibilité d'évolution importante : le système de maintien de la pièce.

La V1 utilise un support fixe pour positionner les composants à équiper.

Pour améliorer cette fonction, la deuxième version prévoit l'intégration d'un étau de serrage directement sur le socle de la presse.

## 9.2. Principe de la nouvelle architecture

L'étau sera fixé sur le socle et permettra de maintenir la pièce entre deux surfaces de serrage.

Le déplacement du mors mobile sera commandé par une vis de manœuvre, permettant d'adapter l'ouverture à différentes dimensions de pièces.

Cette solution doit faciliter le maintien de la pièce avant et pendant l'insertion thermique.

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

## 9.5. Points de dimensionnement

La conception de la V2 devra prendre en compte :

- La largeur maximale des pièces à maintenir.
- La course d'ouverture de l'étau.
- La hauteur et la géométrie des mors.
- La rigidité du corps de l'étau.
- La résistance des fixations au socle.
- L'effort de serrage admissible.
- La protection des pièces thermoplastiques contre l'écrasement.
- L'accessibilité de la zone d'insertion.

Une attention particulière sera portée à la coaxialité entre l'axe de l'outil chauffant et la position de l'insert.

## 9.6. Améliorations attendues

L'intégration de cet étau devrait permettre de passer d'un simple support de positionnement à un véritable système de maintien mécanique réglable.

Cette évolution doit apporter une meilleure stabilité de la pièce, faciliter les opérations successives et élargir les possibilités d'utilisation de la presse.

**La V2 ne constitue donc pas une simple modification esthétique : elle représente une évolution fonctionnelle de l'architecture mécanique, directement issue des observations réalisées lors des essais de la première version.**

---

# 10. Comparaison entre les deux versions

| Critère | AMR-3D V1 | AMR-3D V2 |
|---|---|---|
| Support de pièce | Support fixe | Étau réglable |
| Maintien | Positionnement sur le socle | Serrage mécanique |
| Guidage vertical | Intégré | Conservé |
| Outil chauffant | Intégré | Conservé |
| Adaptabilité | Selon le support | Selon l'ouverture de l'étau |
| Fabrication | Réalisée | Prévue prochainement |
| Validation | Essais réalisés | À réaliser |

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

Une démonstration vidéo permettra de présenter le fonctionnement de la première version, le mécanisme de déplacement et les opérations d'insertion thermique réalisées.

**Vidéo de démonstration :** à venir.

---

# 13. Conclusion

AMR-3D est un projet personnel de conception et de développement mécanique illustrant une démarche complète allant de l'identification d'un besoin technique à la réalisation et à la validation expérimentale d'un prototype fonctionnel.

La première version, désormais fabriquée et testée, a permis de confirmer la faisabilité de la solution proposée et de mettre en évidence plusieurs possibilités d'amélioration.

La deuxième version, dont le développement est prévu prochainement, intégrera un étau de serrage réglable destiné à améliorer le maintien des pièces et à rendre le dispositif plus polyvalent.

Cette démarche d'amélioration progressive témoigne de l'importance de l'expérimentation, de l'analyse des résultats et de l'évolution de la conception dans le développement d'une solution mécanique.

Le projet mobilise des compétences en conception mécanique, modélisation CAO, fabrication additive, assemblage, prototypage et validation expérimentale.

---

**Conception, modélisation, fabrication et développement : Amour Tamègnon AZONNAKPO**

**Projet personnel : AMR-3D**

*Concevoir. Fabriquer. Tester. Améliorer.*
