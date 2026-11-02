# 📊 NexaStore 2024-2025 : analyse des ventes avec Power BI

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power_Query-217346?style=for-the-badge)
![DAX](https://img.shields.io/badge/DAX-6D14EB?style=for-the-badge)

##  Le projet

La direction de NexaStore voulait savoir **comment se porte l'activité en 2024-2025** et **quels leviers permettraient d'augmenter le chiffre d'affaires réellement encaissé**.

J'ai analysé **18 049 commandes** et **4 000 clients** sur 24 mois, puis j'ai présenté mes résultats et mes recommandations à la direction.

##  Ce que j'ai fait

1. **Nettoyage des données (Power Query)** : harmonisation des canaux de vente (6 libellés → 3), suppression de 85 doublons, conversion des dates et des remises, création d'une colonne de montant net après remise.
2. **Modélisation** : modèle en étoile avec 1 table de faits (Ventes) et 4 dimensions (Clients, Produits, Magasins, Calendrier).
3. **Mesures DAX** : CA livré, CA de l'année précédente, évolution, taux de retour, classement des produits.
4. **Rapport interactif de 4 pages** : Synthèse, Ventes, Clients, Rentabilité.

##  Ce que j'ai découvert

- Le CA livré progresse de **+11,3 %** en 2025.
- Le **4ᵉ trimestre** représente **36 %** du CA annuel.
- **20 % des clients** génèrent **47,5 %** du CA.
- Le **Web** a presque **2 fois plus de retours** que le magasin (8,66 % contre 4,91 %).
- La **carte de fidélité** ne change pas les achats : même panier moyen (212,6 €) avec ou sans carte.

##  Mes recommandations

- Réduire les retours Web (fiches produits plus complètes, motif de retour obligatoire).
- Préparer le 4ᵉ trimestre dès octobre (stocks, équipes, campagnes).
- Fidéliser les meilleurs clients et revoir les avantages de la carte de fidélité.

##  Fichiers

- `ProjetPOWERBI.pbix` : le rapport Power BI
- `NexaStore_Synthese_Power_Query.pdf` : le détail du nettoyage des données
- `NexaStore_Presentation_Direction.pptx` : la présentation à la direction

---

 Projet réalisé par **Kany Sissako**, Bachelor Intelligence Artificielle & Business, Nexa Digital School · [LinkedIn](https://www.linkedin.com/in/kany-sissako-8a18a5348)
