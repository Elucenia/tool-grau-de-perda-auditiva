<!-- ELUCENIA technical documentation · grau-de-perda-auditiva · fr · no clinical/professional/rights approval -->

# Moyenne tonale et degré de perte auditive (OMS 2021)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/grau-de-perda-auditiva)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Oreille droite · 500 Hz

`od500`

dB HL · intervalle: -10–120

### Oreille droite · 1 000 Hz

`od1k`

dB HL · intervalle: -10–120

### Oreille droite · 2 000 Hz

`od2k`

dB HL · intervalle: -10–120

### Oreille droite · 4 000 Hz

`od4k`

dB HL · intervalle: -10–120

### Oreille gauche · 500 Hz

`oe500`

dB HL · intervalle: -10–120

### Oreille gauche · 1 000 Hz

`oe1k`

dB HL · intervalle: -10–120

### Oreille gauche · 2 000 Hz

`oe2k`

dB HL · intervalle: -10–120

### Oreille gauche · 4 000 Hz

`oe4k`

dB HL · intervalle: -10–120

## Édition de la méthode

WHO 2021 World Report on Hearing : PTA 4 fréquences 500/1000/2000/4000, meilleure oreille ; PTA 3 séparée

## Formule documentée

Moyenne sur quatre fréquences (OMS) = moyenne des seuils en conduction aérienne à 500, 1 000, 2 000 et 4 000 Hz. Moyenne sur trois fréquences = moyenne à 500, 1 000 et 2 000 Hz (classifications traditionnelles, comme Lloyd et Kaplan).

Le grade OMS est défini par la moyenne sur quatre fréquences de la meilleure oreille.

## Limites et population

La classification OMS de 2021 utilisée ici repose sur la moyenne de 500, 1000, 2000 et 4000 Hz dans la meilleure oreille et sur ses grades pour adultes ; la moyenne de trois fréquences affichée séparément ne doit pas être confondue avec cette méthode. Les seuils doivent provenir d’une audiométrie appropriée et être exprimés en dB HL, également appelés dB NA. Le grade numérique ne décrit pas à lui seul la capacité de communication, le contexte ou les besoins de réadaptation ; l’OMS elle-même souligne cette limite. La perte unilatérale et l’application pédiatrique exigent une interprétation spécifique et ne doivent pas être déduites du total adulte.

## Références

- [Chadha S, Kamenov K, Cieza A. The world report on hearing, 2021. Bull World Health Organ, 2021.](https://doi.org/10.2471/BLT.21.285643)

- [Organização Mundial da Saúde. World report on hearing, 2021.](https://www.who.int/publications/i/item/9789240020481)

- [WHO2021,WorldReportOnHearing,ISBN978-92-4-002048-1,primary-content mirror](https://soundhearing2030.org/pdf/World%20report%20on%20hearing.pdf)

- [WHO2021 official archive](https://iris.who.int/bitstream/handle/10665/339913/9789240020481-eng.pdf)

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
