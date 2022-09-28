# Treball d'entorns
**Java, Python, C#, SQL** 

**Activitat de recerca de llenguatges de programació**        

D'aquests llenguatges heu de comentar obligatòriament els següents aspectes:               
• Naixement, creadors i evolució històrica.                    
• Característiques del llenguatge.               
• Imperatiu, declaratiu, OOP...               
• Compilat, interpretat, híbrid...               
• Principals novetats o aportacions respecte altres llenguatges.               


# Java
## Què és Java?
---
Java es el **tercer llenguatge de programació més popular del mòn** segons la famosa llista **TIOBE**, va ser disenyada i **creada l'any 1996 per "James Gosling" de Sun Microsystems (Corporation)**. La seva sinatxis es deriva en una gran part de C i C++. 

Les aplicacions fetes en Java son compilades a **bytecode**, que pot ser executada en qualsevol JVM (màquina virtual de Java).
<p align="center">
  <img src="java1.svg" />
</p>

## Característiques de Java.
---
La característica més important de Java es el **"OOP"** es a dir, (Programació Orientada a Objectes). Els llenguatges de programació que tenen aquesta característica tenen en comú que utilitzen les entitats **"objectes"**, es a dir, una combinació de variables, funcions i dades.

Una altra característica que fa a Java un llenguatge de programació molt respetable es el seu lema, **"write once, run anywhere"**, amb el significat de que Java es capaç de escriure un programa una vegada i que es pugui executarse desde qualsevol dispositiu, independement del hardware.

Java compila el codi font per a generar el codi **"bytecode"**, del que hem parlat abans. Aquest llenguatge **"bytecode"** son instruccions de màquina simplificades. Aquest codi no es codi font, però tampoc es codi màquina, es un llenguatge que només Java el pot entendre, després, la **màquina virtual (JVM)** s'encarrega de interpretar i executar el codi.


## Utilització de Java.
---
Un dels IDE mes comuns per a Java sol ser **Eclipse**, o també **IntelIJ IDEA**, i es poden fer una gran varietat de projectes amb Java, degut a la seva gran versatibilitat. 

Java serveix per a fer:
  1. Videojocs
  2. Aplicacions móbils per Android
  3. Aplicacions de escritori
  4. Aplicacions web
 
 
 
## Avantatges i desavantatges.
---
### Avantatge

**1. Multiplataforma**      
        Java funciona independentment del tipo de **plataforma**, es a dir, es pot executar en **Windows, Linux, Mac**, inclús en el **telèfon mobil**!     
        
**2. Fàcil d'apendre.**                
       La curva d'aprenentatge de Java es **curta**, i la sintaxis es fàcil d'apendre, ademés, es pareix a C i C++ en alguns aspectes.     
       
**3. Programació orientada a objectes**.                 
       Els conceptes **"OOP"** de Java ajuden a resoldre problemes del món real. També ajuda a mantenir el codi gran dividint-los en fragments amb nom més petits. 
       
**4. Java es d'alt nivell.**                
        Los llenguatges de baix sòn més dificils d'entendre, els de alt nivell tenen moltes paraules de **l'anglès**, lo qual el fa més fàcil d'apendre i de llegir.      
### Desavantatges

**1. Baix rendiment**                 
      Java es més lent en comparació amb els llenguatges de programació natius com **C i C++**, això es deu al treball adicional per convertir el codi en llenguatge **màquina**.      
      
**2. Memoria**              
      L'administració de **memòria** de Java no es molt bona comparada amb altres llenguatges de programació com per exemple **C++**.    
      
