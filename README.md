# Atelier de conditionnement de médicaments — UML (R3.03 Analyse)

Projet collaboratif de modélisation UML pour le module **R3.03 Analyse** (IUT Caen — Département Informatique).

## Équipe

- Nathan Chaignon
- Clément Bazin
- Paul Maillard

*(Identifiants rendu : `NUM = TD1` · `GP = 1C` — Échéance : 20/12/2026 à 23h59)*

## Structure du dépôt

```text
.
├── uml/
│   └── atelier_conditionnement.mdj       # Modèle StarUML (DCU, Déploiement, Classes)
├── docs/
│   ├── seance1_analyse.md                # Livrables Séance 1 : DCU (5-1), objets physiques (5-2) et informatiques (5-3)
│   └── seance2_architecture_classes.md   # Livrables Séance 2 : ordinateurs (5-4), technos (5-6), déploiement (5-7), classes (5-5)
└── README.md
```

## Avancement par séance

- [x] **Séance 1** : Diagramme de cas d'utilisation (5-1), liste des objets physiques (5-2), liste des objets informatiques (5-3)
- [x] **Séance 2** : Association aux ordinateurs (5-4), comparaisons technologiques (5-6), diagramme de déploiement (5-7), diagramme de classes V1 (5-5)
- [ ] **Séance 3** : Affinage diagramme de classes (5-5), diagramme de séquence haut niveau (5-8)
- [ ] **Séance 4** : Diagramme de séquence bas niveau (5-9), finalisation du rapport PDF et de l'archive ZIP

## Bonnes pratiques Git pour StarUML (`.mdj`)

Un fichier `.mdj` est un fichier **JSON** généré par StarUML : deux modifications simultanées sur le même fichier peuvent provoquer des conflits difficiles à fusionner.

1. Toujours faire `git pull` **avant** d'ouvrir `uml/atelier_conditionnement.mdj` dans StarUML.
2. Prévenir le binôme / groupe quand on édite le `.mdj` (un seul éditeur à la fois sur le `.mdj`, pendant que les autres travaillent sur les fichiers Markdown/rapport dans `docs/`).
3. Enregistrer dans StarUML puis committer et pousser rapidement :
   ```bash
   git add uml/atelier_conditionnement.mdj docs/
   git commit -m "seance2: ..."
   git push
   ```
