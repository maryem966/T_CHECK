# T_CHECK
 T_CATCH – Système de Vérification de Produits
T_CATCH est une application web interactive développée avec Streamlit, OpenCV, YOLOv5, OCR, et barcode detection, permettant d’analyser les images de produits pour :

✅ Vérifier s'ils font partie des marques à boycotter

🖼️ Identifier les logos de marque à l'aide d'un modèle YOLOv5

📊 Extraire et valider le numéro de code-barres

📷 Comparer visuellement les produits à une base d’images locale

🌍 Objectif
Soutenir les consommateurs responsables dans leurs décisions d’achat en fournissant un outil de reconnaissance de produits boycottés grâce à l’intelligence artificielle et au traitement d’images.

📦 Fonctionnalités principales
Correspondance Produit :

Suppression de l’arrière-plan

Calcul de la similarité d’image (histogramme, couleur, SSIM)

Recherche dans une base locale d’images boycottées

Détection de Logo :

Utilise YOLOv5 pour détecter des marques dans les images

Compare les résultats à une liste de marques boycottées

Validation du Code-Barres :

Détection du code-barres via pyzbar

Extraction du numéro via OCR (Tesseract)

Vérification du préfixe du code (e.g., 729 pour Israël, 619 pour Tunisie)

🧰 Technologies utilisées
Streamlit – Interface utilisateur

OpenCV – Traitement d’image

YOLOv5 – Détection de logo

Pytesseract – OCR

pyzbar – Lecture de code-barres

