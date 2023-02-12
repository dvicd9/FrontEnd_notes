# Building & Firebase hosting

### Buildelés *(kész alkalmazás)*:

> `ng build (--prod)` -> build to production

### Hosting / Webserver *(static web server)*:
**Firebase hosting**
[Firebase dokumentáció](https://firebase.google.com/docs/cli)
> https://firebase.google.com/docs/cli

**Firebase tools install**
> `npm install -g firebase-tools` *(console install -> global)*

**Login**
> `firebase login`

**Projektek**
> `firebase projects:list`

**Firebase projekt inicializálása**
> `firebase init` *(Hosting: Confirgure files for Firebase Hosting)*

> *use as public directory:* `dist/project-name` **(!!!)**
> *single page app:* `Y`
> *git hub? :* `N`
**DO NOT OVERWRITE `index.html`!!!**

**Deploy**
> `firebase deploy` (--only hosting)
