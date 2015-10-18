# Les Events avec Jquery

Avec jquery nous pouvons aussi écouter les Events du DOM.

On utilise la syntaxe $(".maClass").on("click", function);

exemple:
```js
var handleClick = function() {
	$(this).hide(); // l'élément se cache quand on click dessus
};

$(".maClass").on("click", handleClick);
```