# Les Licences Open Source

## Liens

- [Licences](https://choosealicense.com/licenses/)
- [OSI](https://opensource.org/)
- [FSF](https://www.fsf.org/fr)
- [FSF france](https://www.fsffrance.org/)
- [Licences libres](https://fr.wikipedia.org/wiki/Licence_libre)
- [Open Source](https://fr.wikipedia.org/wiki/Open_source)

## Les organisations

### OSI - Open Source Initiative

* Organisation créée en 1998
* Objectif : promouvoir l’open source (libre accès au code, collaboration, adoption par les entreprises)
* Critères : conformité à la définition de l’open source (Open Source Definition)
* L’OSI valide certaines licences comme « open source » (GPL, MIT, Apache, etc.)
* Approche : pragmatique => l’important est que le code soit accessible, modifiable et redistribuable.

### FSF - Free Software Foundation

* Organisation fondée par Richard Stallman en 1985.
* Objectif : défendre la philosophie du « logiciel libre » (4 libertés fondamentales : utiliser, étudier, modifier, partager).
* Critères : conformité à la définition du logiciel libre.
* La FSF maintient et promeut ses propres licences, en particulier la GPL, la LGPL, l’AGPL et la GFDL.
* Approche : idéologique/éthique => priorité à la liberté des utilisateurs, même si cela limite certaines utilisations.

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

1. Liberté d’**exécuter** le programme pour tout usage.
2. Liberté d’**étudier** le fonctionnement du programme et de l’adapter à ses besoins (accès au code source requis).
3. Liberté de **redistribuer** des copies.
4. Liberté d’**améliorer** le programme et de publier ses modifications.

### Différence entre licences Open Source et Libres

La différence réside dans l'approche. En pratique les deux concepts sont assez similaire.
Les licences Libres sont Open Source en revanche quelques exceptions peuvent être Open mais non libre.

* Libre : approche éthique & philosophie, elle défend les libertés d'usage de l'utilisateur
* Open source : approche technique et pragmatique, elle défend l'aspect collaboratif l'ouverture du code

Exemple de licence Open mais non Libre : NOSA, APSL, RPL, RSPL, SOWPL...

## Les licences

# Tableau des licences libres et open source

| Domaine            | Licence                           | Libre (FSF) | Open Source (OSI) | Remarques principales |
|--------------------|-----------------------------------|-------------|-------------------|-----------------------|
| **Code logiciel**  | GPLv3 (GNU General Public License)| ✅ Oui       | ✅ Oui            | Copyleft fort, oblige à redistribuer sous GPL. |
|                    | LGPL (Lesser GPL)                 | ✅ Oui       | ✅ Oui            | Copyleft faible, tolère l’usage dans du code proprio. |
|                    | AGPL (Affero GPL)                 | ✅ Oui       | ✅ Oui            | Copyleft adapté aux logiciels SaaS. |
|                    | MIT                               | ✅ Oui       | ✅ Oui            | Très permissive, très populaire. |
|                    | Apache 2.0                        | ✅ Oui       | ✅ Oui            | Permissive, protège contre brevets. |
|                    | BSD (2-clause, 3-clause)          | ✅ Oui       | ✅ Oui            | Permissives, proches du MIT. |
|                    | Mozilla Public License (MPL 2.0)  | ✅ Oui       | ✅ Oui            | Copyleft faible, très utilisé (Firefox). |
|                    | NOSA 1.3 (NASA)                   | ❌ Non       | ✅ Oui            | Trop de restrictions (pas libre pour la FSF). |
|                    | Sybase Open Watcom                | ❌ Non       | ✅ Oui            | Oblige à publier les modifs même en interne. |
| **Documentation**  | GNU FDL (Free Documentation Lic.) | ✅ Oui       | ✅ Oui            | Utilisé pour Wikipédia avant migration en CC BY-SA. |
|                    | CC BY                             | ✅ Oui       | ✅ Oui            | Attribution obligatoire, permissive. |
|                    | CC BY-SA                          | ✅ Oui       | ✅ Oui            | Partage dans les mêmes conditions, proche d’un copyleft. |
|                    | CC0                               | ✅ Oui       | ✅ Oui            | Équivaut à un domaine public volontaire. |
| **Données**        | ODbL (Open Database License)      | ✅ Oui       | ✅ Oui            | Copyleft pour bases de données (ex : OpenStreetMap). |
|                    | Open Data Commons Attribution (ODC-BY) | ✅ Oui   | ✅ Oui            | Similaire à CC BY mais orienté données. |
| **Art/Création**   | CC BY-NC                          | ❌ Non       | ❌ Non            | Interdit l’usage commercial, pas libre ni open source. |
|                    | CC BY-ND                          | ❌ Non       | ❌ Non            | Interdit les modifications, pas libre ni open source. |
| **Mixte**          | EPL (Eclipse Public License)      | ✅ Oui       | ✅ Oui            | Copyleft faible, souvent utilisé pour projets Eclipse. |
|                    | RPL (Reciprocal Public License)   | ❌ Non       | ✅ Oui            | Trop de restrictions (usage interne limité). |


## Comment ajouter une licence à son code ?

Pour ajouter une licence à son code, rien de plus simple :

1. Selectionner la licence qui fonctionne le mieux avec la philosophie de son code :
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

## Comment retirer une licence ?

1. Il n'est pas possible de retirer une licence sur des versions déjà publiées
2. Il est possible de changer de licence sur les versions futures
3. Il est possible de supprimer l'accès à son dépôt publique
4. Il est également possible de publier son code sous plusieurs licences (double licences)

*Note : il faut avoir 100% des droits sur son code pour exercer ces actions.*

Et bien entendu communiquer avec transparence (à l'avance) ce type de changement majeur.

## Point sur les licences contaminantes

### Qu'est ce qu'une licence contaminante ?

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

## Résumé Licences

Les licences open source encadrent l’usage, la modification et la redistribution du code.
Elles vont des licences permissives (MIT, Apache) favorisant la diffusion, aux licences copyleft (GPL) qui protègent les libertés en imposant le partage du code dérivé.
Leur choix impacte la compatibilité avec d’autres projets et l’adoption par la communauté ou les entreprises.
Elles offrent des bénéfices : transparence, collaboration, réduction des coûts et pérennité du projet.
Bien choisie, une licence peut être un levier de diffusion et de confiance pour ton logiciel.
