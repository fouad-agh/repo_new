##Codi font

Per crear un programa el que es far� ser� crear un arxiu i escriure a un fitxer 
el seguit d'instruccions que es vol que l'ordinador executi. Aquestes instruccions 
hauran de seguir unes pautes determinades en funci� del llenguatge de programaci�
escollit. A m�s , haurien de seguir un ordre determinat que donar� sentit al programa
escrit. Per  comen�ar n'hi haur� prou amb un editor de text simple.

Un cop s'ha acabat d'escriure el programa, el conjunt de fitxers de text resultants,
on es troben les instruccions, es diu que contenent **el codi font**. Aquest codi font 
pot ser des d'un nivell molt alt, molt a prop del llenguatge hum�, fins a un de nivell
m�s baix, m�s proper al codi de les m�quines, com ara el codi assemblador.

El proc�s anomenat **compilaci�** �s la traducci� del cdi font dels fitxers del programa en fitxers en format binari que contenen les instruccions en un format que el processador pot entendre. El cntingut d'aquests fitxers s'anomena **codi objecte**. El programa que fa aquest proc�s s'anomena **compilador**.

El **codi objecte** �s el codi font tradu�t (pel compilador) a codi m�quina, per� aquest codig encara no pot ser executat per l'ordinador.

El **codi executable** �s la traducci� completa a codi m�quina, duta a terme per l'enlla�ador (en angl�s, *linker*). El codi executable �s interpretat directament per l'ordinador.

L'**enlla�ador** �s l'encarregat d'inserir al codi objecte les funcions de les llibreries que s�n necess�riues per al programa i de dur a terme el proc�s de muntatge generarnt un arxiu executable.

Una **llibreria** �s un col�lecci� de codi predefinit que facilita la tasca del programador a l'hora de codificar un programa.

**1.2.1 M�quina virtual**

El concepte de m�quina virtual sorgeix amb l�objectiu de facilitar el desenvolupament de compiladors que generen codi per a diferents processadors.
La compilaci� consta de dues fases:
* La primera parteix del codi font a un llenguatge intermedi obtenint un programa equivalent amb un menor nivell d�abstracci� que l�original i que no pot ser directament executat.
* La segona fase tradueix el llenguatge intermedi a un llenguatge comprensible per la m�quina.
