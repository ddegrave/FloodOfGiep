# ThermiCity Builder (Prototype Web)
Prototype de **builder d'infrastructure thermique urbaine**.

Le joueur construit un réseau chaleur/froid sur une carte territoriale et doit l'équilibrer dans une vue technique.
Objectif: rendre le réseau robuste, acceptable politiquement et économiquement viable en passant de l'îlot pilote à l'échelle ville.

## Gameplay actuel
- Carte interactive avec nœuds (sources et clients).
- Connexion des nœuds (tronçons de réseau) avec coût dépendant de la distance.
- Saisons (hiver, printemps, été, automne) qui modifient les besoins chaud/froid.
- Leviers de gestion: stockage thermique, optimisation des pompes, rénovation des clients.
- KPI temps réel: budget, robustesse, acceptabilité, CO₂ évité, couverture territoriale.

## Boucle de jeu
1. Sélectionner un nœud et connecter source/client.
2. Renforcer l'infrastructure (stockage, pompes, rénovation).
3. Passer à la saison suivante.
4. Ajuster selon l'équilibre thermique, l'économie et l'acceptabilité.

## Jouer en local
- Ouvrir `index.html` dans un navigateur moderne.
- Ou lancer un serveur statique simple:
  - `python -m http.server 8080`
  - puis ouvrir `http://localhost:8080`

## Licence
MIT — voir `LICENSE`.
