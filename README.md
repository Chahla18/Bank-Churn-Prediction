# Bank Customer Churn Prediction 🏦💡

Projet réalisé dans le cadre d'une analyse des données sur le churn des clients bancaires.  
L'objectif est de prédire si un client quittera la banque ou non, en utilisant un dataset contenant des informations démographiques, financières et comportementales.

---

## À Propos du Projet

Ce projet utilise le dataset **"Bank Customer Churn"**, un jeu de données utilisé pour prédire la fidélité des clients dans le secteur bancaire.  

Le but est de développer un modèle de machine learning capable d’estimer la probabilité qu’un client quitte la banque (**churn**).

### **Description des Données :**

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

### **Fichiers fournis :**

- **`train.csv`** : Jeu d’entraînement contenant la variable cible `Exited`.  
- **`test.csv`** : Jeu de test pour effectuer les prédictions.  
- **`sample_submission.csv`** : Exemple de soumission au format attendu.  

---

## Travailler sur le Projet

### **Cloner le Repository et Configurer l’environnement virtuel:**

```bash
git clone https://github.com/Chahla18/Bank-Churn-Prediction.git
cd bank-churn-prediction


python3 -m venv .venv_churn
source .venv_churn/bin/activate   # Sur Windows : .venv_churn\Scripts\activate
pip install -r requirements.txt
