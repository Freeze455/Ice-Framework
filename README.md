# Ice-Framework

ICE is a framework developed for the purpose of having a lighter alternative to large frameworks.
You will find the basic elements (typology, layouts, animations ...) and various components such as a slider, cards, jumbotron ...

## Installing

Afin d'utiliser le framework ICE, veuillez ajouter dans votre page le code suivant :
```html
<link rel="stylesheet" href="http://93.26.101.34/assets/css/ice.min.css">
<script src="http://93.26.101.34/assets/js/ice.min.js"></script>
```

## The framework structure

Soon

## Components

### Menu
If you would create a new menu, you can use this code in your html page. Don't forget to include js file in your <head>
```html
<div class="ice-menu"> <!-- If you want to have a sticky menu, you should add "sticky" tag here -->
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

### Slider
For the moment, you can't show many images (soon ?). In this area, you can add a text here with "display-$your_position"
```html
<div class="ice-sm-container-fluid">
    <div class="ice-slider">
        <img class="slider-image" src="https://cdn.allwallpaper.in/wallpapers/1920x1080/8789/champs-elyses-paris-cities-light-lights-1920x1080-wallpaper.jpg"> <!-- Choose your image -->
        <div class="slider-overlay"></div> <!-- Keep empty this tag -->
        <div class="display-center">display center</div>
        <div class="display-bottom-right">display bottom right</div>
        <div class="display-bottom-left">display bottom left</div>
        <div class="display-top-left">display top left</div>
        <div class="display-top-right">display top right</div>
    </div>
</div>
```

### Jumbotron
Initially, the jumbotron is used to create a visible area when loading the page in which you want to indicate important information.
Be aware, however, that no child element of jumbotron-container is required.
In this way, you can better modulate your element.
>NOTE : If you add more jumbotrons, they will be alternated left and right.
```html
<div class="ice-jumbotron">
    <div class="jumbotron-container">
        <div class="jumbotron-title"><h1>I'm a title</h1></div>
        <div class="jumbotron-describe">I'm a short describe</div>
        <hr>
        <div class="jumbotron-content">I'm a content to my jumbotron</div>
        <div class="ice-btn bg-green">If you want to add a button link</div>
    </div>
</div>
```

## Built With

* [SASS](https://sass-lang.com/) - The css compiler


## Authors

* **Freeze** - *Initial work* - [read more](https://github.com/Freeze455)