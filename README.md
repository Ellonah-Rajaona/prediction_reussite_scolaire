Ce projet personnel est dédié à la prédiction de la réussite scolaire à l'aide des facteurs socio-économiques tels que "le niveau d'étude des parents, le type de repas que les élèves prend, la participation au test de prépararion
# Pour ce projet j'ai suivi les étapes suivant :
* L'Analyse Exploratoire des Données (EDA)
* Le preprocessing (pré-traitement)
* Le split de données (séparation de données)
* l'entraînement de modèle
* L'évaluation et amélioration de modèle
* La prédiction

# Le but étant de prédire une variable cible binaire (Réussite / Échec), donc j'ai choisi deux algorithmes de classifications:
**La Régression Logistique** : Un algorithme parfaitement adapté aux cibles binaires grâce à sa fonction sigmoïde qui ramène les prédictions dans un intervalle entre 0 et 1.
**Le Random Forest** : Un modèle d'ensemble robuste, basé sur des arbres de décision, capable de capturer des relations non-linéaires complexes entre les facteurs sociaux et d'éviter qu'une seule variable ne dicte aveuglément la décision.

# Pour l'évaluation du modèle:
Accuracy a donné un score plus elevé pour l'algorithme random forest, par contre avec ROC_AUC c'est la regréssion logistique qui détient le meilleur score
alors j'ai choisi la regression logistique pour la prochaine prédiction

# J'ai chargé le modèle performant dans un fichier .pkl pour éviter de refaire tous les étapes pour la nouvelle prédiction
