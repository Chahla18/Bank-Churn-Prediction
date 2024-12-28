# Bank Customer Churn Prediction 🏦💡


## À Propos du Projet

**Objectif** : Construire un modèle de machine learning pour prédire si un client quittera la banque (churn). L'objectif est de maximiser l'**AUC** (Area Under the Curve), la métrique utilisée pour évaluer les prédictions.

### **Description des Données :**

- **Train** : Contient les caractéristiques des clients et la variable cible **Exited** (1 = client a quitté, 0 = client est resté).
- **Test** : Contient les mêmes caractéristiques, mais sans la variable cible **Exited**. Il faut prédire cette variable pour soumettre les résultats. le jeu de test qu'on a represente seulement 20% de la base total (seulement le prof détient la base total).... 

---

Le dataset inclut les attributs suivants :  

- **Customer ID** : Identifiant unique pour chaque client.  
- **Surname** : Nom de famille du client.  
- **Credit Score** : Score de crédit du client.  
- **Geography** : Pays où réside le client (France, Espagne, Allemagne).  
- **Gender** : Sexe du client (Homme ou Femme).  
- **Age** : Âge du client.  
- **Tenure** : Nombre d’années de fidélité avec la banque.  
- **Balance** : Solde du compte bancaire.  
- **NumOfProducts** : Nombre de produits bancaires utilisés.  
- **HasCrCard** : Possession d’une carte de crédit (1 = Oui, 0 = Non).  
- **IsActiveMember** : Client actif ou non (1 = Oui, 0 = Non).  
- **EstimatedSalary** : Salaire estimé du client.  
- **Exited** : Variable cible (1 = Churn, 0 = Fidèle).  

#### Processus à suivre :
1. **Préparation des données** : Analyser et nettoyer les données (gestion des valeurs manquantes, encodage des variables catégorielles, normalisation si nécessaire).
2. **Modélisation** : Tester plusieurs modèles (régression logistique, forêts aléatoires, SVM, etc.) et ajuster les hyperparamètres pour optimiser l'AUC.
3. **Validation** : Utiliser l'AUC comme principale métrique pour évaluer les modèles sur un ensemble de validation.
4. **Soumission** : Soumettre les prédictions pour l'ensemble de test sans la variable **Exited**. L'évaluation des soumissions sera basée sur l'AUC.

#### Livrables :
- **Présentation** : Explique la méthodologie, les choix de modèles et les résultats obtenus.
- **Code** : Notebook bien documenté, incluant la préparation des données, la modélisation et les prédictions.

---

## Travailler sur le Projet

### **Cloner le Repository et Configurer l’environnement virtuel:**

```bash
git clone https://github.com/Chahla18/Bank-Churn-Prediction.git
cd bank-churn-prediction


python3 -m venv .venv_churn
source .venv_churn/bin/activate   # Sur Windows : .venv_churn\Scripts\activate
pip install -r requirements.txt
