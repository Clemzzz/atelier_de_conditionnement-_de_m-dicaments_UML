# Atelier de conditionnement de médicaments — UML (R3.03 Analyse)

Projet collaboratif de modélisation UML pour le module **R3.03 Analyse** (IUT Caen — Département Informatique).

## Équipe

- Nathan Chaignon
- Clément Bazin
- Paul Maillard
- *(autres membres du groupe à compléter)*

## Structure du dépôt

```text
.
├── uml/
│   └── atelier_conditionnement.mdj   # Modèle StarUML du projet (à renommer GP_PRJ_nom1_... avant rendu)
├── docs/
│   ├── seance1_analyse.md            # Livrables Séance 1 : DCU, objets physiques (5-2) et informatiques (5-3)
│   └── seance2_architecture.md       # Livrables Séance 2 : 5-4, 5-6, déploiement (5-7), début classes (5-5)
└── README.md
```

## Avancement par séance

- [x] **Séance 1** : Diagramme de cas d'utilisation (5-1), liste des objets physiques (5-2), liste des objets informatiques (5-3)
- [x] **Séance 2** : Association aux ordinateurs (5-4), comparaisons technologiques (5-6), diagramme de déploiement (5-7), début diagramme de classes (5-5)
- [ ] **Séance 3** : Fin diagramme de classes (5-5), diagramme de séquence haut niveau (5-8)
- [ ] **Séance 4** : Diagramme de séquence bas niveau (5-9), finalisation du rapport PDF et de l'archive ZIP

## Bonnes pratiques Git pour StarUML (`.mdj`)

Un fichier `.mdj` est un fichier **JSON** généré par StarUML : deux modifications simultanées sur le même fichier peuvent provoquer des conflits difficiles à fusionner.

1. Toujours faire `git pull` **avant** d'ouvrir `uml/atelier_conditionnement.mdj` dans StarUML.
2. Prévenir le binôme / groupe quand on édite le `.mdj` (un seul éditeur à la fois sur le `.mdj`, pendant que les autres travaillent sur les fichiers Markdown/rapport dans `docs/`).
3. Enregistrer dans StarUML puis committer et pousser rapidement :
   ```bash
   git add uml/atelier_conditionnement.mdj docs/
   git commit -m "seance1: ajout DCU et listes objets physiques/informatiques"
   git push
   ```
