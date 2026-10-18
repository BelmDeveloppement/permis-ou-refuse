# Fiche mémo · Labels et intégrité : BLP, Biba, Clark-Wilson
*Permis ou refusé ? · Famille LABELS & INTÉGRITÉ · Confidentialité (BLP), intégrité (Biba) et transactions bien formées (Clark-Wilson)*

| Modèle | Objectif | Règle de lecture | Règle d’écriture |
|---|---|---|---|
| **Bell-LaPadula (BLP)** | Confidentialité | Pas de lecture vers le haut (propriété simple) | Pas d’écriture vers le bas (propriété *) |
| **Biba** | Intégrité | Pas de lecture vers le bas | Pas d’écriture vers le haut |
| **Clark-Wilson** | Intégrité « commerciale » | Les données contrôlées (CDI) ne bougent que par des procédures certifiées (TP) | Vérification périodique (IVP), séparation des tâches |

**Moyen mnémotechnique.** BLP protège le secret : *rien ne monte pour être lu, rien ne descend pour fuir*. Biba est son miroir : *rien de douteux ne monte, rien de douteux n’est lu par le fiable*.

**Propriété de tranquillité (BLP).** Les labels ne changent pas pendant l’utilisation (forme forte), ou seulement sans violer la politique (forme faible).

**Forces et limites.** BLP ignore l’intégrité ; Biba ignore la confidentialité ; Clark-Wilson est lourd à mettre en œuvre mais proche des processus d’entreprise. Les conventions de notation peuvent varier selon les ouvrages : vérifiez celle de votre support.

**Chez TransLor.** Classification Public < Interne < Confidentiel < Secret ; la comptabilité est protégée en intégrité ; les factures sont des CDI modifiées par le seul module de facturation.

**Cartes de cette famille :** [B01](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1B01.md) · [B02](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1B02.md) · [B03](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1B03.md) · [B04](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1B04.md) · [B05](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1B05.md) · [B06](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1B06.md) · [B07](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1B07.md) · incidents : [X01](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1X01.md) · [X02](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/J1X02.md)

---
[← Retour à l’index](https://github.com/BelmDeveloppement/permis-ou-refuse/blob/main/README.md) · Collection La Vigie · UCUE-S5-4-1 · Modèles de contrôle d’accès · © 2026 SAS BEL’M DÉVELOPPEMENT
