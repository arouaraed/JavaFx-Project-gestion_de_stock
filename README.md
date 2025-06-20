# 📦 Système de Gestion de Stock pour mon université

Application JavaFX pour la gestion de stock et d'inventaire des établissements universitaires.

## 🎯 Description

Système développé pour gérer efficacement l'inventaire universitaire : équipements de laboratoire, fournitures administratives, matériel informatique et ressources pédagogiques.

## 🎥 Démonstration vidéo

[![Voir la démonstration](https://img.youtube.com/vi/qRg6_Rc_biI/0.jpg)](https://www.youtube.com/watch?v=qRg6_Rc_biI)

👉 **[Regarder la vidéo sur YouTube](https://www.youtube.com/watch?v=qRg6_Rc_biI)**  
Démonstration complète de l'application JavaFX de gestion de stock développée pour les établissements universitaires : fonctionnalités principales, interface et flux de travail.

## ✨ Fonctionnalités

- 📋 **Gestion des produits** - Ajout, modification, alertes de stock
- 🏢 **Gestion des fournisseurs** - Base de données des partenaires
- 📦 **Commandes** - Externes (achats) et internes (inter-services)
- 🏭 **Inventaire par local** - Suivi par bâtiment/salle
- 📊 **Tableau de bord** - Statistiques et indicateurs en temps réel
- 📄 **Export PDF** - Rapports et listes d'inventaire

## 🛠️ Technologies

- **Java**
- **JavaFX**
- **SQLite**
- **Maven**
- **Apache PDFBox**

## 🗄️ Base de Données

### Schéma SQLite

![image](https://github.com/user-attachments/assets/97885165-4658-4de9-8151-cf20b6a7efb4)


**Structure :** 9 tables interconnectées gérant le flux complet de l'inventaire universitaire
- **Workflow :** Services → Commandes → Produits → Stock → Locaux
- **Relations :** Clés étrangères garantissant l'intégrité des données
- **Audit :** Traçabilité complète via stock_movements
## 🚀 Installation

```bash
git clone https://github.com/[username]/projet-gestion-stock.git
cd projet-gestion-stock/gestion
mvn javafx:run
 
