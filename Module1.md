# Module 6 - Les hooks React

## Documents consultés

### [useState](https://react.dev/reference/react/useState)

----------------
### [10 React Hooks Explained // Plus Build your own from Scratch](https://www.youtube.com/watch?v=TNhaISOUy6Q)

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

## Exercices faits
- Exercice 1: ok
- Exercice 2: erreur car j'avais pas ajouté `<button onClick={() => setCount(count +1)}>` dans le return
- Exercice 3: ok
  
## Évaluation
Résultat = bien
