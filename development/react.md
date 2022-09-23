# Titre de la compétence

> 📈 En cours

## 🎓 J'ai compris et je peux expliquer

- l'état (_state_) pour contrôler l'affichage d'un composant 📈
- les composants enfants et les _props_ qu'on leur passe ✔️
- le déclenchement d'instructions en fonction des actions de l'utilisateur ✔️
- le déclenchement d'instructions en fonction de l'étape du cycle de vie du composant ou du changement de valeur de ses props 📈
- l'usage d'un reducer (_useReducer_) pour gérer un état composé dans un composant ❌
- l'état stocké dans un composant avec un _context provider_ et accessible dans ses descendants via `useContext` ❌ 

## 💻 J'utilise

### Un exemple personnel commenté ✔️

 ```
 // Ce code permet de créer un tableau de skills récupérées avec axios. Et de le mettre à jour automatiquement avec le useEffect()
 
 const [skills, setSkills] = useState([]);

 useEffect(() => { 

    const fetchSkills = async () => {
      const skillsFromApi = await axios.get('http://localhost:5000/api/skills');
      setSkills(skillsFromApi.data);
    };

    fetchSkills();
  }, []);
 ```

### Utilisation dans un projet ✔️

[React](https://github.com/QuentD36/wild_code_school/tree/master/React/wild-book)

Description :

### Utilisation en production si applicable ❌


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
