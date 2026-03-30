# Stress Hydrique Tchad 🌾

Système intelligent de détection précoce du stress hydrique
pour les cultures de mil et sorgho au Tchad.

## Objectif

Classifier l'état hydrique des parcelles agricoles en 4 niveaux :
Normal · Stress léger · Stress modéré · Stress sévère

## Stack technique

* Données : Sentinel-2 via Google Earth Engine
* ML : Random Forest → TensorFlow Lite
* App : Android (Java)

## Structure du projet

* `data/` → données satellites brutes et traitées
* `notebooks/` → exploration et entraînement ML (Google Colab)
* `models/` → modèles entraînés (.tflite)
* `android-app/` → application mobile
* `docs/` → documentation et cahier des charges

## Statut

🚧 En cours de développement — Phase 1 : Données satellites

