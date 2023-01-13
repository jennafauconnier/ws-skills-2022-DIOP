# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- Comment développer en utilisant un système de *livereloading* (`nodemon` par exemple) ✔️
- La connexion de mon application à une base de données avec et sans ORM/ODM (avec `mongodb` puis `mongoose` par exemple) ✔️
- Le développement d'une API REST et GraphQL (avec les packages `express` et `graphql` par exemple) ❌ / ✔️
- *Bonus : la manipulation des fichiers système avec `fs` et l'utilisation des streams en NodeJS* ❌ / ✔️

## 💻 J'utilise

### Un exemple personnel commenté / ✔️

```javascript
// I declare empty array. 
// I use the post route on /users to create a salt by bcrypt. With the hashedPassword const, i recover the password, i hash it and add the salt to make it more indecriptible. 
// In the const user, i declare an object that's will recover the username from the body & and the password hashed and i push it in my empty array users.

let users = []
app.post('/users', async (req, res) => {
    try {
        const salt = await bcrypt.genSalt()
        const hashedPassword = await bcrypt.hash(req.body.password, salt)

        const user = {
            name: req.body.name,
            password: hashedPassword
        }
        users.push(user)
        res.status(201).send()
    } catch (error) {
        res.status(500).send()
        console.log(error.message)
    }

})
```

### Utilisation dans un projet ✔️

[lien github] Ligne 8 : controller getAll : https://github.com/jennafauconnier/chat_projet-pro/blob/master/server/src/users/controller.js

Description :
``` I use the query Builder Knex. So i call my db service sql. 
    It will select all my user by id and username. 
    As a response a send back the users. 
```


### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ✔️

Description : I use the ORM Sequelize. So i had to make the username unique. 
            I check if the name is already in db by it's id and i add the options to lower all the name. Because we don't want 2 Jenna and jenna juste because of the capitalize J. 
            And if the name is already take, i send an error. 

## 🌐 J'utilise des ressources

### Titre

- https://www.youtube.com/@WebDevSimplified/playlists
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
