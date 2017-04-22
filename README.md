# Developper Skills Simon


**Curriculum**   
Je décris ici mes compétences de programmation ReactJS utilisé dans le développement de [skiscool.com](https://www.skiscool.fr)

Ici la liste des dépendances du projet:

-> [![Dependency Status](https://david-dm.org/simonjoom/Competence.svg?style=flat-square)](https://david-dm.org/simonjoom/Competence)
[![devDependency Status](https://david-dm.org/simonjoom/Competence/dev-status.svg?style=flat-square)](https://david-dm.org/simonjoom/Competence#info=devDependencies)


---------------------------------------------------

## Au sujet du projet

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;J'ai développé le site-web de mon école de ski avec la collaboration d'un programmeur,  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ce projet m'a permis d'apprendre beaucoup de ReactJS et des API de feathers.  

 Le site est configuré multi-langue et entièrement real-time (feathers) et responsible.  
Le design utilise material-ui.  
La gestion de la langue est interne avec un router personnalisé, chaque langue correspond à un domaine ou sous domaine pour un meilleur CEO.

      https://www.skiscool.fr pour le français  
      https://www.ski-courchevel.deals pour l'anglais   
      https://ru.skiscool.com pour le russe   
      https://pt.skiscool.com pour le portugais  


 J'ai d'abords commencé par un boilerplate isomorphique dans le soucis de référencement, cependant le projet devenant trop complexe a mettre en oeuvre ; j'ai alors opté pour un projet plus simple utilisant un stand-alone web applications (SPA) couplé a prerender-io pour le référencement.

Voici le lien du boilerplate utilisé comme base:
https://github.com/kriasoft/react-static-boilerplate


## Serveur:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Le site web est hébergé sur un kimsufi tournant sur le dernier debian, j'administre moi même et sécurise mon serveur debian.  
(firewall, bind9, mongodb, courrier etc...)   

**Nginx** last version 1.12 sert le code et le rewriting en première couche, apache est en 2éme couche pour le serveur PHP/Mysql : un proxy fait tourner mon ancien site-web en PHP avec apache; nginx gère mon nouveau site-web servi par nodejs.  

**PageSpeed** est utilisé.  

Mon ancien site-web utilise **PHP7 / MySQL** cependant je ne continue plus son développement, il me sert juste à garder mes anciennes url et ainsi garder mon page-rank.   


#### Softwares utilisé pour le développement: 
* Mac OS
* Webstorm
* Sourcetree
* Robomongo
* Photoshop

#### Connaissances: 

✓ **Webstorm** pour le développement.  
✓ **Feathers** pour les Api comme la gestion du payment en ligne et du systeme d'authentification.  (http://feathersjs.com)  
✓ Maitrise **Photoshop, Illustrator, Gimp** .. et autres outils **PAO**  
✓ Maitrise de **Markdown** et **Sourcetree** pour la gestion de projet.  
✓ Maitrise de **FileZilla**.    
✓ Connaissance de **Mongodb**  
✓ Connaissance de **React-native**  développement de l'application mobile.  
✓ Utilisation de **CSS3** comme les transitions.  
✓ Parle **Anglais et Russe couramment**.  
 
Ancien utilisateur windows, je ne travaille plus que sur **Mac OS**;  
J'ai aussi de très bonne connaissance en **PHP/MYSQL** mais cela me semble obsolète par rapport à React et NodeJS.  

Excellentes connaissance en **CEO** gestion balise, title, description ... keywords in page.

**Efficacité**:
Toutes les connaissances ReactJS énoncées en bas de page ont été apprise en seulement un an d'apprentissage et de développement.

#### Efficacité du boilerplate:
Le nouveau site-web sous react utilisant prerender m'a permis de remonter sur les premières page sur le classement google avec les mots clefs: 'ski school courchevel'  
Ce site-web m'a permis de concurrencer mes concurrents et d'attirer de nouveaux clients.  



#### ReactJS/NodeJS

Voici ci-dessous la description des technologies React utilisées:

✓ Babel with babel-runtime , external polyfill for old browsers.  
✓ Deep knowledge using "Promise" and async  
✓ Api avec Mongodb using the amazing library Feathers,  
✓ Chat system using socket-io  
✓ API with feathers creation hooks , database with mongodb.    
✓ Gestion login with feathers library  
✓ Gestion online payment with feather and stripe   
✓ Last web pack 2  
✓ Code-splitting and HMR (Hot Module Replacement)   
✓ Https using different certificate for each domain/subdomain  
✓ Gestion state with mobx (a mon sens bien plus efficace et plus facile à maintenir que redux)  
✓ Material-ui with:  https://github.com/callemall/material-ui/tree/next/src  
✓ Optimisation du code with react-lite et une librairie minimal jQuery zepto.js  
✓ Création de chart with google-chart  
✓ Géolocalisation , Map with a mod of mapbox.js  
✓ Css with basscss with font-awesome  
✓ Using Prerender-io to generate page for CEO   
(_escaped_fragment_) see below:  
-> https://www.skiscool.fr/?_escaped_fragment_=


### Techno boilerplate app Simon:
This is a starter boilerplate app   
**fontawesome + mobx + material-ui** 

* [React](https://github.com/facebook/react)
* [Babel](http://babeljs.io) for ES6 and ES7 magic
* [Webpackv2](http://webpack.github.io) for bundling
* [ProxyPass with nginx](http://nginx.org/en/docs/http/ngx_http_proxy_module.html) Nginx manage javascript-cors and help us to develop under http://www.mysite.com (port 80)
* [Express](http://expressjs.com)
* [Feathers](https://github.com/feathersjs) Api with feathers
* [Feathers-stripe](https://github.com/feathersjs/feathers-stripe) Api payment call with stripe.
* [Webpack code splitting](https://webpack.github.io/docs/code-splitting.html) Code splitted depending language and routes with require.ensure  
* [Webpack Dev Middleware](http://webpack.github.io/docs/webpack-dev-middleware.html)
* [Webpack Hot Middleware](https://github.com/glenjamin/webpack-hot-middleware)
* [Mobx](https://mobxjs.github.io/mobx/best/devtools.html) Better than redux in my opinion to maintain code  
* [mobx Dev Tools](https://github.com/mobxjs/mobx-react-devtools) for next generation DX (developer experience). 
* [ESLint](http://eslint.org) to maintain a consistent code style 
* [material-ui](https://github.com/callemall/material-ui/tree/next/src) material-ui source code
* [mobx-react-form](https://github.com/foxhound87/mobx-react-form) mobx reac form validation AJV 
* [style-loader](https://github.com/webpack/style-loader), 
* [MAP](https://github.com/mapbox/mapbox.js), Mapbox pour le plan des piste
* [less-loader](https://github.com/webpack/less-loader) to allow import of stylesheets in plain css, sass and less,
* [async-js](https://www.npmjs.com/package/async-js) async to load javascript dynamically
* [prerender](https://github.com/prerender/prerender) CEO Prerender
* [fontawesome](http://fontawesome.io)  font awesome
* [CSS](http://basscss.com) BASSCSS Lightning Fast Modular CSS with No Side Effects
* [markdown-it](https://www.npmjs.com/package/markdown-it) Mardown to display view


### Code optimization:
* [Optimization react-lite](https://github.com/Lucifier129/react-lite) React-lite 60% lighter than react.
* [Optimization Jquery](https://github.com/madrobby/zepto)  minimalist JavaScript library jquery


 ![logo skiscool courchevel](https://skiscool.com/dist/icons/logo.png)