**3. GUI (Interfície d'usuari)**              
      Alhora de desenvoluipar GUI's, Java es queda enrere, degut a que no es poden fer interfícies molt complexes. 
      Els llenguatges moderns com **Python, R, o C#** tenen la posibilitat de crear interfícies mes complexes que Java.      
      
  ## Exemple de codi.
  
    
      public class holaMundo {

        public static void main(String[] args) {
            System.out.println("Hola mòn!");
        }
    }
    
  **Output:**
  *Hola mòn!*
  
  
  Demanar el nom a l'usuari i mostrar-lo en Java
  ---
 
      import java.util.Scanner;

      public class HolaUser {
          public static void main(String[] args) {

              Scanner ent = new Scanner(System.in);
              String nom;

              nom = ent.nextLine();

              System.out.println("Hola, " + nom);

          }
      }
      
  **Input:** Eric   
  **Output:** *Hola, Eric*
  
  
## Infojobs i Java.

Hi han **818 ofertas de Java en tota Espanya**. Comparat amb altres, hi ha **588** ofertes per a **Python**, **242** per a **C++**, i **392** per a **C#**.       
Un salari considerat **"baix"** per a un **Java Developer son 19.900 a l'any.**     
Un salari considerat **"mitjà"** per a un **Java Developer son 31.200 a l'any.**      
Un salari considerat **"alt"** per a un **Java Developer son +45.000 a l'any.**      

Informació extreta de "jobted" --> https://www.jobted.es/salario/programador-java     


## Conclusió
---

Podríem dir que Java es un dels llenguatges més populars en l'actualitat. Molta gent el califica com "antic", pero la realitat es que alhora de buscar treball, encara hi ha moltísimes ofertes de feina per en aquest llenguatge. Encara que Java tingui alguns problemes amb la memòria, les seves qüalitats fan que prosperi per molts anys més.


## Webgrafia  
---

https://es.wikipedia.org/wiki/Java_(lenguaje_de_programaci%C3%B3n)    
https://www.jobted.es/salario/programador-java    
https://www.infojobs.net    
https://ca.wikipedia.org/wiki/Programaci%C3%B3_orientada_a_objectes   
https://en.wikipedia.org/wiki/Object_(computer_science)   


# Python

## Què és Python?


Python es el **llenguatge de programació més popular del mòn** segons la famosa llista **TIOBE** és un llenguatge **d'alt nivell** de programació **interpretat**.  
Va ser disenyat l'any 1991, per **Guido van Rossum**, en **Python Software Foundation**.

Python s'epecialitza en la **llegibilitat del seu codi**, d'aqui tota la seva popularitat en els darrers anys. S'utilitza per desenvolupar aplicacions de tot tipus. 

<p align="center">
  <img src="https://user-images.githubusercontent.com/113585897/191532394-1909c176-e531-40e0-b725-966b71d31d2c.png" />
</p>


El codi que segueixi els principis de **Python** es diu que és “pytònic”. Aquests principis van ser descrits pel desenvolupador de Python **Tim Peters** a El Zen de Python

![prova](https://user-images.githubusercontent.com/113585897/191541778-b898a45e-2263-4029-90ca-10d7067d88cd.PNG)



## Característiques de Python.
---


### Programació Orientada a objectes (POO):

Com altres llenguatges populars com Java, C++ o Javascript, Python és un llenguatge **orientat a objectes**. Un llenguatge orientat a objectes és aquell en què el codi s'organitza en unitats anomenades classes i objectes. Això permet representar **conceptes quotidians** en un programa.


### Llenguatge interpretat:

Hi ha dos tipus de llenguatges: **compilats o interpretats** com en el cas de **Python**. No cal compilar (transformar el llenguatge dels programes informàtics a un d'equivalent) quan es treballa amb Python, ja que els **intèrprets** que s'utilitzen amb aquest llenguatge s'**encarreguen d'executar aquests programes mitjançant scripts propis**.

### Àmpliament recolzat:

Les seves característiques i les seves funcionalitats fan que aquest llenguatge sigui molt interessant. Per això, **Python ha generat una comunitat d'usuaris molt gran** al seu voltant que pot ser útil quan volem trobar informació o demanar ajuda per desenvolupar qualsevol tipus de programa o algorisme.


## Utilització de Python.
---

Un dels IDE més utilitzats per a Python sol ser **PyCharm**, o també **PyDev**. Python es el llenguatge més versatil del mercat. Per això, funciona en pràcticament casi **tots els àmbits**.

Python serveix per a fer:

1. Aprenentatge automàtic **(Machine Learning)**
2. Intel·ligència Artificial **(IA)**
3. Big data i Anàlisi de dades
4. Operacions matemàtiques
5. Visualització de dades
6. Programació **d'apps**
7. Desenvolupament **web**
8. Desenvolupament de **videojocs**
9. Gestió financera


## Avantatges i desavantatges.
---

### Avantatge

**1. Biblioteques i Frameworks**

Com ja he comentat abans, Python, en ser de codi lliure i gratuït, permet que una gran comunitat darrere pugui **contribuir al desenvolupament de codi i frameworks** que ajuden altres programadors a crear projectes


**2. Llenguatge senzill i de gran potencial**

Molta gent califica **Python** com un dels llenguatges més **facils d'apendre**, ja que aquest llenguatge substitueix els famosos **"corxets" { }** per identació amb tabulaciuons. D'aquesta manera Python es un llenguatge molt més **llegible** per algù que no esta familiaritzat del tot amb la programació.

**3. Multiplataforma**

**Python** és un d'aquests llenguatges de programació que es pot executar en qualsevol sistema operatiu en què s'operi. Així és: no importa si es tracta de Windows, Linux, macOS, i d'altres

### Desavantatges

**1. No tot és perfecte.**

El fet que sigui un llenguatge versàtil, no vol dir que sigui eficient en tots els camps en què es pot executar. En el cas del desenvolupament d'aplicacions mòbils, **Python no és la millor opció**, ja que hi ha altres llenguatges més especialitzats i que ofereixen millors resultats.

**2. Processament lent**

Degut a la seva gran versatilitat, Python pot arribar a processar avegades de forma lenta, ja que no té definit un ús específic i compilat

**3. Hosting**

En general, no tots els serveis de hosting estan preparats per suportar els programes de Python.

 ## Exemple de codi.
 Com podem veure el codi es molt mes sencill que en l'exemple anterior de Java, ja que només es 1 línea de codi. 
 
   ``` 
   print("Hola mòn!") 
   ```
    
  **Output:**
  *Hola mòn!*
  
  
  Demanar el nom a l'usuari i mostrar-lo en Python
  ---
  ```
 nom = input("Com et dius?: ")
  print("Hola", name + "!")
  ```
  **Input:** Eric   
  **Output:** *Hola, Eric*



## Infojobs i Python.

Hi han **588 ofertas de Python en tota Espanya**. Comparat amb altres, hi ha **818** ofertes per a **Java**, **242** per a **C++**, i **708** per a **C#**.       
Un salari considerat **"baix"** per a un **Python Developer son 21.000 a l'any.**     
Un salari considerat **"mitjà"** per a un **Python Developer son 32.200 a l'any.**      
Un salari considerat **"alt"** per a un **Python Developer son +49.000 a l'any.**      

Informació extreta de Glassdoor --> https://www.glassdoor.es/Sueldos/python-developer-sueldo-SRCH_KO0,16.htm

## Conclusió:
---

**Python** es el llenguatge de programació **mes popular d'aquest any**, i segurament ho sigui per els propers anys.   
Python es pot utiltizar en **tots els camps** de la programació, encara que hi ha diversos casos en els que **no es la millor opció**, com he dit abans en l'exemple de les aplicacions mòbils. El camp en el que més destaca es IA **(Inteligencia Artificial)** i el **Machine Learning**. El fet de que sigui un dels llenguatges més **fàcils** d'apendre el fa molt atractiu per a que gent nova començi a programar **desde 0**.  

## Webgrafia  
---

https://es.wikipedia.org/wiki/Python  
https://www.glassdoor.es/Sueldos/python-developer-sueldo-SRCH_KO0,16.htm  
https://www.infojobs.net      
https://ca.wikipedia.org/wiki/Programaci%C3%B3_orientada_a_objectes     
https://en.wikipedia.org/wiki/Object_(computer_science)     
  

# C#
## Què és C#?
---

**C#** és un llenguatge de programació **compilat**, desenvolupat i estandarditzat per l'empresa **Microsoft l'any 2000** com a part de la seva plataforma **.NET**. La idea principal de **C#** la va tindre **Anders Hejlsberg**, que, juntament amb el seu equip, van desenvolupar aquest llenguatge de programció.

La sintaxi bàsica deriva de **C/C++** i utilitza el model d'objectes de la plataforma **.NET**, similar al de **Java**, encara que inclou millores derivades d'altres llenguatges.

<p align="center">
  <img src="https://user-images.githubusercontent.com/113585897/192094639-b756bc3b-1774-4f3d-b778-602648b148c6.png") />
</p>


## Característiques de C#.
---


**Orientació a components.**

L'objectiu de la programació **orientada a components (POC)** és construir un **mercat global** de components programari, on els usuaris són els desenvolupadors de les aplicacions que necessiten reutilitzar components ja fets i testejats per construir les **seves aplicacions** de manera més **ràpida i robusta**.



**Integració amb altres llenguatges.**  

Qualsevol llenguatge que es compile amb .NET, com la nova versió de visual basic, pot aprofitar-se per fer servir en el teu projecte.



**Unity i C#.**

**Unity** es una de les plataformes més famoses en tot el mòn si parlem sobre la **creació de videojocs**, i perquè el menciono aqui?   
Doncs perquè Unity funciona amb **C#** i pots **programar jocs amb aquest llenguatge** si utilitzes **Unity**.  



<p align="center">
  <img src="https://user-images.githubusercontent.com/113585897/192718067-0a9e0e3c-d9c8-4852-a769-607d1cd40573.png") />
</p>

**Multifil**.   

En **C#** es possible dividir el codi en múltiples fils d'execució, treballar en paral·lel i sincronitzar-los al final.

## Utilització de C#.
---

El **IDE** més utilitzat per **C#** es, sense cap mena de dubte, **Visual Studio (Microsoft Visual Studio)**. Això es deu a que C# es un llenguatge fet per **Microsoft**, per tant, han fet també un IDE que **s'adapta perfectament** als seus llenguatges de programació. **C# ocupa el lloc número 5** en la llista **TIOBE**.

C# serveix per a fer:

1. Aplicacions de **mòbil**
2. **Videojocs**
3. Aplicacions **d'escritori**

## Avantatges i desavantatges.
---

### Avantatge

  **1. Programació orientada a objectes**   
  
  Des del principi, C# es va basar en els principis de programació orientada a objectes (OOP). Aquest concepte permet definir el tipus i l'estructura de les dades, per aplicar-hi el conjunt de funcions estàndard   


**2. Documentació**     

  Microsoft ofereix una àmplia documentació per a **C# i .NET**, que inclou tutorials interactius, sèries de vídeos i explicacions de problemes.    
 
 **3. Llenguatge per evitar errors**    

  C# és segur de tipus, cosa que significa que una variable **no pot canviar el seu tipus en tot el codi**. Per exemple, si heu declarat una variable GoodDay com a **enter**, només podeu assignar-li valors numèrics exactes i els valors de cadena com dissabte o diumenge són **inacceptables**.    
  
  
### Desavantatges

  **1.El rendiment de C# no és el millor**    

  El rendiment d'un llenguatge es pot mesurar en termes de temps de compilació i el rendiment real de l'aplicació. En comparació amb el seu llenguatge més proper, **Java**, C# té un **temps de compilació similar**.
  
  **2. Dependència de la plataforma .NET**
  
  Com he dit abans, **C# depèn en gran mesura dels recursos .NET** per executar-se en diferents sistemes operatius o plataformes. Tanmateix, per si sol **no és tan flexible**, si no esteu considerant .NET com la vostra pila de **tecnologia principal**.
  
   **3. Corba d'aprenentatge dura**
   
   Tot i que C# no és el llenguatge més fàcil d'aprendre per si sol, l'ús de biblioteques .NET afegeix una altra capa de complexitat. Les biblioteques a .NET s'actualitzen sovint i hi ha milers de recursos que necessites per aprendre
   
## Exemple de codi.

```
namespace HolaMon
{
    class Hola {         
        static void Main(string[] args)
        {
            System.Console.WriteLine("Hola Mon!");
        }
    }
}
```

**Output:** *Hola Mon*

 Demanar el nom a l'usuari i mostrar-lo en C#
  ---
  
  ```
 using System;

class MainClass {
  public static void Main (string[] args) {
    string nom = Console.ReadLine();
    Console.WriteLine("Hola {0}", name); 
   }
} 
```
  **Input:** Eric   
  **Output:** *Hola, Eric*

## Infojobs i C#.

Hi han **708 ofertas de C# en tota Espanya**. Comparat amb altres, hi ha **588** ofertes per a **Python**, **242** per a **C++**, i **818** per a **Java**.       
Un salari considerat **"baix"** per a un **C# Developer son 23.000 a l'any.**     
Un salari considerat **"mitjà"** per a un **C# Developer son 32.000 a l'any.**      
Un salari considerat **"alt"** per a un **C# Developer son +50.000 a l'any.**      

Informació extreta de "GlassDoor" --> https://www.glassdoor.es/Sueldos/programador-c-sueldo-SRCH_KO0,13.htm


## Conclusió:
---

**C# ocupa el lloc número 5** en la llista **TIOBE**. Moltes persones consideren a **C#** com un llenguatge que només serveix per fer **videojocs**. Però la realitat es que també s'utilitza per fer aplicacions de **mòbil** i d'escritori. **C#** gira en voltant de **.NET** i les seves propietats, això fa que **no** sigui un llenguatge tan **flexible** si el comparem amb els demés.


## Webgrafia  
---
 
https://es.wikipedia.org/wiki/C_Sharp
https://www.infojobs.net      
https://ca.wikipedia.org/wiki/Programaci%C3%B3_orientada_a_objectes     
https://en.wikipedia.org/wiki/Object_(computer_science)     
  
# SQL
## Què és SQL?
---

Les sigles de SQL venen de l'angles, **Structured Query Language**; en català **(llenguatge de consulta estructurada**) és un llenguatge fet per administrar, i recuperar informació de sistemes de **gestió de bases de dades relacionals**. Va ser creat l'any **1974** per 	**Donald D. Chamberlin** i **Raymond F. Boyce**, dins de l'empresa **IBM**.   

**SQL** es el número **9** en la llista **TIOBE**, per la seva contrapart, **PL/SQL**, ocupa el lloc número **31**. 

La **sintaxi SQL** es basa en la sintaxi de **l'idioma anglès** i utilitza molts dels mateixos elements que la sintaxi del **Visual Basic**.  

**Exemple:**
*WHERE First_Name = 'Maria';*   

**Nota:** SQL no es fa servir només per manipular dades, sinó també per **crear i modificar el disseny d'objectes** de base de dades, com ara **taules**.  

<p align="center">
  <img src="https://user-images.githubusercontent.com/113585897/192598882-59ad3736-4dab-46f5-b7d4-38888f90a6e0.png") />
