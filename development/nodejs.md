# Titre de la compétence

> ✔️ Environnement permettant l'exécution de JS

## 🎓 J'ai compris et je peux expliquer

- Comment développer en utilisant un système de *livereloading* (`nodemon` par exemple) ✔️ (Nodemon permet le redémarrage du processus en surveillant les modifications)
- La connexion de mon application à une base de données avec et sans ORM/ODM (avec `mongodb` puis `mongoose` par exemple) ✔️ (Connexion à une DB Sqlite avec utilisation de TypeORM) 
- Le développement d'une API REST et GraphQL (avec les packages `express` et `graphql` par exemple) ✔️ (Utilisation de express)
- *Bonus : la manipulation des fichiers système avec `fs` et l'utilisation des streams en NodeJS* ❌

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

```javascript
// Fonction permettant la création d'un Wilder

create: async (req, res) =>{
        try{
            const data = await dataSource
                .getRepository(Wilder)
                .save(req.body)
                res.status(200).send(data);
        }
        catch(error){
            console.log(error);
            res.status(500).send(error);
        }  
    },
```

### Utilisation dans un projet ❌ / ✔️

[Node](https://github.com/QuentD36/wild_code_school/tree/master/Node)

Description :

### Utilisation en production si applicable ❌

Pas encore.

### Utilisation en environement professionnel ❌

Description :

## 🌐 J'utilise des ressources

### Node.js

- [Ici](https://nodejs.org/en/docs/)
- Documentation officielle Node

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
