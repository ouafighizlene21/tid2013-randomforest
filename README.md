# 🌳 tid2013-randomforest  
Random Forest classifier applied to the TID2013 dataset to distinguish reference vs. distorted images based on basic image features.  
Classification d’images TID2013 avec Random Forest : différencier les images de référence et les images dégradées à partir de caractéristiques simples.

---

## 📁 Dataset — TID2013

- 25 reference images  
- 3000 distorted images (24 types × 5 niveaux de distorsion)
- Source officielle : [http://www.ponomarenko.info/tid2013.htm](http://www.ponomarenko.info/tid2013.htm)

---

## ⚙️ Model — Random Forest

- Modèle : `RandomForestClassifier(n_estimators=100)`
- Input : images RGB redimensionnées (224×224×3), puis aplaties
- Prétraitement : redimensionnement avec Keras, normalisation [0, 1]

---

## 🧪 Résultats / Results

**Accuracy globale :** `99%`

**Confusion Matrix:**
[[596 5]
[ 4 0]]

