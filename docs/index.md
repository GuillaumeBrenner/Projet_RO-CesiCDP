---
---
title: Diagramme de Gantt du Projet
layout: default
---

```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title       Projet Mobilité Multimodale Intelligente

    section Planification
    Définition des objectifs        :done,    des1, 2024-06-01, 2024-06-07
    Répartition des tâches          :done,    des2, 2024-06-08, 2024-06-14

    section Modélisation
    Modélisation formelle           :active,  des3, 2024-06-15, 2024-06-28
    Analyse de la complexité        :active,  des4, 2024-06-29, 2024-07-11

    section Développement
    Développement de l'algorithme   :des5,    2024-07-12, 2024-08-01
    Tests unitaires                 :des6,    2024-08-02, 2024-08-08

    section Implémentation et Tests
    Implémentation Jupyter          :des7,    2024-08-09, 2024-08-22
    Tests sur cas de test           :des8,    2024-08-23, 2024-09-06

    section Analyse des Résultats
    Étude statistique               :des9,    2024-09-07, 2024-09-20

    section Documentation et Présentation
    Rédaction de la documentation   :des10,   2024-09-21, 2024-10-03
    Préparation de la présentation  :des11,   2024-10-04, 2024-10-10
    Révision finale et soumission   :des12,   2024-10-11, 2024-10-17
