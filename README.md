# Ice-Framework

ICE is a framework developed for the purpose of having a lighter alternative to large frameworks.
You will find the basic elements (typology, layouts, animations ...) and various components such as a slider, cards, jumbotron ...

## Installing

Afin d'utiliser le framework ICE, veuillez ajouter dans votre page le code suivant :
```html
<link rel="stylesheet" href="http://93.26.101.34/assets/css/style.min.css">
<script src="soon></script>
```

## The framework structure

Soon

## Coding your page

### Components
If you would create a new menu, you can use this code in your html page. Don't forget to include js file in your <head>
```html
<div class="ice-menu"> <!-- If you want to have a sticky menu, you should add  sticky tag here -->
    <a href="#" class="menu-logo"></a>
    <div class="menu-container">
        <div class="menu-content" id="menu-content">
            <nav>
                <ul>
                    <li><a href="#">Découvrir</a></li>
                    <li><a href="#">Comment ça marche</a></li>
                    <li><a href="#">À propos</a></li>
                    <li><a href="#">FAQ</a></li>
                </ul>
            </nav>
            <a href="#" class="button button-sign-up">S'inscrire</a>
            <a href="#" class="button button-sign-in">Se connecter</a>
        </div>
        <button class="menu-button" id="menu-button">&#9776;</button>
        <div class="menu-sidebar">
            <div class="menu-sidebar-header"></div>
            <div class="menu-sidebar-body" id="menu-sidebar-body"></div>
        </div>
        <div class="menu-overlay" id="menu-overlay"></div>
    </div>
</div>
```


## Built With

* [SASS](https://sass-lang.com/) - The css compiler


## Authors

* **Freeze** - *Initial work* - [read more](https://github.com/Freeze455)