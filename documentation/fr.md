<!-- ELUCENIA technical documentation · nexus-coluna-cervical · fr · no clinical/professional/rights approval -->

# Critères NEXUS (rachis cervical)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/nexus-coluna-cervical)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Douleur à la palpation de la ligne médiane postérieure du rachis cervical

`dor`

### Déficit neurologique focal

`deficit`

### Altération du niveau de conscience

`alerta`

### Signes d’intoxication

`intox`

### Lésion douloureuse distrayante (p. ex., fracture d’un os long, brûlure étendue)

`distrativa`

## Édition de la méthode

NEXUS/Hoffman 2000 : 5 critères de faible risque ; règle cervicale originale

## Formule documentée

L’imagerie peut être omise lorsque tous les critères sont remplis : pas de douleur médiane postérieure, déficit focal, intoxication ou lésion douloureuse distractive ; vigilance normale. Tout signe positif indique l’imagerie.

## Limites et population

La règle NEXUS 2000 a été étudiée chez des patients ayant subi une radiographie cervicale après un traumatisme fermé. La classification en faible probabilité exige simultanément les cinq critères ; l’étude a rapporté des lésions non détectées par la règle, donc un résultat négatif n’assure pas l’absence de lésion. L’âge, les exclusions et l’application aux sous-groupes doivent être vérifiés dans le protocole intégral.

## Références

- [Hoffman JR et al. Validity of a set of clinical criteria to rule out injury to the cervical spine in patients with blunt trauma. N Engl J Med, 2000.](https://doi.org/10.1056/NEJM200007133430203)

- [Stiell IG et al. The Canadian C-Spine Rule versus the NEXUS low-risk criteria in patients with trauma. N Engl J Med, 2003.](https://doi.org/10.1056/NEJMoa031375)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Faible risque : imagerie du rachis cervical non nécessaire

Les cinq critères de faible risque ont tous été remplis.


### 2

Imagerie du rachis cervical indiquée

Maintenir l’immobilisation du rachis jusqu’à l’évaluation par imagerie.


### 3

Imagerie du rachis cervical indiquée

Maintenir l’immobilisation du rachis jusqu’à l’évaluation par imagerie.

