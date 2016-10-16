Introduccio-als-llenguatges-de-marques


*Markdown

  *Que és Markdown?
  
*sintaxi Markdown

  *capçaleres
  
  *Enllaços
  
  *paràgrafs
  
  *format
  
  *cites
  
  *llistes
  
  *Llistes de definicions
  
  *imatges
  
  *taules
  
  *codi
  
  *línies Horitzontals
  
  *escapar caràcters
  
  *Notes a peu de pàgina
  
  *abreviatures
  
  *Indentificadores de capçalera
  
*Pygments

  *Lexers de Pygments més comuns per ressaltat de sintaxi
  
                                Que és Markdown?
Markdown és un llenguatge de marcat lleuger semblant al que s'empra en moltes wikis i basat originalment en convencions existents en el marcatge dels correus electrònics. Empra text pla, procurant que sigui llegible però aconseguint que esdevingui XHTML correctament formatat. Els articles d'aquest lloc estan elaborats emprant Markdown, sense utilitzar cap tipus d'editor visual WYSIWYG, el que facilita el crear documents XHTML nets i fàcilment editables en el futur. En són un bon exemple de les capacitats de Markdown. Encara que no és molt conegut, comença a ser molt popular i utilitzat entre els programadors.

Per conèixer més sobre Markdown, es poden llegir els articles en els que explico perquè és el més adequat per crear un bloc i perquè ho he triat per aquest lloc, articles Markdown

                                 capçaleres
# Això és un H1    

## Això és un H2

### Això és un H3

#### Això és un H4

##### Això és un H5

###### Això és un H6
                                 
                                 Enllaços
Existeixen també dues maneres de crear enllaços, es poden veure a continuació:

   
[amb títol](http://www.google.es "google")

[sense títol](http://www.google.es)

[enllaç 1][1], [enllaç 2][2], [enllaç 3][3]

 [1]: http://www.google.es
 [2]: http://www.yahoo.es
 [3]: http://www.bing.com

  Hi ha una manera addicional de crear enllaços automàtics per a adreces URL, simplement tancar-la entre els caràcters menor <que i major que>:
  
  <http://www.google.com>
  
                                  paràgrafs
Per crear paràgrafs es deixa una línia en blanc. D'aquesta manera.

Aquest és el primer paràgraf.

Aquest és el segon paràgraf.


Aquesta és la primera línia
i aquest és el salt de línia.

                                  format
El format bàsic del text, és a dir negretes i cursiva, es poden realitzar de diverses maneres:

| tecleges    | obtens     |
| ------------- | ------------- |
|**  ** enmig la paraula a posar en negreta | **això és negreta**|
|__   __enmig la paraula a posar en negreta |__això també és negreta__|
|*  * enmig la paraula a posar en cursiva | *això és cursiva*|
|_   _enmig la paraula a posar en cursiva |_això també és cursiva_|
|***  *** enmig la paraula a posar en negreta i cursiva | ***això és negreta i cursiva***|
|___   ___enmig la paraula a posar en negreta i cursiva |___això també és negreta i cursiva___|

                                   cites
Per crear blocs de cita, s'empra el caràcter més gran que> abans del bloc de text. A la següent taula es poden veure les opcions per crear-los.


| tecleges    | obtens     |
| ------------- | ------------- |
|Això és una línia normal
a la dreta del símbol > "la frase per convertir en cita" |> "la frase per convertir en cita" |
|__   __enmig la paraula a posar en negreta |__això també és negreta__|
|*  * enmig la paraula a posar en cursiva | *això és cursiva*|
|_   _enmig la paraula a posar en cursiva |_això també és cursiva_|
|***  *** enmig la paraula a posar en negreta i cursiva | ***això és negreta i cursiva***|
|___   ___enmig la paraula a posar en negreta i cursiva |___això també és negreta i cursiva___|


> "In a few moments he was barefoot, his stockings folded in his pockets and his
  canvas shoes dangling by their knotted laces over his shoulders and, picking a
  pointed salt-eaten stick out of the jetsam among the rocks, he clambered down
  the slope of the breakwater."
