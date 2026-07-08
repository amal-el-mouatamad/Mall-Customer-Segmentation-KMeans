# 🛍️ Segmentation des clients d'un centre commercial avec K-Means

## 📌 Présentation du projet

Ce projet applique l'algorithme de **K-Means Clustering** afin de segmenter les clients d'un centre commercial en fonction de leur **revenu annuel** et de leur **score de dépenses**.

L'objectif est d'identifier différents profils de clients pour aider les entreprises à mieux comprendre le comportement des consommateurs et à optimiser leurs stratégies marketing.

---

## 🎯 Objectifs

- Explorer le jeu de données.
- Nettoyer et prétraiter les données.
- Encoder les variables catégorielles.
- Analyser les corrélations entre les variables.
- Détecter les valeurs aberrantes.
- Normaliser les données avec **StandardScaler**.
- Déterminer le nombre optimal de clusters grâce à la méthode du coude (Elbow Method).
- Entraîner le modèle **K-Means**.
- Visualiser les différents segments de clients.

---

## 📊 Informations sur le jeu de données

**Nom :** Mall Customer Segmentation Dataset

- Nombre d'observations : **200**
- Nombre de variables : **4**
  
- Variables
- Sexe (Gender)
- Âge
- Revenu annuel (k$)
- Score de dépenses (1–100)

---

## 🛠 Technologies et bibliothèques utilisées

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 🤖 Processus de Machine Learning

1. Chargement du jeu de données
2. Analyse exploratoire des données (EDA)
3. Vérification des valeurs manquantes
4. Vérification des doublons
5. Suppression de l'identifiant du client (Customer ID)
6. Encodage de la variable **Gender**
7. Analyse des corrélations
8. Détection des valeurs aberrantes (Boxplot)
9. Normalisation des données avec **StandardScaler**
10. Détermination du nombre optimal de clusters (Elbow Method)
11. Entraînement du modèle **K-Means**
12. Prédiction des clusters
13. Visualisation des segments de clients

---

## 📈 Résultats

- Nombre optimal de clusters : **5**
- Algorithme utilisé : **K-Means Clustering**

---

## 📉Visualisations

### Matrice de corrélation
<img width="752" height="702" alt="image" src="https://github.com/user-attachments/assets/125a107d-7a63-4bd3-b469-348aa0c6233c" />

### Détection des valeurs aberrantes (Boxplot)
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/609763cb-c764-434c-83d8-d4a0f0c53fc3" />

### Méthode du coude (Elbow Method)

<img width="695" height="470" alt="image" src="https://github.com/user-attachments/assets/416f674b-b601-4338-aaa0-436ab1633dec" />

### Segmentation des clients
<img width="695" height="547" alt="image" src="https://github.com/user-attachments/assets/c5d85e24-5073-41fa-8885-0fc029efeb67" />

### Centres des clusters

<img width="695" height="547" alt="image" src="https://github.com/user-attachments/assets/940d4d7d-c706-44e2-a981-70e4ddcfa88c" />

---

## 📁 Structure du projet

```text
Mall-Customer-Segmentation-KMeans/
│
├── mall_customer_segmentation_kmeans.ipynb
├── Mall_Customers.csv
├── README.md
├── requirements.txt
└── images/
    ├── correlation_matrix.png
    ├── boxplot.png
    ├── elbow_method.png
    ├── customer_segmentation.png
    └── cluster_centers.png
```

---

## 🚀Améliorations futures

- Comparer les résultats avec le clustering hiérarchique.
- Appliquer la réduction de dimension (**PCA**) pour améliorer la visualisation.
- Tester différents nombres de clusters.
- Développer un tableau de bord interactif pour explorer les segments de clients.

---

## 👩‍💻 Author

**Amal El Mouatamad**

AI & Data Analytics Student

ISTA NTIC Rabat
