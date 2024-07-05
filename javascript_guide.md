
# Guide langage JavaScript

JavaScript est un langage de programmation de haut niveau principalement utilisé pour le développement web. Il permet de créer des pages web interactives et dynamiques.

JavaScript est exécuté dans le navigateur, mais peut également être utilisé côté serveur avec Node.js.

## À propos

Cette page est une référence rapide des fonctionnalités de base du langage JavaScript dont tu auras besoin pour les sujets du Coding Club. N'hésite pas à demander des explications supplémentaires si tu as besoin ! 😄

## Liens utiles 🔗

Quelques liens utiles pour aller plus loin et se documenter sur le langage JavaScript :
- [JavaScript (programming language) sur Wikipedia](https://fr.wikipedia.org/wiki/JavaScript)
- [Mozilla Developer Network (MDN) JavaScript Guide](https://developer.mozilla.org/fr/docs/Web/JavaScript/Guide)
- [JavaScript.info](https://javascript.info/)

## Structure d'un programme
Un programme JavaScript commence par la déclaration des variables, des fonctions et de l'exécution du code principal.
```javascript
function main() {
    console.log("Hello, World!");
    console.log(Math.sqrt(16));
}

main();
// Output: 
// Hello, World!
// 4
```

## Variables et types
Déclaration de variables et types de données de base.
```javascript
let x = 5;  // number
let y = 3.14;  // number
let name = "Alice";  // string
let isActive = true;  // boolean
console.log(typeof x);  // Output: number
console.log(typeof y);  // Output: number
console.log(typeof name);  // Output: string
console.log(typeof isActive);  // Output: boolean
```

## Fonctions
Définition et utilisation des fonctions.
```javascript
function greet(name) {
    return "Hello " + name;
}

console.log(greet("Alice"));  // Output: Hello Alice
```

## Conditions
Utilisation des conditions if, else if et else.
```javascript
let x = 10;
if (x > 0) {
    console.log("Positive");
} else if (x === 0) {
    console.log("Zero");
} else {
    console.log("Negative");
}
// Output: Positive
```

## Boucles
Utilisation des boucles for et while.
```javascript
// Boucle for
for (let i = 0; i < 5; i++) {
    console.log(i);
}
// Output: 0 1 2 3 4

// Boucle while
let count = 0;
while (count < 5) {
    console.log(count);
    count++;
}
// Output: 0 1 2 3 4
```

## Tableaux / Strings
Manipulation des tableaux et des chaînes de caractères.
```javascript
// Tableaux
let fruits = ["apple", "banana", "cherry"];
console.log(fruits[1]);  // Output: banana

fruits.push("orange");
console.log(fruits);  // Output: ['apple', 'banana', 'cherry', 'orange']

fruits.splice(1, 1);  // supprime 'banana'
console.log(fruits);  // Output: ['apple', 'cherry', 'orange']

// Strings
let str1 = "Hello";
let str2 = "World";
let fullStr = str1 + " " + str2;
console.log(fullStr);  // Output: Hello World

// Fonctions de base sur les strings
console.log(fullStr.length);  // Output: 11
console.log(fullStr.toLowerCase());  // Output: hello world
console.log(fullStr.toUpperCase());  // Output: HELLO WORLD
```

## Objets
Création et manipulation d'objets.
```javascript
let person = {name: "John", age: 30};
console.log(person.name);  // Output: John

person.age = 31;
console.log(person);  // Output: {name: 'John', age: 31}

delete person.age;
console.log(person);  // Output: {name: 'John'}
```

## Exécuter sur un compilateur en ligne

Pour exécuter rapidement du code JavaScript sans installer de logiciel, tu peux utiliser [JSFiddle](https://jsfiddle.net/).
