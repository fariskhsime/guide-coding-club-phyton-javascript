
# Guide langage Python

Le Python est un langage de programmation de haut niveau créé dans les années 1990, connu pour sa simplicité et sa lisibilité. Il est largement utilisé dans le développement web, la science des données, l'automatisation, et bien plus encore.

C'est un langage polyvalent qui convient aussi bien aux débutants qu'aux développeurs expérimentés.

## À propos

Cette page est une référence rapide des fonctionnalités de base du langage Python dont tu auras besoin pour les sujets du Coding Club. N'hésite pas à demander des explications supplémentaires si tu as besoin ! 😄

## Liens utiles 🔗

Quelques liens utiles pour aller plus loin et se documenter sur le langage Python :
- [Python (programming language) sur Wikipedia](https://fr.wikipedia.org/wiki/Python_(langage))
- [Documentation officielle de Python](https://docs.python.org/3/)
- [Learn Python the Hard Way](https://learnpythonthehardway.org/)

## Structure d'un programme
Un programme Python commence par l'importation des modules nécessaires, suivi de la définition des fonctions et de l'exécution du code principal.
```python
import math

def main():
    print("Hello, World!")
    print(math.sqrt(16))

if __name__ == "__main__":
    main()
# Output: 
# Hello, World!
# 4.0
```

## Variables et types
Déclaration de variables et types de données de base.
```python
x = 5  # int
y = 3.14  # float
name = "Alice"  # str
is_active = True  # bool
print(type(x))  # Output: <class 'int'>
print(type(y))  # Output: <class 'float'>
print(type(name))  # Output: <class 'str'>
print(type(is_active))  # Output: <class 'bool'>
```

## Fonctions
Définition et utilisation des fonctions.
```python
def greet(name):
    return "Hello " + name

print(greet("Alice"))  # Output: Hello Alice
```

## Conditions
Utilisation des conditions if, elif et else.
```python
x = 10
if x > 0:
    print("Positive")
elif x == 0:
    print("Zero")
else:
    print("Negative")
# Output: Positive
```

## Boucles
Utilisation des boucles for et while.
```python
# Boucle for
for i in range(5):
    print(i)
# Output: 0 1 2 3 4

# Boucle while
count = 0
while count < 5:
    print(count)
    count += 1
# Output: 0 1 2 3 4
```

## Listes / Strings
Manipulation des listes et des chaînes de caractères.
```python
# Listes
fruits = ["apple", "banana", "cherry"]
print(fruits[1])  # Output: banana

fruits.append("orange")
print(fruits)  # Output: ['apple', 'banana', 'cherry', 'orange']

fruits.remove("banana")
print(fruits)  # Output: ['apple', 'cherry', 'orange']

# Strings
str1 = "Hello"
str2 = "World"
full_str = str1 + " " + str2
print(full_str)  # Output: Hello World

# Fonctions de base sur les strings
print(len(full_str))  # Output: 11
print(full_str.lower())  # Output: hello world
print(full_str.upper())  # Output: HELLO WORLD
```

## Dictionnaires
Création et manipulation de dictionnaires.
```python
person = {"name": "John", "age": 30}
print(person["name"])  # Output: John

person["age"] = 31
print(person)  # Output: {'name': 'John', 'age': 31}

del person["age"]
print(person)  # Output: {'name': 'John'}
```
