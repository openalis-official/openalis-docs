# Les Licences Open Source

![logo OSI](https://i0.wp.com/opensource.org/wp-content/uploads/2023/03/cropped-OSI-horizontal-large.png?fit=640%2C229&ssl=1)

## Liens

- [Licences](https://choosealicense.com/licenses/)
- [OSI](https://opensource.org/)
- [FSF](https://www.fsf.org/fr)
- [FSF france](https://www.fsffrance.org/)
- [Licences libres](https://fr.wikipedia.org/wiki/Licence_libre)
- [Open Source](https://fr.wikipedia.org/wiki/Open_source)
- [Fair code](https://faircode.io/)
- [Fair core](https://fcl.dev/)
- [Fair source](https://fair.io/)
- [FSL](https://fsl.software/)

## Introduction

Les éditeurs de logiciels sont nécessairement amenés à penser leur modèle économique et le mode de diffusion de leur logiciel.

L'Open Source est une des solutions à disposition des éditeurs pour répondre à ces enjeux.

Ce document a pour objectif de donner les clés à celles et ceux qui souhaitent en savoir plus sur cette solution, comment en tirer parti et comment la mettre en oeuvre.

## C'est quoi l'Open Source ?

L'Open Source est une méthode de développement où le code ("nommé les sources") est partagé 
dans une optique de transparence et d'innovation collective.

Ce partage est cadré selon les modalités de la licence choisie pour protéger l'oeuvre ainsi que les droits de l'éditeur et de l'utilisateur.

Des organisations existent comme l'OSI et la FSF pour définir et publier ces licences.

## Quels sont les avantages et les inconvénients du modèle Open ?

### Avantages (utilisateur)

*Pour les versions communautaires :*

* **Transparence** :
  - Le code peut être audité en permanence et par tout le monde
  - Cela permet notamment de détecter rapidement les failles et les corriger
  - Favorise une relation de confiance

* **Maîtrise** :
  - Permet d'adapter le logiciel à son contexte (si on en a la compétence)
  - Permet d'intégrer le logiciel sans restriction

* **Économies** :
  - Vous permet de tester le logiciel rapidement (sans demande de démonstration ou de licence d'essai)
  - Permet de ne pas subir l'inflation du coût de licence propriétaire

* **Maintenabilité** :
  - permet à n'importe qui de contribuer
  - possibilité de faire appel à d'autres entreprises pour maintenir la solution

### Avantages (éditeur)

* **Contribution Communautaire** :
  - Lorsqu'on arrive à fédérer une communauté, il est possible de récupérer leurs contributions

* **Diffusion massive** :
  - L'accès étant facilité, le produit peut se retrouver rapidement utilisé dans beaucoup de contextes

* **Valeurs fortes** :
  - Défendre l'accessibilité et le partage sont des messages forts envoyés à vos utilisateurs

### Inconvénients (utilisateur)

* **Support faible ou manquant** :
  - Selon le projet et le "business model" de l'éditeur, la version communautaire du logiciel peut être délaissée (sans support)

* **Expertise** :
  - Les compétences nécessaires à la maintenance du logiciel peuvent demander une certaine expertise

### Inconvénients (éditeur)

* **Fork :**
  - Risques de fork, souvent lorsque l'on change de licence ou de "business model" ou même d'orientation produit.
  La communauté peut être tentée de créer un clone du projet et le faire vivre de son côté.

* Le code étant lisible par tous, une certaine rigueur de développement est nécessaire


## Modèles économiques de L'Open

Comment vivre de l'Open Source si tout le monde peut copier mon code et l'utiliser ?

Il existe plusieurs manières de parvenir à générer du chiffre d'affaires avec un logiciel Open.

Premièrement chaque entreprise est libre de définir son business modèle et en voici quelques axes communs aux éditeurs du logiciel libre :

* **SaaS** (abonnements au service en ligne) 
* **Services** (intégration des outils dans le SI du Client)
* **Formations**
* **Conseil et consulting** (expertise dans un domaine)
* **Création d'une communauté** (récupération des contributions externes)
* **Support logiciel**
* **Dons**
* **Modèle dérivé** : Open Core, Double licences ou encore Fair-core.

  - Il s'agit ici de publier son code avec une partie communautaire et une partie propriétaire
  - Ceci permettant de se rémunérer sur la licence propriétaire tout en bénéficiant des contributions externes sur la partie Open
  - Permet de continuer de partager sa solution gratuitement
  - En général, la version communautaire est plus limitée en fonctionnalité pour attirer le client vers le choix du propriétaire

* **Partenariats**

## Différentes variantes du modèle Open-source

* **Open Source** :
  - Axé sur le partage du code à tous
* **Libre** :
  - Axé sur l'absence de contrainte pour les utilisateurs
* **Open Core** :
  - Axé sur un coeur Open Source et des fonctionnalités propriétaires
* **Dual Licensing** :
  - Axé sur deux versions différentes du logiciel (une open et une propriétaire)
* **Freemium Open Source** :
  - Axé sur la modularité, la base est Open mais les modules peuvent être propriétaires
* **Alternatives anti-cloud (SSPL & BSL)** :
  - Pour se protéger des fournisseurs de cloud en ajoutant des restrictions sur la partie commerciale
* **Fair-code** :
  - Approche qui se veut être un entre deux entre la partie open et propriétaire

## Les organisations principales

### OSI - Open Source Initiative

* Organisation créée en **1998**
* **Objectif** : promouvoir l’open source (libre accès au code, collaboration, adoption par les entreprises)
* **Critères** : conformité à la définition de l’open source (Open Source Definition)
* **L’OSI valide** certaines licences comme « open source » (GPL, MIT, Apache, etc.)
* **Approche** : pragmatique => l’important est que le code soit accessible, modifiable et redistribuable.

### FSF - Free Software Foundation

* Organisation fondée par Richard **Stallman en 1985**.
* **Objectif** : défendre la philosophie du « logiciel libre » (4 libertés fondamentales : utiliser, étudier, modifier, partager).
* **Critères** : conformité à la définition du logiciel libre.
* **La FSF maintient et promeut ses propres licences**, en particulier la GPL, la LGPL, l’AGPL et la GFDL.
* **Approche** : idéologique/éthique => priorité à la liberté des utilisateurs, même si cela limite certaines utilisations.

### Le Fair-code

C'est **un mouvement récent** alternatif qui se positionne entre l'open source et le propriétaire.
Principe : le code est ouvert (lisible, modifiable), mais son usage commercial est restreint.

Gratuit et libre pour un usage personnel, éducatif ou non-commercial.
Mais si une entreprise veut l’utiliser pour en tirer profit, elle doit payer une licence ou souscrire à un contrat commercial.

C’est donc un modèle de licence hybride : ouverture du code + modèle économique durable pour les créateurs.

Exemples de projets fair-code :

Fair-Core License (FCL-1.0.0) : "usage non commercial libre, usage commercial sous conditions".

Dans ce concept général, on y retrouve :

- Le Fair-Source : Formalise le concept de DOSP (Publication Open Source Différée)
- Le Fair-core Licence : Un modèle similaire à l'Open Core applicable au Fair-source
- Le Functional Source Licence : Une licence officielle correspondant au modèle Fair-code


## Choisir sa licence

### Critères d'une licence open source

10 critères fondamentaux :

1. **Libre redistribution** : Le logiciel peut être redistribué sans frais.
2. **Accès au code source** : Le code source doit être disponible pour tous.
3. **Autorisation de création d'œuvres dérivées** : Les utilisateurs ont le droit de modifier le code et de distribuer les versions modifiées.
4. **Intégrité du code source de l'auteur** : Les modifications doivent être distinctes du travail initial, sans interdire les modifications.
5. **Absence de discrimination** : Aucune restriction ne peut cibler des personnes, groupes ou domaines d'application spécifiques.
6. **Distribution de la licence** : Les droits attachés au programme s'appliquent à tous ceux qui reçoivent le logiciel.
7. **Licence non spécifique à un produit** : Les droits ne dépendent pas d'un produit particulier dans une distribution.
8. **Licence ne restreignant pas d'autres logiciels** : La licence ne doit pas imposer de restrictions aux autres logiciels distribués avec le programme.
9. **Neutralité technologique** : Aucune clause ne doit dépendre d'une technologie ou d'un style d'interface spécifique.
10. **Compatibilité avec d'autres licences** : Les licences doivent permettre la combinaison avec d'autres licences, selon les types (permissives ou copyleft).

### Critères d'une licence libre

4 libertés fondamentales :

1. Liberté d’**utiliser/exécuter** le programme pour tout usage.
2. Liberté d’**étudier** le fonctionnement du programme et de l’adapter à ses besoins (accès au code source requis).
3. Liberté de **redistribuer** des copies.
4. Liberté d’**améliorer/modifier** le programme et de publier ses modifications.

### Différence entre licences Open Source et Libres

La différence réside dans l'approche. En pratique les deux concepts sont assez similaires.
Les licences Libres sont Open Source en revanche quelques exceptions peuvent être Open mais non libre.

* Libre : approche éthique & philosophie, elle défend les libertés d'usage de l'utilisateur
* Open source : approche technique et pragmatique, elle défend l'aspect collaboratif l'ouverture du code

Exemple de licence Open mais non Libre : NOSA, APSL, RPL, RSPL, SOWPL...


## Comparatif des types de licences : Libre / Open Source / Fair-code

| Critère                  | **Logiciel Libre** 🐧 (FSF) | **Open Source** 🔓 (OSI) | **Fair-code** ⚖️ (Source available) |
|---------------------------|-----------------------------|---------------------------|-------------------------------------|
| **Philosophie**          | Défend la **liberté des utilisateurs** (les 4 libertés : utiliser, étudier, modifier, partager). | Vise la **qualité, la collaboration et l’adoption** par les entreprises, sans charge idéologique forte. | Vise la **justice pour les créateurs** : code ouvert mais usage commercial restreint. |
| **Usage commercial**     | Oui, totalement libre.      | Oui, totalement libre.    | Non libre : usage commercial **soumis à conditions** (contrat, licence payante). |
| **Accès au code**        | Oui, obligatoire.           | Oui, obligatoire.         | Oui, obligatoire, mais redistribution limitée. |
| **Redistribution**       | Oui, parfois avec obligation de copyleft (GPL). | Oui, sans restriction.    | Possible mais **restreinte** (pas pour SaaS ou services commerciaux sans accord). |
| **Exemples de licences** | GPL, AGPL, LGPL, MPL.       | MIT, Apache 2.0, BSD, EPL.| FCL (Fair-Core License), BSL (Business Source License), SSPL (MongoDB), Elastic License 2.0, Redis Source Available License. |
| **Exemples de projets**  | Linux, WordPress, LibreOffice, GIMP. | Kubernetes, React, PostgreSQL, Eclipse. | MongoDB (SSPL), ElasticSearch (Elastic License 2.0), Redis modules (RSAL), Sentry (BSL), Graylog. |
| **Forces**               | Garantit les libertés fondamentales. | Favorise l’innovation et l’adoption massive. | Protège les créateurs face aux géants du cloud. |
| **Limites**              | Perçu comme trop radical pour certains usages commerciaux. | Permet la captation par les Big Tech sans retour aux auteurs. | Pas reconnu comme open source par l’OSI → souvent critiqué comme “faux libre”. |


## Tableau résumé de comparaison de licences

| Domaine            | Licence                           | Libre (FSF) | Open Source (OSI) | Fair-code | Remarques principales |
|--------------------|-----------------------------------|-------------|---------------------|-----------|-----------------------|
| **Code logiciel**  | GPLv3 (GNU General Public License)| ✅ Oui      | ✅ Oui              | ❌ Non    | Copyleft fort, oblige à redistribuer sous GPL. |
|                    | LGPL (Lesser GPL)                 | ✅ Oui      | ✅ Oui              | ❌ Non    | Copyleft faible, tolère l’usage dans du code propriétaire. |
|                    | AGPL (Affero GPL)                 | ✅ Oui      | ✅ Oui              | ❌ Non    | Copyleft adapté aux logiciels SaaS. |
|                    | MIT                               | ✅ Oui      | ✅ Oui              | ❌ Non    | Très permissive, très populaire. |
|                    | Apache 2.0                        | ✅ Oui      | ✅ Oui              | ❌ Non    | Permissive, protège contre brevets. |
|                    | BSD (2-clause, 3-clause)          | ✅ Oui      | ✅ Oui              | ❌ Non    | Permissives, proches du MIT. |
|                    | Mozilla Public License (MPL 2.0)  | ✅ Oui      | ✅ Oui              | ❌ Non    | Copyleft faible, très utilisé (Firefox). |
|                    | NOSA 1.3 (NASA)                   | ❌ Non      | ✅ Oui              | ❌ Non    | Trop de restrictions (pas libre pour la FSF). |
|                    | Sybase Open Watcom                | ❌ Non      | ✅ Oui              | ❌ Non    | Oblige à publier les modifs même en interne. |
|                    | Fair-Core License (FCL)           | ❌ Non      | ❌ Non              | ✅ Oui    | Code ouvert mais usage commercial restreint. |
|                    | Business Source License (BSL)     | ❌ Non      | ❌ Non              | ✅ Oui    | Code source visible, restrictions commerciales. |
|                    | Server Side Public License (SSPL) | ❌ Non      | ❌ Non              | ✅ Oui    | Code ouvert, restrictions pour SaaS. |
|                    | Elastic License 2.0               | ❌ Non      | ❌ Non              | ✅ Oui    | Licence source available pour ElasticSearch/Kibana. |
|                    | Redis Source Available License    | ❌ Non      | ❌ Non              | ✅ Oui    | Restrictions commerciales sur modules Redis. |
| **Documentation**  | GNU FDL (Free Documentation Lic.) | ✅ Oui      | ✅ Oui              | ❌ Non    | Utilisé pour Wikipédia avant migration en CC BY-SA. |
|                    | CC BY                             | ✅ Oui      | ✅ Oui              | ❌ Non    | Attribution obligatoire, permissive. |
|                    | CC BY-SA                          | ✅ Oui      | ✅ Oui              | ❌ Non    | Partage dans les mêmes conditions, proche d’un copyleft. |
|                    | CC0                               | ✅ Oui      | ✅ Oui              | ❌ Non    | Équivaut à un domaine public volontaire. |
| **Données**        | ODbL (Open Database License)      | ✅ Oui      | ✅ Oui              | ❌ Non    | Copyleft pour bases de données (ex : OpenStreetMap). |
|                    | Open Data Commons Attribution (ODC-BY) | ✅ Oui | ✅ Oui              | ❌ Non    | Similaire à CC BY mais orienté données. |
| **Art/Création**   | CC BY-NC                          | ❌ Non      | ❌ Non              | ❌ Non    | Interdit l’usage commercial, pas libre ni open source. |
|                    | CC BY-ND                          | ❌ Non      | ❌ Non              | ❌ Non    | Interdit les modifications, pas libre ni open source. |
| **Mixte**          | EPL (Eclipse Public License)      | ✅ Oui      | ✅ Oui              | ❌ Non    | Copyleft faible, souvent utilisé pour projets Eclipse. |
|                    | RPL (Reciprocal Public License)   | ❌ Non      | ✅ Oui              | ❌ Non    | Trop de restrictions (usage interne limité). |


## Comment ajouter une licence à son code ?

Pour ajouter une licence à son code, rien de plus simple :

1. Sélectionner la licence qui fonctionne le mieux avec la philosophie de son code :
  * Permissive ? (MIT, Pache 2.0, BSD...)
  * Copyleft fort ? (GPL, AGPL, ...)
  * Copyleft faible ? (LGPL, MPL, ...)
2. Ajouter un fichier "LICENCE" ou "COPYING" à la racine de son dépôt logiciel
  * Copier le contenu de la licence officielle (en anglais) dans ce fichier
3. Ajouter un en-tête de licence dans les fichiers source importants :
  * Exemple MIT :
```
# Copyright (c) 2024 Nom Auteur
# Licensed under the MIT License. See LICENSE file in the project root for details.
```
4. Ajouter une section "Licence" dans son README :
  * Exemple :
```
## Licence

Ce projet est distribué sous la licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.
```

En bonus, sous Github, Gitlab... tu peux ajouter directement une licence depuis les fonctionnalités de l'interface. 

Il est aussi important de communiquer avec transparence la licence choisie pour son code.

## Gérer les contributions

Définissez votre de fonctionnement concernant les contributions externes.

Ajoutez un fichier "CONTRIBUTING" à la racine de vos sources pour définir les modalités de contribution.

## Comment retirer une licence ?

1. Il n'est pas possible de retirer une licence sur des versions déjà publiées
2. Il est possible de changer de licence sur les versions futures
3. Il est possible de supprimer l'accès à son dépôt public
4. Il est également possible de publier son code sous plusieurs licences (double licences)

*Note : il faut avoir 100% des droits sur son code pour exercer ces actions.*

Et bien entendu communiquer avec transparence (à l'avance) ce type de changement majeur.

## Point sur les licences "réciproques" ou "contaminantes"

### L'objectif

On parle de licence contaminante lorsqu’une licence impose que tout logiciel dérivé ou tout code combiné avec celui-ci soit distribué sous la même licence.

L’idée est de garantir que les libertés du logiciel soient préservées dans toutes les versions, modifications et redistributions.

Le terme « contaminant » est souvent utilisé par les éditeurs propriétaires (un peu péjoratif). La FSF préfère le terme copyleft.

### Conséquences

Les licences contaminantes (GPL) protègent les libertés des utilisateurs mais peuvent freiner l’adoption par les entreprises qui veulent intégrer le code dans des produits propriétaires.

Les licences permissives (MIT, Apache) sont souvent préférées pour favoriser une large adoption, même au prix d’un risque d’appropriation par des acteurs fermés.

### Exemples

**Copyleft fort (très contaminant) :**

Exemple : GPLv2, GPLv3

Toute redistribution (modifiée ou combinée) doit être sous GPL.

Impossible de combiner avec du code propriétaire sans ouvrir celui-ci.

**Copyleft faible (moins contaminant) :**

Exemple : LGPL, MPL

Tu peux utiliser la librairie dans un logiciel propriétaire sans que ton logiciel devienne libre, tant que tu respectes certaines conditions (lien dynamique, publication des modifs sur la librairie elle-même).

**Sans copyleft (permissives, non contaminantes) :**

Exemple : MIT, BSD, Apache 2.0

Tu peux intégrer du code dans un projet propriétaire sans obligation de redistribuer sous la même licence.


## Mettre en place de l'Open Core

Une solution avantageuse si l'on veut protéger sa propriété intellectuelle sur certaines fonctionnalités.

On ne montre que la partie communautaire, mais on garde caché la partie propriétaire.

Exemple de projet : Gitlab

## Mettre en place une double licence

Peut-être la méthode la plus simple en termes de maintenabilité de dépôt si l'on veut avoir un logiciel open pour la communauté et un propriétaire pour les entreprises tout en concervant une certaine transparance.

Mais elle inclut quelques contraintes :

* Nécessite de bien choisir sa licence copyleft (doit poser une contrainte de "contamination")
* Sa licence commerciale doit être formalisée comme une solution au copyleft
* Un contrat de licence doit être mis en place pour les contributions externes ("CLA" = Contributeur Licence Agreement) permettant ainsi de l'utiliser avec votre licence propriétaire.

1. Placez un ou deux fichiers de LICENCE à la racine de votre projet en explicitant les modalités d'usage.
2. Écrire un fichier "CONTRIBUTING" en y indiquant le lien vers la signature du CLA

Exemples de projet : MySQL

## Résumé Licences Open

Les licences Open Source encadrent l’usage, la modification et la redistribution du code.

Elles vont des licences permissives (MIT, Apache) favorisant la diffusion, aux licences copyleft (GPL) qui protègent les libertés en imposant le partage du code dérivé.

Leur choix impacte la compatibilité avec d’autres projets et l’adoption par la communauté ou les entreprises.

Elles offrent des bénéfices : transparence, collaboration, réduction des coûts et pérennité du projet.

Bien choisie, une licence peut être un levier de diffusion et de confiance pour ton logiciel.

## Conseils

Il est toujours judicieux de faire appel à un cabinet spécialisé en licence open source / droit des logiciels et Propriété Intellectuelle si vous n'êtes pas sûr de vous.

Inspirez-vous de projets existants réputés pour définir votre business model et la mise en place d'une licence.
