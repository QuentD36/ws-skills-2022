# Langage Javascript

> 📈 En progression concernant la phase algo

> ✔️ Base du langage

## 🎓 J'ai compris et je peux expliquer

- les `structures` de base du langage ✔️
- les normes `ecmascript` ✔️ (ES5/ES6/ES7) 
- l'utilisation de l'`asynchrone` ✔️ (Utilisation de async/await géré avec try/catch ou then/catch)
- les spécifités du mot-clef `this` ✔️ (Accès aux propriétés de la classe concernée : this.name, this.city...)

## 💻 Je code en Javascript

### Un exemple de code commenté ✔️

```javascript
// Ce code est utilisé pour résoudre un challenge codewars :

String.prototype.toJadenCase = function () {
  return this.split(' ').map(el => { // On récupère une string qu'on découpe en tableau de mots sur lequel on map
    const word = el.split(''); // Pour chaque mot, on le découpe par lettre
    word[0] = word[0].toUpperCase(); // On met la première lettre du mot en majuscule
    return word.join(''); // Puis on reforme le mot qui est maintenant en uppercase
  }).join(' '); // On reforme la phrase complète
};
```

### Utilisation dans un projet ✔️

[Projet node en JS](https://github.com/QuentD36/wild_code_school/tree/master/Node)

Description :

### J'ai utilisé ce langage en production ❌

Pas encore.

Description :

### J'ai utilisé ce langage en environement professionnel ❌

Description :

## 🌐 J'utilise des ressources

### Code Wars

- [Ici](https://www.codewars.com/)
- Permet de réaliser des challenges d'algorithmes

### Eloquent Javascript

- [Ici](https://eloquentjavascript.net/)
- Ressource générale sur le langage JS

### Learn Javascript

- [Ici](https://learnjavascript.online/)
- Apprendre en pratiquant le JS

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️

