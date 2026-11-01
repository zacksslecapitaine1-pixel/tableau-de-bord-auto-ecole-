# Auto-École Le Patron — Tableau de bord de gestion

Application de gestion complète pour une auto-école, connectée à Supabase : inscriptions, élèves, planning, examens, paiements et alertes.

**Démo :** https://zacksslecapitaine1-pixel.github.io/tableau-de-bord-auto-ecole-/

## Fonctionnalités

- Vue générale avec indicateurs clés
- Inscriptions et suivi des élèves (inscrit, en formation, prêt pour examen, reçu, recalé)
- Planning des cours et gestion des examens
- Paiements (payé, partiel, impayé, en attente)
- Alertes et paramètres
- Thème sombre/clair

## Stack technique

React 18 (via CDN) · JavaScript · Supabase (base de données) · application monopage dans un seul fichier

## Architecture

```
tableau-de-bord-auto-ecole-/
└── index.html   application complète (interface, logique, connexion Supabase)
```

Les identifiants Supabase (URL et clé publique) sont saisis dans l'application et enregistrés localement dans le navigateur ; aucune clé n'est stockée dans le dépôt.

## Déploiement

Site statique publié depuis la branche `master` via GitHub Pages.

## Auteur

Créé par **Zackss (Oumate Razakou)** — [Dev.zak](https://dev-zak.netlify.app), développeur Full Stack & automatisation IA à Lomé, Togo.
