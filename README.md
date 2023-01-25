# Pokedex
https://hovinhthanh7893.github.io/pokedex/

# WORK ON MAIN BRANCH
git checkout main

# DEPLOY ON GH-PAGES BRANCH
git checkout gh-pages

-------------------------------------------------------

## Install
npm install -g @angular/cli

## Init project
ng new project-folder-name

## Run dev
ng serve --open

## Create new header
ng g c header

## Create service for data
ng g s service/data

## Import HttpClientModule to app.module.ts
## Import HttpClient to data.service.ts > getPokemons function

## Create new pokemon list
ng g c pokemon-list

## Install pagination
npm install ngx-pagination --save

## Import NgxPaginationModule to app.module.ts

## Create new footer
ng g c footer

---------------------------------------------------------------

## Install package for gh-pages
ng add angular-cli-ghpages

## Deploy to gh-pages
ng deploy --base-href=https://hovinhthanh7893.github.io/pokedex/