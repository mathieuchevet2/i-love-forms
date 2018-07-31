# README

## Lancer le programme  
Télécharger le projet
```sh
git clone https://github.com/mathieuchevet2/i-love-forms
```
Installer les gems
```sh
bundle install --without production
```
Genérer la base de donnée
```sh
rails db:migrate
```
Lancer le serveur 
```sh
rails server
```
[Lien vers le localhost](https://localhost:3000/)<br>
[Lien vers le heroku](https://moussaillon-thp-2018.herokuapp.com)
## Table  

Le projet ne comporte qu'une seule table: 
<ul>
       <li> La table Users </li>
       <li>. 3 colonnes username, email et bio </li>
</ul>

|       Users            	|
| :------------------------:|
| ***username*** `:string`  |
| ***email***  `:string` 	|
| ***bio***    `:text`    	|
