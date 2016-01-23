Existeixen molts llenguatges de programaci� diferents, fins al punt que moltes tecnologies tenen el seu llenguatge propi. Cada un d�aquests llenguatges t� un seguit de particularitats que el fan diferent de la resta.
Els llenguatges de programaci� m�s difosos s�n aquells que m�s es fan servir en cadascun dels diferents �mbits de la inform�tica.

L�**orientaci� a objectes** (en endavant, OO) �s un paradigma de construcci� de programes basat en una abstracci� del m�n real.
En un programa orientat a objectes, l�abstracci� no s�n els procediments ni les funcions, s�n els objectes. Aquests objectes s�n una representaci� directa d�alguna cosa del m�n real, com ara un llibre, una persona, una organitzaci�, una comanda, un empleat...

Un **objecte** �s una combinaci� de dades (anomenades atributs) i m�todes(funcions i procediments) que ens permeten interactuar amb ell. En OO, doncs, els programes s�n conjunts d�objectes que interactuen entre ells a trav�s de missatges (crides a m�todes).

**Abstracci�**

�s el proc�s en el qual se separen les propietats m�s importants d�un objecte de les que no ho s�n. �s a dir, per mitj� de l�abstracci� es defineixen les caracter�stiques essencials d�un objecte del m�n real, els atributs i comportaments que el defineixen com a tal, per despr�s modelar-lo en un objecte de programari.

**Encapsulaci�**

Permet als objectes triar quina informaci� �s publicada i quina informaci� �s amagada a la resta dels objectes. Per aix� els objectes solen presentar els seus
m�todes com a interf�cies p�bliques i els seus atributs com a dades privades o protegides, essent inaccessibles des d�altres objectes. Les caracter�stiques que es poden atorgar s�n:
Entorns de desenvolupament 30 Desenvolupament de programari
* P�blic: qualsevol classe pot accedir a qualsevol atribut o m�tode declarat com a p�blic i utilitzar-lo.
* Protegit: qualsevol classe heretada pot accedir a qualsevol atribut o m�tode declarat com a protegit a la classe mare i utilitzar-lo.
* Privat: cap classe no pot accedir a un atribut o m�tode declarat com a privat i utilitzar-lo.
    
**Modularitat**

Permet poder modificar les caracter�stiques de cada una de les classes que defineixen un objecte, de forma independent de la resta de classes en l�aplicaci�.

**Jerarquia**

Permet l�ordenaci� de les abstraccions. Les dues jerarquies m�s importants d�un sistema complex s�n l�her�ncia i l�agregaci�.
L�her�ncia tamb� es pot veure com una forma de compartir codi, de manera que quan s�utilitza l�her�ncia per definir una nova classe nom�s s�ha d�afegir all�
que sigui diferent, �s a dir, reaprofita els m�todes i variables, i especialitza el comportament.

**El polimorfisme**

�s una caracter�stica que permet donar diferents formes a un m�tode, ja sigui en la definici� com en la implementaci�.

La **sobrec�rrega (overload)** de m�todes consisteix a implementar diverses vegades un mateix m�tode per� amb par�metres diferents, de manera que, en invocar-lo, el compilador decideix quin dels m�todes s�ha d�executar, en funci� dels par�metres de la crida.

Un exemple de m�tode sobrecarregat �s aquell que calcula el salari d�un treballador en una empresa. En funci� de la posici� que ocupa el treballador tindr� m�s o menys conceptes a la seva n�mina (m�s o menys incentius, per exemple).

La **sobreescriptura (override)** de m�todes consisteix a reimplementar un m�tode heretat d�una superclasse exactament amb la mateixa definici� (incloent nom de m�tode, par�metres i valor de retorn).

Un exemple de sobrec�rrega de m�todes podria ser el del m�tode *Area()*. A partir d�una classe *Figura* que cont� el m�tode *Area()*, existeix una classe derivada per a alguns tipus de figures (per exemple *Recangle* o *Quadrat*).
