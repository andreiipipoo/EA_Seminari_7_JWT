## Funcionalitats Implementades

- Permetre que un usuari, introduint el seu ID i el seu token, pugui fer canvis sobre les seves dades.
- Restringir la visualització del llistat d'usuaris només als usuaris amb rol d'administrador.
- Clonació correcta del repositori utilitzant les següents comandes:

  ```sh
  git remote remove origin
  git remote add origin <URL-del-nou-repositori>
  git push -u origin main

## Seminari JWT

- register: crear usuari i et retorna un token 

- login: et loggeja i et retorna un token 

- profile: si li dones el teu id d'usuaari + token i comprova que ets propietari del token i et mostre les teves

- funcionalitat encrypted password enabled

- Delete user: comprova que el token que has introduit es d'un usuari administrador i deixa borrar el usuari introduit en la ruta

# Commands to execute

Instal·lar jwt
```sh
npm install jsonwebtoken 
npm install @types/jsonwebtoken -D
```
Instal·lar dotenv
```sh
npm i dotenv
npm i @types/dotenv -D
```

Instal·lar bcrypt
```sh
npm i bcryptjs
npm i @types/bcryptjs -D
```
