# agronomie

## Résumé 
### Notebook d'exploration et de modélisations à partir de datasets issus de l'INRAE (UMR Agronomie). Analyse de différentes cultures de plantes, zones agricoles, modes de culture. Modélisation de rendements agricoles en fonction d'émission de gaz à effet de serre et d'utilisation de fertilisants azotés.

## Description du notebook
### Analyse univariée  
- Présentation des jeux de données
- Modes de conduite des cultures
- Zones agricoles
### Analyse de l'utilisation des intrants (de l'azote particulièrement)
- Différents types de culture  
- Utilisation de l'azote par type de culture  
- Utilisation des intrants vs. Rendement par zone et culture  
### Analyse de l'émission de gaz à effets de serre
- Émissions de gaz à effet de serre par zone
- Émissions de gaz à effet de serre moyennes par zone et culture
### Modélisation prédictive des rendements des cultures
- Jointure des datasets
- Choix du modèle
- Visualisation du scatterplot
- Distribution des résidus
- Feature importance
### Traitement du langage naturel
- Dataset des opérations de chantier
- Nettoyage des descriptions
- Nuage de mots

## Utilisation 
Pour exécuter ce notebook en local, suivre les étapes suivantes: 
1. **Cloner le repository** :
   ```bash
   git clone https://github.com/juuljul/agronomie.git
   cd agronomie

2. **Créer un environnment virtuel** :
   ```bash
   python3 -m venv env
   source env/bin/activate  # Sur Windows: env\Scripts\activate

3. **Installer les dépendances à l'aide du fichier requirements.txt** :
   ```bash
   pip install -r requirements.txt
  
## Crédits
#### Les datasets sont issus du dépôt de l'UMR Agronomie (INRAE)
**Article**: Référentiel de performances économiques, environnementales et sociales de pratiques culturales économes en intrants

**Auteurs**: Simon Buresi, Chantal Loyce, Rémy Ballot

**Subsidiary Authors**: Agence nationale de la recherche

**Date de publication**: Période de publication : 2022-01-01 à 2024-07-31

**Édition**: V1

**Mots-clés**: produit phytosanitaire, engrais azoté, conduite de la culture, rotation des cultures, analyse multicritère

**Langue**: Anglais

**Éditeur**: Recherche Data Gouv

**DOI**: [https://doi.org/10.57745/LCA116](https://doi.org/10.57745/LCA116)
