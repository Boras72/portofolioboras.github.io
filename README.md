# Portofolio personnel : https://boras72.github.io/portofolioboras.github.io/


## Créer un Repo sur GitHub :

### Créer un nouveau repository Sur GitHub :

1. **Créer un nouveau dépôt distant ** :
   - Allez sur le menu à droite / "Your repositories"
   - Cliquez sur le bouton vert "New repository"
   - Create a new Repository :
     - **Repository name** : Donnez un nom à votre dépôt.
     - **Description** : (Facultatif) Ajoutez une description de votre projet.
     - **Public/Private** : Choisissez si vous voulez que votre dépôt soit public ou privé.
     - Cochez "Initialize this repository with a README" si vous avez déjà un projet local.
   - Cliquez sur "Create repository".

### Dans votre Terminal (VSC):

2. **Pour initialiser le dépôt local et pousser sur GitHub** :
   - Ouvrez votre terminal et allez dans le répertoire de votre projet que vous vouler pousser (un dossier ".git" apparaitra)
   - Initialisez un dépôt Git local :
     ```
     git init
     ```

- Ajoutez vos fichiers au dépôt :
  ```
  git add .
  ```
  - Cette commande affichera les fichiers (staged) qui sont prêts à être commis
    ```
    git status
    ```
  - Faites un commit de vos fichiers :
    ```
    git commit -m "commentaire"
    ```
  - Ajoutez le dépôt distant que vous avez créé sur GitHub : ("Code"/HTTPS:copier l'url/coller l'url dans le terminal)
    ```
    git remote add origin https://github.com/<votre_nom_d_utilisateur>/<nom_du_depot>.git
    ```
- Poussez vos fichiers vers GitHub :
  `   git push -u origin main  /   git push origin main`
  (si c'est la première fois que vous poussez votre branche locale vers GitHub, il est recommandé d'utiliser git push -u origin main
  pour définir la branche distante par défaut pour les futurs git push.)



## Cloner un dépôt distant existant sur votre machine locale :

  - Cliquez sur le bouton vert "Code" d'un repo sur github et copiez l'URL du dépôt.
  - Ouvrez votre terminal et allez dans le répertoire où vous voulez cloner le dépôt.
  - Clonez le dépôt sur votre machine locale :
    ```
    git clone
    ```
    - Collez l'URL du dépôt que vous avez copiée.
    - Appuyez sur "Enter".


