# Webserv - Projet 42

Ce projet consiste à écrire votre propre serveur HTTP en C++ 98. Ce README vous guidera à travers les étapes nécessaires pour réaliser ce projet.

## Table des matières

1. [Introduction](#introduction)
2. [Prérequis](#prérequis)
3. [Configuration de l'environnement](#configuration-de-lenvironnement)
4. [Structure du projet](#structure-du-projet)
5. [Étape 1 : Comprendre le protocole HTTP](#étape-1--comprendre-le-protocole-http)
6. [Étape 2 : Configuration du Makefile](#étape-2--configuration-du-makefile)
7. [Étape 3 : Implémentation du serveur HTTP](#étape-3--implémentation-du-serveur-http)
8. [Étape 4 : Gestion des requêtes et réponses HTTP](#étape-4--gestion-des-requêtes-et-réponses-http)
9. [Étape 5 : Gestion des fichiers de configuration](#étape-5--gestion-des-fichiers-de-configuration)
10. [Étape 6 : Tests et validation](#étape-6--tests-et-validation)
11. [Rendu et évaluation](#rendu-et-évaluation)

## Introduction

Le but de ce projet est de créer un serveur HTTP en C++ 98. Vous allez apprendre comment fonctionne le protocole HTTP et comment un serveur web traite les requêtes des clients.

## Prérequis

- Connaissance de base en C++.
- Compréhension des concepts de réseau (sockets, ports, etc.).
- Familiarité avec les commandes de base de Linux.

## Configuration de l'environnement

1. **Installer les outils nécessaires :**
   - Assurez-vous d'avoir un compilateur C++ installé (g++).
   - Installez les outils de développement nécessaires (make, etc.).

2. **Créer le répertoire du projet :**
   ```bash
   mkdir webserv
   cd webserv
