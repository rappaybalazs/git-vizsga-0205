** Adott projekt klónozása saját gépre **

* mkdir git-vizsga-0205
* cd mkdir git-vizsga-0205
* git init
* git pull https://github.com/szpeter992/git-vizsga-0205

** Projekten belül hozzatok létre egy „README.md” elnevezésű fájlt **

* touch README.md

** A projekthez hozzatok létre egy gitignore fájlt, melyben rögzítsétek, hogy a txt,doc,docx,pdf kiterjesztésű fájlokat hagyjuk figyelmen kívül. **

* touch .gitignore

//
*.txt
*.doc
*.docx
*.pdf

//

** Projekten belül hozzatok létre egy új ágat, melynek neve legyen „console” **

* git branch console

** Az új ágon az app.js fájl-t módosítsátok úgy, hogy ha az oldal betöltődött, akkor a consolba ezt írjuk ki -> rögzítsük a változtatást **

* git checkout console
* git add app.js

** Szintén ebben az új ágban a css fájlban módosítsátok a weboldal háttér színét egy általatok választott átmenetes színre -> rögzítsük a változtatást **

* git add style.css

** Rögzítsük ezt a változtatást a verzióban és pusholjátok fel a projektet a  saját github fiókotokba **

*

