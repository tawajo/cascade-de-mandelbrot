# Étude d'une Mesure Aléatoire

Ce projet explore l'étude des propriétés mathématiques et statistiques de certaines mesures aléatoires, à travers des simulations numériques et des analyses théoriques. Les résultats incluent des comparaisons avec des distributions connues et des observations sur les tendances statistiques.

## Contexte

Ce projet s'inscrit dans l'étude des processus aléatoires et des lois statistiques associées. Il comprend :

- La définition et simulation de lois (Bernoulli, Poisson).
- L'étude des attentes mathématiques et variances de certaines mesures aléatoires.
- La comparaison des résultats théoriques avec des simulations.

## Contenu

### Notions principales étudiées

1. **Simulation de mesures aléatoires :**
   - Génération de données aléatoires selon des lois spécifiques.
   - Exploration des fréquences et des distributions des variables étudiées.
2. **Analyse théorique :**
   - Calculs des espérances mathématiques et des variances.
   - Démonstrations sur des cas particuliers.
3. **Comparaison théorique-simulation :**
   - Illustration des concepts via des histogrammes.
   - Validation des hypothèses théoriques.

### Structure du projet

- **Section 1 :** Simulation pour une loi de Bernoulli.
- **Section 2 :** Simulation pour une loi de Poisson.
- **Section 3 :** Calcul des probabilités associées à des sous-divisions spécifiques.
- **Section 4 :** Étude de l'espérance et de la variance des mesures aléatoires.
- **Section 5 :** Étude récursive des variances avec une tentative d'approche algorithmique.

## Visualisations

Le projet utilise des visualisations via `matplotlib` pour représenter les distributions observées. Ces histogrammes permettent d'analyser visuellement les tendances pour différentes tailles d'échantillons.

## Exécution

### Prérequis

- Python 3.6 ou plus récent.
- Bibliothèques Python : `numpy`, `matplotlib`, `scipy`.

### Instructions

1. Cloner ce dépôt :
   ```bash
   git clone https://github.com/tawajo/mesure-aleatoire.git
   ```
2. Installer les dépendances :
   ```bash
   pip install -r requirements.txt
   ```
3. Exécuter le notebook :
   ```bash
   jupyter notebook Etude_mesure_aleatoire.ipynb
   ```

## Résultats

Les simulations montrent des comportements variés en fonction des paramètres (r, x, n). Ces résultats confirment certaines conclusions théoriques, notamment :

- Une convergence vers zéro pour certaines mesures lorsque les paramètres augmentent.
- Des tendances qui diffèrent en fonction de la relation entre les paramètres.

## Auteurs

- Joel Tagne Waffo
- Justin Moreau
