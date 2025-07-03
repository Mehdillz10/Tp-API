
# Mehdi Loulizi – API Microservices Réseau Social

# Présentation

Ce projet est une API REST construite selon une architecture microservices pour un réseau social minimaliste. Il comporte trois services indépendants :

- **auth-service** : gestion des utilisateurs (inscription, connexion, réinitialisation de mot de passe)
- **publication-service** : gestion des publications (CRUD et compteur de réactions)
- **reaction-service** : gestion des réactions (likes) associés aux publications

Une documentation Swagger unifiée est disponible pour explorer les endpoints.

---
# Prérequis

- Node.js >= 18
- MongoDB local ou MongoDB Atlas
- Git

---

# Installation

Clonez le projet et installez les dépendances pour chaque service :

```bash
git clone https://github.com/MehdiLoulizi/tp-microservices-reseau-social.git
cd tp-microservices-reseau-social
```

Puis exécutez le script global pour démarrer tous les services :

```bash
./start.sh
```

La documentation Swagger est accessible sur :  
[http://localhost:4500/api-docs](http://localhost:4500/api-docs)

---

# Documentation API

Consultez [http://localhost:4500/api-docs](http://localhost:4500/api-docs) pour une vue complète de l’API.

---

# Auteur

 **Mehdi Loulizi** 
