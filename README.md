FirstNPM
========

Creiamo il nostro primo progetto in [Node](http://nodejs.org/). 
Scarichiamo l'istaller o cloniamo il progetto tramite git e poi effettiamo l'installazione.

Dopodichè: 
* creiamo una cartella per il nostro progetto.
    * eseguiamo l'init della directory.
* installiamo [Mocha](http://mochajs.org/) e [Chai](http://chaijs.com/):
    * creamo un piccolo test.
    * eseguiamo il test da npm.
* installiamo [Grunt](http://gruntjs.com/) e [grunt-contrib-uglify](https://www.npmjs.com/package/grunt-contrib-uglify).
    * creamo un piccolo file js.
    * eseguiamo uni script di build sul file js.
  

```shell
mkdir 'newProject'
cd 'newProject' 

npm init 

npm install mocha --save
npm install chai --save

mkdir test
$EDITOR test/test.js

npm test

mkdir 'newProjectGrunt'
cd 'newProjectGrunt' 

npm init 

npm install grunt --save
npm install grunt-contrib-uglify --save-dev

mkdir src
$EDITOR src/firstNPM.js

$EDITOR Gruntfile.js

grunt
```
