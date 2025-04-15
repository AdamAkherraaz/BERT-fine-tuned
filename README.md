# Projet d'Analyse de Sentiment Multiclasse avec BERT

## Aperçu
Ce projet vise à implémenter et fine-tuner un modèle BERT pour l'analyse de sentiment multiclasse. L'objectif est de classifier des textes courts (comme des tweets ou des commentaires) dans trois catégories de sentiment : négatif (0), neutre (1) et positif (2).

## Dataset
Le dataset utilisé est "multiclass-sentiment-analysis-dataset" de Sp1786, qui contient des textes courts annotés avec leur sentiment correspondant. 

Caractéristiques du dataset:
- **Format**: CSV
- **Colonnes principales**: 'text' (le texte) et 'label' (le sentiment)
- **Classes**: 
  - 0: Sentiment négatif
  - 1: Sentiment neutre
  - 2: Sentiment positif
- **Taille**: Plus de 31 000 entrées

## Structure du Projet