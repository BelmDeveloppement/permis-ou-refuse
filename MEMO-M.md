# Fiche mémo · MAC : le système impose
*Permis ou refusé ? · Famille MAC · Labels, niveaux, compartiments, dominance, SELinux*

- **Définition.** Une politique centrale attribue un **label** (niveau + compartiments) à chaque sujet et chaque objet ; le système décide à chaque accès, sans discrétion de l’utilisateur.
- **Dominance.** Le sujet S domine l’objet O si niveau(S) ≥ niveau(O) **ET** compartiments(O) ⊆ compartiments(S).
- **Exemples.** SELinux (domaines et types), AppArmor (profils par programme), cloisonnement défense et santé.
- **Atouts.** Isolation forte, confinement d’un processus compromis, protection contre les erreurs humaines.
- **Limites.** Administration lourde, rigidité, une erreur de label bloque ou expose.
- **Exercice type.** Marc (Confidentiel, {Exploitation}) lit Bilan (Confidentiel, {Finance}) : **refusé**, le compartiment Finance manque.

**Cartes de cette famille :** [M01](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1M01.md) · [M02](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1M02.md) · [M03](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1M03.md) · [M04](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1M04.md) · [M05](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1M05.md) · [M06](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1M06.md) · [M07](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1M07.md) · incidents : [X07](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1X07.md) · [X08](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1X08.md)

---
[← Retour à l’index](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/README.md) · Collection La Vigie · UCUE-S5-4-1 · Modèles de contrôle d’accès · © 2026 SAS BEL’M DÉVELOPPEMENT
