# Fiche mémo · DAC : le propriétaire décide
*Permis ou refusé ? · Famille DAC · Le propriétaire décide : ACL, délégation, dérive des droits, capabilities*

- **Définition.** Le propriétaire d’un objet décide, à sa discrétion, des droits des autres sujets, le plus souvent par une **ACL**.
- **Mécanismes.** ACL (liste attachée à l’objet), table d’autorisations, **capabilities** (jetons détenus par les sujets), DAC pur, étendu ou combiné.
- **Atouts.** Souplesse, granularité fine, facilité d’usage pour les équipes projet.
- **Limites.** Délégation en chaîne, **dérive des droits**, faible résistance aux menaces internes, conformité difficile à démontrer.
- **Bonnes pratiques.** Délégations encadrées, revues trimestrielles des ACL, journal des changements, complément par RBAC ou MAC.
- **Chiffre à retenir.** 15 gestionnaires × 8 dossiers × 3 personnes = **360** autorisations non validées.
- **Lecture de la matrice.** Par colonne : ACL d’un objet. Par ligne : capabilities d’un sujet.

**Cartes de cette famille :** [D01](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1D01.md) · [D02](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1D02.md) · [D03](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1D03.md) · [D04](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1D04.md) · [D05](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1D05.md) · [D06](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1D06.md) · [D07](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1D07.md) · incidents : [X03](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1X03.md) · [X04](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1X04.md)

---
[← Retour à l’index](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/README.md) · Collection La Vigie · UCUE-S5-4-1 · Modèles de contrôle d’accès · © 2026 SAS BEL’M DÉVELOPPEMENT
