# REST API

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les verbes HTTP ✔️
- les statuts HTTP ✔️
- les endpoints ✔️
- CORS ✔️
- la nomenclature recommandée pour les routes ✔️

## 💻 J'utilise

### Un exemple personnel commenté ✔️

```javascript
// Ici je renvois un statut 200 si le user recherché par son Id a bien été trouver. Si je ne le trouve pas, j'envois une apiError qui notifie Not Found.

const user = await User.findOne({
    where: { id: ctx.params.id }
  })

  if (!user) {
    ctx.apiError('NOT_FOUND')
  }

  ctx.status = 200
  ctx.body = {
    user
  }

```


### Utilisation dans un projet ✔️

[lien github](...)
https://github.com/jennafauconnier/twitter/blob/feature/CRUD_backend/server/src/components/users/users.controller.js

Fonction addUser.

Description : Ajout d'un user, dans le body je récupère le name, handle, email. par son id je vérifie si son email existe déjà, si c'est le cas je renvois une 409 en notifiant que son email est déjà utilisé. Sinon je crée le nouveau user en renvoyant une 200 une fois que la query est bien passé. 

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ✔️

Description : Même chose que pour Utilisation dans un projet.

## 🌐 J'utilise des ressources
    Koa.js
    Daily.dev
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
