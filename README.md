# 🌐 Projet d’Architecture Réseau – Euro-Med Université

## 📌 Description
Ce projet consiste en la **conception, l’implémentation et la simulation d’une architecture réseau universitaire**
pour l’**Euro-Med Université**, réalisée à l’aide de **Cisco Packet Tracer (Windows)**.

L’architecture proposée vise à assurer :
- une **segmentation logique du réseau**,
- une **gestion efficace des utilisateurs**,
- une **sécurité renforcée**,
- une **évolutivité** adaptée à un environnement universitaire.

---

## 👤 Auteur
- **Nom :** Youssef Alaoui Hichami  
- **Encadrant :** M. Ahmed Amamou  
- **Université :** Euro-Med Université  

---

## 🛠️ Outils et Technologies
- Cisco Packet Tracer (Windows)
- VLAN
- Routage inter-VLAN
- DHCP
- ACL (Access Control Lists)
- DMZ
- Modèle hiérarchique réseau (Core / Distribution / Accès)

---

## 🏗️ Architecture du Réseau

L’architecture suit un **modèle hiérarchique** :

- **Couche Cœur (Core)**  
  Routage principal et interconnexion des VLANs.

- **Couche Distribution**  
  Gestion du trafic entre le cœur et l’accès.

- **Couche Accès**  
  Connexion des utilisateurs finaux (PC, Wi-Fi, laboratoires).

---

## 🧩 Segmentation VLAN

| VLAN | Description        |
|-----:|-------------------|
| 10   | Administration     |
| 20   | Enseignants        |
| 30   | Étudiants          |
| 40   | Laboratoires       |
| 50   | Serveurs / DMZ     |

---

## 🔐 Sécurité
- Isolation des utilisateurs via VLANs
- Mise en place d’une **DMZ** pour les serveurs
- Filtrage du trafic à l’aide d’**ACL**
- Accès administrateur sécurisé

---

## ⚙️ Services Réseau
- **DHCP** : attribution automatique des adresses IP
- **DNS** : résolution des noms
- **Serveurs** placés en DMZ
- Accès Internet simulé

---

## 🧪 Tests Réalisés
- Connectivité inter-VLAN
- Attribution DHCP automatique
- Accès aux serveurs depuis différents VLANs
- Vérification de l’isolation réseau

---

## 📁 Contenu du dépôt