</p>



## Utilització de SQL.
---
**SQL** és un llenguatges de programació que els desenvolupadors utilitzen per **definir i accedir** a les bases de dades, que són col·leccions de dades organitzades als quals els usuaris hi poden accedir electrònicament. Aquests llenguatges permeten als usuaris realitzar tasques com **controlar l'accés a les dades**, **definir** i **actualitzar les dades** i **cercar informació** dins del sistema de gestió de bases de dades.

**SQL** s'utilitza en MySQL, MariaDB, SQLite, PostgreSQL, Microsoft SQL Server i Oracle

## Característiques de SQL.
---

**Llenguatge de definició de dades:** L'SQL proporciona ordres per a la definició d'esquemes de relació, esborrament de relacions i modificacions dels esquemes de relació. 
**Control de transaccions:** SQL té ordres per especificar el començament i el final d'una transacció.  

**SQL incorporat i dinàmic**: Això vol dir que es poden incorporar **instruccions de SQL** en llenguatges de programació com ara **C++, C, Java, PHP, COBOL, Pascal i Fortran.**

**Autorització**: El LDD inclou ordres per especificar els drets d'accés a les relacions ia les vistes.

**Flexibilitat**: Una de les raons per les que SQL és un llenguatge tan utilitzat per la seva flexibilitat, la seva versatilitat a l'hora d'implantar solucions i per permetre definir diferents formes de veure les dades.

