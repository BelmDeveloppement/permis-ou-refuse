# Fiche mémo · ABAC : des règles sur des attributs
*Permis ou refusé ? · Famille ABAC · Attributs, contexte, PEP / PDP / PAP / PIP, OPA et XACML*

- **Définition.** La décision évalue des règles sur les attributs du sujet, de la ressource, de l’action et de l’environnement (heure, lieu, appareil).
- **Architecture.** **PEP** applique, **PDP** décide, **PAP** administre les politiques, **PIP** fournit les attributs.
- **Outils.** XACML (standard OASIS), OPA / Rego (policy as code), conditions des politiques IAM du cloud.
- **Atouts.** Précision, agilité, Zero Trust ; évite l’explosion de rôles.
- **Limites.** Complexité, performance, qualité des attributs, audit moins immédiat.
- **Politique d’exercice.** PERMIS si rôle = gestionnaire ET appareil = géré ET heure entre 7 h et 20 h ET classification ≤ Confidentiel.

**Cartes de cette famille :** [A01](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1A01.md) · [A02](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1A02.md) · [A03](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1A03.md) · [A04](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1A04.md) · [A05](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1A05.md) · [A06](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1A06.md) · [A07](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1A07.md) · incidents : [X09](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1X09.md) · [X10](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1X10.md)

---
[← Retour à l’index](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/README.md) · Collection La Vigie · UCUE-S5-4-1 · Modèles de contrôle d’accès · © 2026 SAS BEL’M DÉVELOPPEMENT
