# Module 1

## Documents consultés

### [useState](https://react.dev/reference/react/useState)

#### Sujet
Description détaillée de `useState` avec exemples d'utilisation

#### Notes
Quand on utilise useState on lui passe une valeur initiale. useState retourne 2 choses:
- la variable qui contient la valeur
- la fonction qu'on utilise pour changer cette valeur

#### Questions 
Qu'est-ce qui se passe si on change directement la valeur sans passer par la fonction retournée par useState?

----------------
### [10 React Hooks Explained // Plus Build your own from Scratch](https://www.youtube.com/watch?v=TNhaISOUy6Q)

#### Sujet
Description des hooks en React

#### Notes 
Les hooks remplacent les classes dans les anciennes versions de React

Les hooks sont préfixés avec "use"

useState est le plus utile

useEffect sert à gérer les "side effects". Side effects = les requêtes de données mais aussi bcp d'autres choses.

Exemple:
```js
useEffect(() => {    
    document.title = `You clicked ${count} times`;
});
```

#### Questions
Est-ce que useEffect peut être utilisé sans useState?

## Exercices faits
- Exercice 1: ok
- Exercice 2: erreur car j'avais pas ajouté `<button onClick={() => setCount(count +1)}>` dans le return
- Exercice 3: ok
  
## Évaluation
Résultat = bien