## Exemple de codi.
Com que és un llenguatge per a base de dades, fer un **"Hello World"** no siría molt pràctic, per tant, ensenyarem altre tipos d'exemples.

**SELECT:** La instrucció SELECT s'utilitza per seleccionar diferents dades que conté una base de dades, A continuació mostrem un exemple:  
```
SELECT Nom, Cognom, ... 
DE Datos_Clients;   
```
**SELECT DISTINCT:** Per seleccionar els diferents valors d'una taula per afegir la instrucció: 
```
SELECT DISTINCT Nom, Cognom, ...  
DE Datos_Clients; 
```
**WHERE:** La instrucció WHERE és utilitzada per establir condicions i filtres a la query.  
```
SELECT columna1, ...  
FROM nom_taula  
WHERE condicio; 
```

## Infojobs i SQL#.

Hi han **1300 ofertes relacionades amb la paraula "SQL" en tota Espanya**. Comparat amb altres, hi ha **588** ofertes per a **Python**, **242** per a **C++**, i **818** per a **Java**.  

És difícil de calcular el salari d'un programador SQL, ja que aquests **fan diverses tasques i compaginen els coneixements de SQL amb altres llenguatges de programació**.  

Un salari considerat **"mitjà"** per a un **SQL Developer son entre 25.000 i 30.000 a l'any.**      


## Conclusió:
---

**SQL** és un dels llenguatges de programació més famosos per controlar bases de dades, gestionarles i administrar-les. Aquest llenguatge s'utilitza desde fa casi **50 anys**; encara que sigui un llenguatge de programació especialitzat només en base de dades ha conseguit accedir al **rànquing 9** en la llista Tiobe, competint amb altres llenguatges compilats i interpretats.


## Webgrafia  
---

https://www.infojobs.net    
https://bigdata-analytics.es/sql/ 
https://www.tiobe.com/tiobe-index/sql/  
https://es.wikipedia.org/wiki/Sistema_de_gesti%C3%B3n_de_bases_de_datos_relacionales  
