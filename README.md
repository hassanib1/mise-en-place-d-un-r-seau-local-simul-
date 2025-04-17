# 💻 Simulation d’un Réseau Local avec Cisco Packet Tracer

Ce projet a pour but de comprendre le fonctionnement des VLANs, du routage inter-VLANs, et la configuration des équipements réseau de base dans un environnement d’entreprise..

## 📌 Objectifs

- Créer une topologie réseau représentative d'une petite entreprise
- Mettre en œuvre la segmentation réseau via VLAN
- Configurer un routage inter-VLAN (Router-on-a-Stick)
- Vérifier la connectivité entre tous les équipements

## 🧰 Équipements Simulés

- 🖧 1 Routeur Cisco 2811
- 🔀 `1 Switchs Cisco 2960
- 🖥️ 2 PC (utilisateurs)

## 🗂️ Plan d’Adressage IP


device	Ipv4	Subnet mask	Default Gateway
Pc4	192.168.1.10	255.255.255.0	192.168.1.1
Pc5	192.168.1.20	255.255.255.0	192.168.1.1	
Pc6	192.168.2.10	255.255.255.0	192.168.2.1
Pc7	192.168.2.20	255.255.255.0	192.168.2.1


## 🖥️ Configuration Réseau

- VLAN configurés sur les switchs (10, 20)
- Ports attribués selon les services
- Lien trunk du switch  vers le routeur
- Sous-interfaces configurées sur le routeur

## ✅ Tests Réussis

- Ping entre PC d’un même VLAN
- Communication inter-VLAN

## 🧠 Compétences Démontrées

- Configuration VLAN et trunking
- Routage inter-VLAN (Router-on-a-Stick)
- Dépannage réseau (ping, show vlan, show ip int brief)

## 👤 Auteur

**Hassan Ibrahim**  
Étudiant en Licence Réseaux et Sécurité Informatique  

