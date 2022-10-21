# GraphQL

> ✔️ Compréhension

## 🎓 J'ai compris et je peux expliquer

- la différence entre REST et GraphQL ✔️
- les besoins auxquels répond GraphQL ✔️
- la définition d'un schéma ✔️
- Query ✔️
- Mutation ✔️
- Subscription 📈

## 💻 J'utilise

### Un exemple personnel commenté ✔️

```
// Query GraphQL 

export const GET_WILDERS = gql`
  query GetAllWilders {
    getAllWilders {
      id
      name
      description
      city
      grades {
        id
        grade
        skill {
          id
          title
        }
      }
    }
  }
`;
```

### Utilisation dans un projet ✔️

[Wilder Book avec GraphQL](https://github.com/QuentD36/ws-docker-quest3)

Description :

### Utilisation en production si applicable ❌

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

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
