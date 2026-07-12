# Fusion Caméra-LiDAR

Système de fusion caméra-LiDAR pour la détection et la localisation de lignes en environnement agricole.

## 🎯 Objectif du projet

Développer un système de perception intelligent combinant une caméra RGB et un LiDAR 4D pour détecter, localiser et estimer la distance des lignes au sol en temps réel.

## 🛠️ Technologies utilisées

- **ROS 2 Humble** : Middleware pour la communication entre les nœuds
- **YOLOv8-seg** : Détection et segmentation des lignes
- **OpenCV** : Traitement d'images
- **Python** : Langage de développement
- **NVIDIA Jetson Xavier NX** : Carte embarquée

## 📋 Pipeline de traitement

1. **Acquisition** : Caméra + LiDAR
2. **Détection** : YOLOv8-seg
3. **Calibration** : Intrinsèque et extrinsèque
4. **Fusion** : Caméra-LiDAR (Late Fusion)
5. **Estimation** : RANSAC + Calcul des distances

## 📊 Résultats

- Erreur de reprojection : 0.386 pixels
- Erreur de distance : < 0.05 m
- Précision détection : 92%

## 👨‍💻 Auteurs

- **Amin Ben Mahmoud**
- **Eya Hbaieb**
- **Yosr Hammami**

## 👩‍🏫 Encadrement

- **Feten Cherni** - Encadrante professionnelle
- **Hanene Medhaffar** - Encadrante académique
- **Ferdaous Masmoudi** - Encadrante industrielle (NOVEL-TI)

## 🏢 Entreprise

**NOVEL-TI** - Sfax, Tunisie

## 📅 Année universitaire

2025-2026

## 📄 Licence

**Licence appliquée en Électronique, Électrotechnique et Automatique (EEA)**  
ISGIS - Sfax
