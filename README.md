# Brief : Création d'une page de base avec GitHub Pages

## Objectif  
Créer une page web simple et fonctionnelle, hébergée sur GitHub Pages, en utilisant uniquement HTML et CSS. Vous devrez consulter la documentation officielle pour apprendre à configurer et déployer votre site.  

---

## Étapes à suivre  

### 1. Créez un dépôt GitHub  
- Rendez-vous sur [GitHub](https://github.com) et connectez-vous.  
- Créez un nouveau dépôt nommé `ma-page-web`.  
- Initialisez le dépôt avec un fichier `README.md`.  

---

### 2. Préparez votre projet localement  
- Clonez le dépôt sur votre ordinateur en utilisant la commande :  

```bash
git clone git@github.com:votre-nom-utilisateur/ma-page-web.git
```

Dans le dossier du projet, créez deux fichiers :
`index.html`
`style.css`

---

### 3. Créez le contenu de la page

**HTML :**
Copiez et collez le code ci-dessous dans index.html :

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ma Page Web</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Bienvenue sur ma page web</h1>
    </header>
    <main>
        <p>Ceci est une page de base créée avec HTML et CSS, hébergée sur GitHub Pages.</p>
        <a href="https://github.com" target="_blank">Découvrez GitHub</a>
    </main>
    <footer>
        <p>© 2024 - Créé avec ❤️ par [votre nom]</p>
    </footer>
</body>
</html>
```

**CSS :**
Ajoutez ce code dans style.css :

```css
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f9;
    color: #333;
}

header {
    background: #007bff;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

main {
    padding: 2rem;
    text-align: center;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
    position: absolute;
    bottom: 0;
    width: 100%;
}

a {
    color: #007bff;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}
```

---

### 4. Déployez sur GitHub Pages

- Ressources à consulter :
    - Documentation GitHub Pages
    - Introduction à HTML (MDN)
    - Introduction à CSS (MDN)
    - Guide GitHub : Cloner un dépôt

--- 

**Livrable attendu :**

- Une page fonctionnelle hébergée sur GitHub Pages.
- Lien à partager avec le formateur pour évaluation.

--- 

**Bon courage et amusez-vous bien avec votre première page web hébergée en ligne ! 🚀**
