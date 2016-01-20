##**1.5.Característiques dels llenguatges més difosos.**

__Els llenguatges de programació més difosos corresponents a diferents àmbits,
a diferents tecnologies o a diferents tipus de programació tenen una sèrie de
característiques en comú que són les que marquen les similituds entre tots ells__.

###**1.5.1.Característiques de la programació estructurada.**

__Utilitza únicament tres estructures: seqüència, selecció i iteració, essent innecessari l’ús de la instrucció o instruccions de transferència incondicional, les característiques de la programació estructurada són la claredat, el teorema de l’estructura i el disseny descendent__.

####*Claredat*
__Hi haurà d’haver prou informació al codi per tal que el programa pugui ser entès i verificat: comentaris, noms de variables comprensibles i procediments entenedors... Tot programa estructurat pot ser llegit des del principi a la fi sense interrupcions en la seqüència normal de lectura__.

####*Teorema de l’estructura*
__Demostra que tot programa es pot escriure utilitzant únicament les tres estructures bàsiques de control__:

__*Seqüència*: instruccions executades successivament, una darrere l’altra. A la figura 1.8 es pot observar un exemple de l’estructura bàsica de seqüència, on primer s’executarà la sentència A i, posteriorment, la B__.

__*Selecció*: la instrucció condicional amb doble alternativa, de la forma “si condició, llavors SentènciaA, sinó SentènciaB”. A la figura 1.9 es pot observar un esquema que exemplifica l’estructura bàsica de selecció__.

__*Iteració*: el bucle condicional “mentre condició, fes SentènciaA”, que executa les instruccions repetidament mentre la condició es compleixi. A la figura 1.10 es pot observar un esquema que exemplifica l’estructura bàsica d’iteració__.

####*Disseny descendent*
__El disseny descendent és una tècnica que es basa en el concepte de “divideix i venceràs” per tal de resoldre un problema en l’àmbit de la programació. Es tracta de la resolució del problema al llarg de diferents nivells d’abstracció partint d’un nivell més abstracte i finalitzant en un nivell de detall__.

####*Programació modular*
__Es parla de programació modular, ens referim a la divisió d’un programa en parts més manejables i independents. Una regla pràctica per aconseguir aquest propòsit és establir que cada segment del programa no excedeixi, en longitud, d’un pam de codificació__.

####*Tipus abstractes de dades (TAD)*
__aquest concepte de tipus i no eren pocs els problemes que apareixien, lligats molt especialment a la complexitat de les dades que s’havien de definir. Va aparèixer la possibilitat de poder definir tipus abstractes de dades, on el programador pot definir un nou tipus de dades i les seves possibles operacions__.

###**1.5.2.Característiques de la programació orientada a objectes.**

__Un dels conceptes importants introduïts per la programació estructurada és l’abstracció de funcionalitats a través de funcions i procediments. Aquesta abstracció permet a un programador utilitzar una funció o procediment coneixent només què fa, però desconeixent el detall de com ho fa__.

__*Les funcions i procediments comparteixen dades del programa, cosa que provoca que canvis en un d’ells afectin a la resta*__. 

__*Al moment de dissenyar una aplicació és molt difícil preveure detalladament quines funcions i procediments necessitarem*__.

__*La reutilització del codi és difícil i acaba consistint a copiar i enganxar determinats trossos de codi, i retocar-los. Això és especialment habitual quan el codi no és modular*__.

####*Abstracció*
__És el procés en el qual se separen les propietats més importants d’un objecte de les que no ho són. És a dir, per mitjà de l’abstracció es defineixen les característiques essencials d’un objecte del món real, els atributs i comportaments que el defineixen com a tal, per després modelar-lo en un objecte de programari. En el procés d’abstracció no ha de ser preocupant la implementació de cada mètode o atribut, només cal definir-los__.

####*Encapsulació*
__Permet als objectes triar quina informació és publicada i quina informació és amagada a la resta dels objectes. Per això els objectes solen presentar els seus mètodes com a interfícies públiques i els seus atributs com a dades privades o protegides, essent inaccessibles des d’altres objectes. Les característiques que es poden atorgar són__:

__*Públic*: qualsevol classe pot accedir a qualsevol atribut o mètode declarat com a públic i utilitzar-lo__.

__*Protegit*: qualsevol classe heretada pot accedir a qualsevol atribut o mètode declarat com a protegit a la classe mare i utilitzar-lo__.

__*Privat*: cap classe no pot accedir a un atribut o mètode declarat com a privat i utilitzar-lo__.

####*Modularitat*
__Permet poder modificar les característiques de cada una de les classes que defineixen un objecte, de forma independent de la resta de classes en l’aplicació. En altres paraules, si una aplicació es pot dividir en mòduls separats, normalment classes, i aquests mòduls es poden compilar i modificar sense afectar els altres, aleshores aquesta aplicació ha estat implementada en un llenguatge de programació que suporta la modularitat__.

####*Jerarquia*
__Permet l’ordenació de les abstraccions. Les dues jerarquies més importants d’un sistema complex són l’herència i l’agregació.
L’herència també es pot veure com una forma de compartir codi, de manera que quan s’utilitza l’herència per definir una nova classe només s’ha d’afegir allò que sigui diferent, és a dir, reaprofita els mètodes i variables, i especialitza el comportament__.

####*El polimorfisme*
__És una característica que permet donar diferents formes a un mètode, ja sigui en la definició com en la implementació.
La sobrecàrrega (overload) de mètodes consisteix a implementar diverses vegades un mateix mètode però amb paràmetres diferents, de manera que, en invocar-lo, el compilador decideix quin dels mètodes s’ha d’executar, en funció dels paràmetres de la crida__.


