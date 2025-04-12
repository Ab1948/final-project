# 🛍️ غايتي Store – Plan de Développement Agile (Scrum)

Projet final pour CS50 – Objectif : Développer une boutique en ligne simple avec Flask et SQLite.

---

## 🔄 Méthodologie : Scrum (Agile)

- 4 Sprints (1 par semaine)
- Chaque Sprint contient des objectifs clairs et des tâches concrètes
- Avancement par itérations, test et amélioration continue
- Documentation et versioning via GitHub

---

## 🏃 Sprint 1 : Authentification (Login / Register)

### 🎯 Objectif :
Permettre à un utilisateur de créer un compte, se connecter et se déconnecter.

### ✅ Tâches :
- [ ] Initialiser le projet Flask (`app.py`, `templates`, `static`)
- [ ] Créer la base de données SQLite (`store.db`)
- [ ] Créer la table `users` avec `username` et mot de passe haché
- [ ] Créer le formulaire d’inscription (`register.html`)
- [ ] Développer la route `/register` pour enregistrer un utilisateur
- [ ] Créer le formulaire de connexion (`login.html`)
- [ ] Développer la route `/login` avec vérification
- [ ] Développer la route `/logout` pour déconnexion
- [ ] Tester toutes les routes manuellement

---

## 🏃 Sprint 2 : Catalogue de produits

### 🎯 Objectif :
Afficher dynamiquement une liste de produits disponibles à l’achat.

### ✅ Tâches :
- [ ] Créer la table `products` (nom, prix, image, description)
- [ ] Ajouter quelques produits de test
- [ ] Développer la route `/shop` pour afficher les produits
- [ ] Créer le template `shop.html` avec boucle Jinja
- [ ] Intégrer Bootstrap pour un rendu visuel propre
- [ ] Tester l’affichage des produits

---

## 🏃 Sprint 3 : Panier et commande

### 🎯 Objectif :
Permettre à l’utilisateur d’ajouter des produits au panier et de passer une commande.

### ✅ Tâches :
- [ ] Créer la table `cart` liée à l’utilisateur
- [ ] Gérer l’ajout de produits au panier
- [ ] Développer la page `/cart` pour voir le panier
- [ ] Créer la page `/checkout` pour valider la commande
- [ ] Vider le panier après validation
- [ ] (Optionnel) Créer une table `orders` pour enregistrer les commandes

---

## 🏃 Sprint 4 : Finitions et livraison

### 🎯 Objectif :
Finaliser le projet, le rendre beau, documenté et prêt à être publié.

### ✅ Tâches :
- [ ] Ajouter une barre de navigation (`layout.html`)
- [ ] Créer une page d’accueil (landing page)
- [ ] Intégrer un design responsive avec CSS / Bootstrap
- [ ] Effectuer des tests complets (utilisateur, sécurité)
- [ ] Écrire un fichier `README.md` clair et complet
- [ ] Enregistrer une vidéo de démonstration (CS50 requirement)
- [ ] Publier le projet sur GitHub

---

## 📚 Technologies utilisées

- Python / Flask  
- SQLite  
- HTML / CSS / Bootstrap  
- Jinja2  
- Git / GitHub
