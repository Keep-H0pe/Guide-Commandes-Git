## 📚 Commandes Git Utiles

Pour s'assurer que toute l'équipe est sur le même pied d'égalité, voici une liste de commandes Git essentielles avec des exemples pertinents.

## 🗺️ Sommaire
- [Initialisation et Configuration.](#one)
- [Gestion des Branches.](#two)
- [Commits et Historique.](#three)
- [Pull Requests et Fusion.](#four)
- [Collaboration et Revue de Code.](#five)

-----------

### <a name="one"> 1. 🚀 Initialisation et Configuration </a>

**Initialiser un Repository Git**
git init
- **Description** : Initialise un nouveau repository Git dans le répertoire courant.

**Configurer les Informations Utilisateur**
```shell
git config --global user.name "Votre Nom"
```
```shell
git config --global user.email "votre.email@example.com"
```
- **Description** : Configure votre nom et email pour les commits.

-----------

### <a name="two"> 2. 🌿 Gestion des Branches </a>

**Créer une Nouvelle Branche**
```shell
git checkout -b feature/nom-fonctionnalité
```
- **Exemple** : git checkout -b feature/ajout-authentification
- **Description** : Crée et bascule sur une nouvelle branche nommée `feature/nom-fonctionnalité`.

**Lister les Branches**
```shell
git branch
```
- **Description** : Affiche la liste des branches locales.

**Changer de Branche**
```shell
git checkout nom-branche
```
- **Exemple** : git checkout main
- **Description** : Bascule sur la branche spécifiée.

**Supprimer une Branche**
```shell
git branch -d nom-branche
```
- **Exemple** : git branch -d feature/ajout-authentification
- **Description** : Supprime la branche spécifiée.

-----------

### <a name="three"> 3. 📜 Commits et Historique </a>

**Afficher l'état des fichiers en local**
```shell
git status
```

**Ajouter des Fichiers au Staging**
```shell
git add nom-fichier
```
- **Exemple** : git add index.html
- **Description** : Ajoute un fichier spécifique au staging pour le prochain commit.

**Ajouter Tous les Fichiers au Staging**
```shell
git add .
```
- **Description** : Ajoute tous les fichiers modifiés au staging.

**Faire un Commit**
```shell
git commit -m "Message de commit"
```
- **Exemple** : git commit -m "Ajoute la fonctionnalité de connexion utilisateur"
- **Description** : Crée un commit avec un message descriptif.

**Voir l'Historique des Commits**
```shell
git log
```
- **Description** : Affiche l'historique des commits.

-----------

### <a name="four"> 4. 🔄 Pull Requests et Fusion </a>

**Mettre à Jour la Branche Locale avec les Dernières Modifications**
```shell
git pull origin main
```
- **Description** : Récupère les dernières modifications de la branche `main` du repository distant et les fusionne dans la branche courante.

**Pousser les Changements vers le Repository Distant**
```shell
git push -u origin nom-branche
```
- **Exemple** : git push origin feature/ajout-authentification
- **Description** : Pousse les commits de la branche locale vers le repository distant.

**Créer une Pull Request**
- **Description** : Allez sur GitHub, sélectionnez votre branche et cliquez sur "New Pull Request". Fournissez une description détaillée des changements.

-----------

### <a name="five"> 5. 👥 Collaboration et Revue de Code </a>

**Cloner un Repository**
```shell
git clone url-du-repository
```
- **Exemple** : git clone https://github.com/Keep-H0pe/Guide-Commandes-Git.git
- **Description** : Clone un repository distant sur votre machine locale.

**Voir les Différences entre les Commits**
```shell
git diff
```
- **Description** : Affiche les différences entre les fichiers modifiés mais non encore committés.

**Revertir un Commit**
```shell
git revert id-du-commit
```
- **Exemple** : git revert a1b2c3d
- **Description** : Revertit les modifications du commit spécifié par l'ID.

En suivant ces commandes, toute l'équipe sera en mesure de collaborer efficacement et de maintenir un flux de travail Git structuré. 😁
