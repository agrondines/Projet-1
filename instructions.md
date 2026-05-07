# Instructions — Comment je travaille sur ce projet

Ce fichier documente les préférences et habitudes de travail du propriétaire du projet.
Claude doit le lire en complément de `CLAUDE.md`.

## Flux de travail typique

1. Je décris ce que je veux changer ou ajouter
2. Claude **montre les modifications prévues** (diff ou explication claire) avant de toucher aux fichiers
3. Je valide ou demande des ajustements
4. Quand je suis satisfait, je dis **"commit and push"** et Claude exécute

Ne jamais committer ou pousser sans que j'aie dit explicitement de le faire.

## Contenu du site

- Les articles dans `ressources.html` sont **écrits manuellement en HTML**, puis affinés avec Claude
- Pas de CMS — tout est dans les fichiers HTML directement
- Le formulaire de contact/booking est géré par **Formspree** — ne pas modifier les endpoints

## Ce que Claude doit toujours faire

- Lire `CLAUDE.md` et ce fichier au début de chaque session
- Préserver toutes les modifications existantes
- Si un changement majeur risque d'affecter une autre partie du site, régler l'impact **avant** de présenter la modification
- Garder le site dans un état fonctionnel à tout moment — jamais pire qu'avant

## Style de communication

- Français et anglais sont les deux acceptés
- Réponses concises et directes
- Pas besoin de longues explications sauf si je pose une question

## Ce qu'on ne touche pas sans demande explicite

- Les animations existantes (3D ring, logoSpotlight, btnSpotlight, scroll animations)
- Les endpoints Formspree
- La structure de navigation
- Le fichier `politique.html` sauf si demandé

## Infos utiles

- Site en production sur https://sagaconseils.ca/
- Hébergé sur GitHub Pages, domaine custom via CNAME
- Projet solo — pas d'équipe, pas de branches multiples, on travaille sur `main`
