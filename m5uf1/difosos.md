Existeixen molts llenguatges de programació diferents, fins al punt que moltes tecnologies tenen el seu llenguatge propi. Cada un d’aquests llenguatges té un seguit de particularitats que el fan diferent de la resta.
Els llenguatges de programació més difosos són aquells que més es fan servir en cadascun dels diferents àmbits de la informàtica.

L’**orientació a objectes** (en endavant, OO) és un paradigma de construcció de programes basat en una abstracció del món real.
En un programa orientat a objectes, l’abstracció no són els procediments ni les funcions, són els objectes. Aquests objectes són una representació directa d’alguna cosa del món real, com ara un llibre, una persona, una organització, una comanda, un empleat...

Un **objecte** és una combinació de dades (anomenades atributs) i mètodes(funcions i procediments) que ens permeten interactuar amb ell. En OO, doncs, els programes són conjunts d’objectes que interactuen entre ells a través de missatges (crides a mètodes).

**Abstracció**

És el procés en el qual se separen les propietats més importants d’un objecte de les que no ho són. És a dir, per mitjà de l’abstracció es defineixen les característiques essencials d’un objecte del món real, els atributs i comportaments que el defineixen com a tal, per després modelar-lo en un objecte de programari.

**Encapsulació**

Permet als objectes triar quina informació és publicada i quina informació és amagada a la resta dels objectes. Per això els objectes solen presentar els seus
mètodes com a interfícies públiques i els seus atributs com a dades privades o protegides, essent inaccessibles des d’altres objectes. Les característiques que es poden atorgar són:
Entorns de desenvolupament 30 Desenvolupament de programari
* Públic: qualsevol classe pot accedir a qualsevol atribut o mètode declarat com a públic i utilitzar-lo.
* Protegit: qualsevol classe heretada pot accedir a qualsevol atribut o mètode declarat com a protegit a la classe mare i utilitzar-lo.
* Privat: cap classe no pot accedir a un atribut o mètode declarat com a privat i utilitzar-lo.
    
**Modularitat**

Permet poder modificar les característiques de cada una de les classes que defineixen un objecte, de forma independent de la resta de classes en l’aplicació.

**Jerarquia**

Permet l’ordenació de les abstraccions. Les dues jerarquies més importants d’un sistema complex són l’herència i l’agregació.
L’herència també es pot veure com una forma de compartir codi, de manera que quan s’utilitza l’herència per definir una nova classe només s’ha d’afegir allò
que sigui diferent, és a dir, reaprofita els mètodes i variables, i especialitza el comportament.

**El polimorfisme**

És una característica que permet donar diferents formes a un mètode, ja sigui en la definició com en la implementació.

La **sobrecàrrega (overload)** de mètodes consisteix a implementar diverses vegades un mateix mètode però amb paràmetres diferents, de manera que, en invocar-lo, el compilador decideix quin dels mètodes s’ha d’executar, en funció dels paràmetres de la crida.

Un exemple de mètode sobrecarregat és aquell que calcula el salari d’un treballador en una empresa. En funció de la posició que ocupa el treballador tindrà més o menys conceptes a la seva nòmina (més o menys incentius, per exemple).

La **sobreescriptura (override)** de mètodes consisteix a reimplementar un mètode heretat d’una superclasse exactament amb la mateixa definició (incloent nom de mètode, paràmetres i valor de retorn).

Un exemple de sobrecàrrega de mètodes podria ser el del mètode *Area()*. A partir d’una classe *Figura* que conté el mètode *Area()*, existeix una classe derivada per a alguns tipus de figures (per exemple *Recangle* o *Quadrat*).
