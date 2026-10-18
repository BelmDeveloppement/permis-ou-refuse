# Fiche mémo · RBAC : les droits suivent la fonction
*Permis ou refusé ? · Famille RBAC · Rôles, matrices, séparation des tâches, hiérarchies, explosion de rôles*

- **Définition.** Les permissions sont attachées à des **rôles** ; les utilisateurs héritent de celles des rôles qu’on leur affecte.
- **Variantes.** Statique (core), hiérarchique (héritage), contraint (**séparation des tâches**), RBAC + ABAC, just-in-time.
- **Atouts.** Administration centralisée, audit lisible, moindre privilège, passage à l’échelle.
- **Limites.** Explosion de rôles quand on code le contexte ; sur-ingénierie si les rôles sont mal définis.
- **Chiffres du cas TMS.** 120 utilisateurs × 8 permissions = 960 cases ; avec 4 rôles : 4 × 8 + 120 = 152 éléments, soit une réduction de **84 %**.
- **Séparation des tâches.** Qui initie n’approuve pas ; qui saisit un paiement ne le valide pas.
- **Fraude au RIB.** 18 400 € ≈ 6,6 % de la marge de 280 k€ ; deux fraudes identiques dépassent 10 %.

**Cartes de cette famille :** [R01](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1R01.md) · [R02](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1R02.md) · [R03](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1R03.md) · [R04](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1R04.md) · [R05](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1R05.md) · [R06](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1R06.md) · [R07](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1R07.md) · incidents : [X05](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1X05.md) · [X06](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1X06.md)

---
[← Retour à l’index](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/README.md) · Collection La Vigie · UCUE-S5-4-1 · Modèles de contrôle d’accès · © 2026 SAS BEL’M DÉVELOPPEMENT
