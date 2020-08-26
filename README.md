# SASS Transpiler
## Installation
#### SASS Transpiler est un projet à cloner n'importe où :
```shell script
# Via HTTPS
git clone https://github.com/Jason-Essentiel/sass-transpiler.git

OU

# Via SSH (Nécessite un accord et un partage de clé RSA publique au préalable)
git clone git@github.com:Jason-Essentiel/sass-transpiler.git
```
Une fois cloné, **créez** un **dossier** `sass` à côté du **package.json**
### Vous êtes prêt !
Votre dossier doit ressembler à ça : 
```bash
/sass-transpiler/
|-- sass
|   |-- original.sass
|   |-- original.css
|   |-- tests
|   |   |-- test.sass
|   |   |-- test.css
|-- package.json
|-- package-lock.json
|-- README.md
```
Maintenant, tous les fichiers .sass ou .scss contenu récursivement dans le dossier **sass** seront transpilés en fichiers **CSS**, à côté de leurs originaux respectifs, dès lors que vous ouvrirez un **terminal** et que vous y lancerez la **commande** suivante :
```shell script
npm run watch
```
