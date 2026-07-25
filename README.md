# Évaluation d'Impact : Programme Filets Sociaux au Cameroun

## 1. Objectif
Mesurer l'impact du programme Filets Sociaux sur les dépenses des ménages 
dans les régions du Nord et Extrême-Nord entre 2010 et 2014.

## 2. Données
Source : ECAM 4 2014 - INS Cameroun
Échantillon : 15 000 ménages

## 3. Méthodologie
Méthode : Différences-en-Différences sur Stata 17
Commande clé : `regress depenses traite apres diff, robust`
Variable d'impact : `diff = traite * apres`

## 4. Résultats Principaux
Le programme augmente les dépenses des ménages de **15 240 FCFA par an**.
Résultat significatif à 5%. 

## Fichiers du dépôt
- `impact_filets_sociaux.do` : Code Stata complet avec commentaires
- `tableau_resultats.png` : Résultat de la régression
