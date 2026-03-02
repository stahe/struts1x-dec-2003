# Introduction au framework Struts 1.x

👉 **Cours en ligne :**
[Introduction au framework Struts 1.x par l'exemple (décembre 2003)](https://stahe.github.io/struts1x-dec-2003/)

---

## Objectifs

Ce projet a pour objectif de découvrir la méthode de développement **Struts 1.x**, issue du projet Jakarta Struts de l’**Apache Software Foundation**.

Struts propose un cadre standard pour le développement d’applications web Java fondé sur le modèle d’architecture **MVC (Modèle – Vue – Contrôleur)**.

L’ambition pédagogique est de :

* Comprendre les principes du modèle MVC
* Structurer correctement une application web Java
* Séparer clairement présentation, logique applicative et accès aux données
* Mettre en œuvre cette architecture avec Servlets et JSP

---

## Le modèle MVC

Le modèle **MVC (Model–View–Controller)** vise à séparer :

| Couche             | Rôle                  |
| ------------------ | --------------------- |
| **Vue (V)**        | Interface utilisateur |
| **Contrôleur (C)** | Logique applicative   |
| **Modèle (M)**     | Accès aux données     |

Cette architecture est également appelée **architecture 3-tiers**.

### 1️⃣ Vue – Interface utilisateur

* Généralement un navigateur web
* Peut également être une application autonome
* Envoie des requêtes HTTP et met en forme les résultats

### 2️⃣ Contrôleur – Logique applicative

* Traite les demandes de l’utilisateur
* Coordonne les traitements
* Fait appel aux classes métier et aux sources de données

### 3️⃣ Modèle – Sources de données

Peut être constitué de :

* Bases de données
* Fichiers plats
* Services web
* Annuaire LDAP
* Toute autre source persistante

L’objectif principal du modèle MVC est de maintenir une **forte indépendance** entre ces trois couches afin de limiter les impacts lors d’évolutions.

---

## MVC avec Servlets et JSP

Lorsqu’on applique MVC avec les technologies classiques Java EE (Servlets + JSP), l’architecture s’organise comme suit :

### 🔹 Contrôleur

* Une **Servlet** joue le rôle de porte d’entrée de l’application
* Elle centralise les requêtes HTTP

### 🔹 Logique métier

* Ensemble de **classes métier**
* Implémentent les règles fonctionnelles

### 🔹 Accès aux données

* **Classes d’accès aux données (DAO)**
* Interagissent avec les bases ou autres systèmes

### 🔹 Vues

* Pages **JSP**
* Responsables de la présentation

---

## Pourquoi Struts ?

Struts formalise cette organisation en :

* Centralisant le contrôle des requêtes
* Standardisant la gestion des actions
* Facilitant la séparation des responsabilités
* Structurant les applications web Java de manière industrielle

Il fournit ainsi un cadre robuste pour développer des applications web respectant strictement l’architecture MVC.

---

## Public visé

* Étudiants en informatique
* Développeurs Java web
* Personnes souhaitant comprendre l’architecture MVC appliquée aux applications web

---

## Technologies concernées

* Java
* Servlets
* JSP
* Architecture MVC
* Framework Struts 1.x

---

## Licence

Support pédagogique destiné à un usage académique.

---

Si vous le souhaitez, je peux également générer :

* une version plus minimaliste
* une version plus académique
* une version enrichie avec plan détaillé
* ou une version optimisée SEO pour GitHub Pages
