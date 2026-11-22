# Firas J.

Étudiant en **Master Data & IA à HETIC** (Paris).
Ce qui m'intéresse : construire des pipelines de données fiables, du fichier brut jusqu'à l'indicateur qui aide à décider.

🔎 **Je recherche une alternance en data / IA** : rythme 2 semaines en entreprise, 1 semaine à l'école.

## Compétences

- **Données** : Python (pandas, geopandas), SQL, NoSQL, Hadoop
- **Visualisation** : Power BI
- **Qualité des données** : règles de qualité écrites comme des tests, barrière de qualité, RGPD
- **Web** : HTML, CSS
- **Outils** : Git, GitHub (branches, pull requests, relectures)

## Projets

### Feux de forêt dans le Grand Est (HETIC, 2026)
Projet de groupe pour le SDIS du Bas-Rhin : où concentrer les moyens contre les départs de feu, et à quel niveau de danger lancer le dispositif renforcé.
→ [feux-de-foret-grand-est](https://github.com/lawsonboevirobert-boop/feux-de-foret-grand-est)

Ma part :
- **tout le nettoyage des données** : 9 sources (feux de forêt BDIFF, Météo des forêts, satellite NASA FIRMS, indice météo du feu Copernicus, BD Forêt, interventions des pompiers, calendrier…) transformées en tables propres, avec une barrière de qualité qui arrête le pipeline si une donnée est fausse (105 tests)
- l'indice de danger de feu calculé par département, pondéré par la surface de forêt
- un indicateur pour savoir où placer les moyens : 27 % des départs de feu dans 10 communes qui couvrent 8,3 % du département
- l'assemblage du jeu d'indicateurs de l'équipe (12 indicateurs) et des objectifs retenus
- les relectures de code de l'équipe, en relançant le code et en recalculant les chiffres

### Optimisation opérationnelle d'une chaîne GC-MS (HETIC, 2026, projet de groupe, dépôt privé)
Dosage de 16 polluants (HAP) dans des terres agricoles : calcul des temps de rétention et des ratios d'ions à partir des fichiers bruts de l'appareil.
Ma part : le contrôle qualité selon la norme COFRAC (± 0,23 ppm), avec des cartes de contrôle de Shewhart et l'analyse du biais.

### Agent de lecture de bons de commande (HETIC, 2026, projet de groupe, dépôt privé)
Un agent IA qui lit des bons de commande scannés, extrait les informations utiles, vérifie leur cohérence et prépare l'import dans le logiciel du laboratoire.
Ma part : participation à la conception en équipe.
