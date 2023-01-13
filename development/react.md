# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'état (_state_) pour contrôler l'affichage d'un composant ✔️
- les composants enfants et les _props_ qu'on leur passe ✔️
- le déclenchement d'instructions en fonction des actions de l'utilisateur  ✔️
- le déclenchement d'instructions en fonction de l'étape du cycle de vie du composant ou du changement de valeur de ses props ❌ / ✔️
- l'usage d'un reducer (_useReducer_) pour gérer un état composé dans un composant
- l'état stocké dans un composant avec un _context provider_ et accessible dans ses descendants via `useContext` ✔️

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️
```
Here i use the pokeapi. 
First, i use axios to make a get request on the url to have a limit of 100 pokemons. 
After i create a function to create a object of my pokemon to recover all the data i need.
```


<!-- useEffect(() => {
        const getAllCharacters = async () => {
            const res = await axios.get('https://pokeapi.co/api/v2/pokemon/?limit=100&offset=0')

            const createPokemonObject = async (result) => {
                result.forEach( async (pokemon) => {
                    const res = await axios.get(`https://pokeapi.co/api/v2/pokemon/${pokemon.name}`);
                    const dataSort = (arr) => [...arr, res.data].sort((a, b) => a.id > b.id ? 1 : -1)
                    setPokemon(item => dataSort(item))
                })
            }
            setCharacters(
                res.data.results.map((item, index) => {
                    const charac = {
                        key: index,
                        id: item.id,
                        name: item.name,
                        url: item.url,
                    }
                    return charac

                })
            )
            createPokemonObject(res.data.results) 

        }

        getAllCharacters()
    }, []) -->

### Utilisation dans un projet ❌ / ✔️

[lien github](...)

Description :

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ / ✔️

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
