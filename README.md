Introduccio-als-llenguatges-de-marques

Ejemplo html:




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


|Això és una línia normal
a la dreta del símbol > posem la frase que volem convertir en cita


> "In a few moments he was barefoot, his stockings folded in his pockets and his
  canvas shoes dangling by their knotted laces over his shoulders and, picking a
  pointed salt-eaten stick out of the jetsam among the rocks, he clambered down
  the slope of the breakwater."


també podem col·locar un caràcter d'intercalació en cada línia de la cita. Això és particularment útil si la seva cotització abasta diversos paràgrafs. Per exemple:

> His words seemed to have struck some deep chord in his own nature. Had he spoken
of himself, of himself as he was or wished to be? Stephen watched his face for some
moments in silence. A cold sadness was there. He had spoken of himself, of his own
loneliness which he feared.
>
> —Of whom are you speaking? Stephen asked at length.
>
> Cranly did not answer.

Recordeu que fins i tot les línies en blanc ha de contenir el caràcter d'intercalació. Això assegura que tota la blockquote s'agrupa junts.

>Hi havia una vegada, que un noi va començar a estudiar llenguatge de marca....

li agrada tant, que es va apuntar a dos mòduls més.

Ara estudia fins els caps de setmana

Les cites en bloc poden contenir altres elements de rebaixes, com cursiva, imatges o enllaços.

>  [enllaç 1][1], [enllaç 2][2], [enllaç 3][3]

 [1]: http://www.google.es
 [2]: http://www.yahoo.es
 [3]: http://www.bing.com


* Targeta gràfica
* Memòria ram
* Cpu

Es poden emprar també + i - en comptes de *

* Cable sata
+ Pasta tèrmica
- Ventilador

Es poden barrejar diferents tipus de llistes i niar unes dins les altres.

1. Això és una llista ordenada

2. Segon element de la llista ordenada

     1. Aquesta és una llista ordenada imbricada dins d'una altra
     
         * Llista sense endreçar imbricada a tercer nivell
         
         * Segon element d'aquesta llista
         
     2. Aquest és el segon element de la llista ordenada imbricada
  
                                             Llistes de definicions
Es poden crear llista de definicions, que estan compostes de termes i les definicions dels mateixos, com si fos un diccionari. La seva creació és molt senzilla:


primer terme
 : Primera definició

segon terme
 : Segona definició
 
 Es poden aplicar més d'una definició a un termini

primer terme
 : Primera definició
 : Segona definició

segon terme
 : Segona definició
 
 
Es poden aplicar més d'un terme a una definició

primer terme
segon terme
 : Primera definició

tercer termini
 : Segona definició
 
 
Si deixem una línia en blanc entre el terme i la definició, es creés un paràgraf per a la definició.

primer terme

: Primera definició

segon terme
 : Segona definició
 
 Una definición puede constar de varios párrafos.

Primer termino
 : Primera definición

Segundo párrafo de la primera definición

Segundo termino
 : Segunda definición
 
 
                                              imatges
La manera d'enllaçar imatges és bàsicament la mateixa de crear enllaços, amb un única diferència, s'afegeix el caràcter exclamació! al principi de la parella de claudàtors que defineixen el nom de l'enllaç. exemples:

![Con titulo](http://www.gifsanimados.org/data/media/271/barco-imagen-animada-0031.gif "vaixell")


![Sin titulo](http://www.gifsanimados.org/data/media/271/barco-imagen-animada-0031.gif)


![Imagen 1][1]  ![Imagen 2][2]

 [1]: http://www.gifsanimados.org/data/media/271/barco-imagen-animada-0031.gif
 [2]: http://cdn5.dibujos.net/dibujos/pintados/201211/barco-pirata-cuentos-y-leyendas-piratas-pintado-por-alexrider-9724406.jpg ""vaixell"
