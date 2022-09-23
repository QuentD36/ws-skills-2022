# TypeScript

> 📈 En cours de compréhension

## 🎓 J'ai compris et je peux expliquer

- l'intéret de TypeScript dans l'IDE 📈 (C'est une surcouche de JS, qui lui enlève son côté permissif, en ajoutant un système de typage et permet également une résolution de bug plus rapide)
- les types de bases ✔️ (string, number, any, string[] ...)
- comment et pourquoi étendre une interface ✔️
- les classes et les decorators ❌ / ✔️

## 💻 J'utilise

### Un exemple personnel commenté ✔️

```
// Ce code est utilisé pour résoudre un challenge de la Wild Code School

export default function ({ students }: { students: Student[] }): Student[] { // Cette fonction reçoit en paramètre un tableau students de type Student (qui est ici une interface)
    return students
      .sort((c, d) => (c.name > d.name ? -1 : 1)) // Permet de trier les students par ordre alphabétique
      .sort((a, b) => (a.age > b.age ? 1 : -1));  // Permet de trier les students par âge croissant
}
```

### Utilisation dans un projet ✔️

[React & Typescript](https://github.com/QuentD36/react_ts_wildcodeschool)

Description :

### Utilisation en production si applicable ❌ 

Pas encore.

Description :

### Utilisation en environement professionnel ❌ 

Description :

## 🌐 J'utilise des ressources

### TypeOrm

- [Ici](https://typeorm.io/)
- Documentation de l'ORM utilisé en TS 

### Typescript 

- [Ici](https://www.typescriptlang.org/docs/)
- Documentation officielle TS

### Tutoriel TS

- [Ici](https://ts.chibicode.com/todo/)
- Tutoriel TS pour créer une To Do list

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
