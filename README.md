# Pokedex
https://hovinhthanh7893.github.io/pokedex/

//Install
npm install -g @angular/cli

//Init project
ng new project-folder-name

//Run dev
ng serve --open

//create new header
ng g c header

//create service for data
ng g s service/data

//import HttpClientModule to app.module.ts
//import HttpClient to data.service.ts > getPokemons function

//create new pokemon list
ng g c pokemon-list

//Install pagination
npm install ngx-pagination --save

//import NgxPaginationModule to app.module.ts

//create new footer
ng g c footer




//package for gh-pages
ng add angular-cli-ghpages

//deploy to gh-pages
ng deploy --base-href=https://hovinhthanh7893.github.io/pokedex/
