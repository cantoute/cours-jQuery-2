# Exercice : Progress bar

## Énoncé

Nous allons créer une barre de progression, typiquement appelée progress bar, l'animation devra durer 3 secondes et la taille maximum de la barre sera de 400 pixels.
Il y a 2 boutons qui permettront d'arrêter (stop) l'animation et de la reprendre (start).

Lorsque l'on arrête l'animation, il faut indiquer le pourcentage d'avancement dans #log. Cet avancement sera exprimé avec un nombre entier.
Une fois l'animation terminée, on doit voir apparaître `100%` dans #log, les 2 boutons désactivés et la progress bar avec un fond vert.

### HTML

```html
<button id="start">Start</button>
<button id="stop">Stop</button>
 
<div id="bar"></div>
<div id="log"></div>
```


### CSS

```css
#bar {
    width:0px;
    height:25px;
    border:1px solid black;
    background-color:yellow;
    border-radius:3px;
}
```
