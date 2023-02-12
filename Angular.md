# Angular

**Angular weblap: angular.io**
> setup (Angular CLI - ezt telepítjük)

*npm install -g @angular/cli*

**Telepítési infok**
> https://www.youtube.com/watch?v=CF1UoJf2j4Q&ab_channel=doroghouse

- **Új projekt:**
> *ng new ElsoProjekt*

- **start:**
> *ng serve*

- **Új komponens:**
> *ng g c ElsoKomponens*

- **Új komponens másikon belül:**
> *ng g c test/SubTest*

- **Új modul:** 
> *ng g m Test*

- **Új direktíva:**
> *ng g d TestDirective*

- **Install bootstrap:**
> *npm install bootstrap*

- **bootstrap include:**
> *root > angular.json: styles tömbbe: `["node_modules/bootstrap/dist/css/bootstrap.min.css","src/styles.scss"]`*

> *javascript script tömbbe `["node_modules/bootstrap/dist/js/bootstrap.min.js"]`*

> *ng g c test --skip-tests* **(komponens .spec fájl nékül)**

**ng g c test --help**

### Bindingok:

> property binding:
(saját attributum)
pl `<app-recept *ngFor="let recept of receptek" [recept]="recept"></app-recept>`
[recept] - kapcsolódó osztályban paraméter

> beépített pipe-ok:
angolar.io/api > API List > Filter: pipe

**[Firebase](https://firebase.google.com/)**
> https://firebase.google.com/

**auth:**
> https://firebase.google.com/docs/reference/rest/auth

**loading icons:**
> https://loading.io/css