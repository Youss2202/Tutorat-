# synchroniser notre dossier avec un déôt GitHub

```
git init
git add .
git config --global user.name "Youssef"
git config --global user.email "youssef.mankouri@gmail.com"
git commit -m "debut reunion 2"
git branch -M main
git remote add origin https://github.com/Youss2202/Tutorat-.git
git push -u origin main
```

# vowire framing - zoning (le design en fil de fer)

maquette où la disposition des éléments graphiques apparaissent.

```
le header 
    contient le logo
    contient aussi la barre de menu

la partie central - principal de la page 
    contient la partie haute 
        slider
        element 1
        CTA 1
    contient la partie basse
```

# transformer les zones en balises HTML

```
le header : <header> 
    contient le logo : <img> 
    contient aussi la barre de menu : <nav> qui contient un <ul>

la partie central - principal de la page : <main>
    contient la partie haute : <section>
        slider : <div class="slider">
        element 1 : <div class="element1">
        CTA 1 <div class="cat1">
    contient la partie basse : <section>
```