# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- Comment développer en utilisant un système de *livereloading* (`nodemon` par exemple)  ✔️
- La connexion de mon application à une base de données avec et sans ORM/ODM (avec `mongodb` puis `mongoose` par exemple) ❌ / ✔️ un peu du mal avec ça. 
- Le développement d'une API REST et GraphQL (avec les packages `express` et `graphql` par exemple) ✔️ oui mais manque de pratique (on en manque toujours)
- *Bonus : la manipulation des fichiers système avec `fs` et l'utilisation des streams en NodeJS* ❌

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

```javascript
interface IController {
  [key: string]: (arg0: Request, arg1: Response) => {};
}

export const wilderController: IController = {
  read: async (req, res) => {
    try {
      const allWilders = await dataSource.getRepository(Wilder).find({
        relations: {
          grades: {
            skill: true,
          },
        },
      });
      res.send(allWilders);
    } catch (error) {
      console.log(error);
    }
  },
```

### Utilisation dans un projet  ✔️

[lien github] https://github.com/YanLabarthe/n-oubliez-pas-la-replique

Description : une petite app qui ne fonctionne qu'en localhost pour l'instant. Un jeu de devinette avec requête API d'un back en node.

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description : Pas encore

### Utilisation en environement professionnel ❌ / ✔️

Description : Pas encore

## 🌐 J'utilise des ressources

### Titre

- lien
-https://github.com/marioterron/node-exercises
- description
- Des exercices node JS
## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description: Le back c'est complexe mais motivant, alors oui je manque de beaucoup de pratique mais j'y arrive toujours éventuellement. 
Si, je ne sais pas mettre du back sur mon site internet.

Plan d'action : (à valider par le formateur)

- Utiliser un serveur connecté à une bdd pour pouvoir avoir un back lié à mon site Internet ❌ / ✔️
- Faire plus de CRUD ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌
- J'ai fait une [présentation](...) ❌
