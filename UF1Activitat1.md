# Treball d'entorns
**Java, Python, C#, SQL**

Activitat de recerca de llenguatges de programació      

D'aquests llenguatges heu de comentar obligatòriament els següents aspectes:               
• Naixement, creadors i evolució històrica.                    
• Característiques del llenguatge.               
• Imperatiu, declaratiu, OOP...               
• Compilat, interpretat, híbrid...               
• Principals novetats o aportacions respecte altres llenguatges.               

•Avantatges i inconvenients respecte altres llenguatges.               
•Principals entorns on es fa servir el llenguatge.                        

• Exemple de codi (valoraré especialment si mostreu que ho heu implementat i
provat)
• Hola mòn (Molt fàcil de trobar)               
• Demanar el nom a l'usuari i mostrar-lo (haureu de buscar una mica més)               
• Buscar com estan les ofertes de treball a Infojobs del llenguatge.               
• WebGrafia               

# Java
## Què és Java?
---
Java es el **tercer llenguatge de programació més popular del mòn** segons la famosa llista **TIOBE**, va ser disenyada i creada l'any 1996 per "James Gosling" de Sun Microsystems (Oracle Corporation). La seva sinatxis es deriva en una gran part de C i C++. 

Les aplicacions fetes en Java son compilades a **bytecde**, que pot ser executada en qualsevol JVM (màquina virtual de Java).
<p align="center">
  <img src="java1.svg" />
</p>

## Característiques de Java.
---
La característica més important de Java es el **"OOP"** es a dir, (Programació Orientada a Objectes). Els llenguatges de programació que tenen aquesta característica tenen en comú que utilitzen les entitats **"objectes"**, es a dir, una combinació de variables, funcions i dades.

Una altra característica que fa a Java un llenguatge de programació molt respetable es el seu lema, **"write once, run anywhere"**, amb el significat de que Java es capaç de escriure un programa una vegada i que es pugui executarse desde qualsevol dispositiu, independement del hardware.

Java compila el codi fodi per a generar el codi **"bytecode"**, del que hem parlat abans. Aquest llenguatge **"bytecode"** son instruccions de màquina simplificades. Aquest codi no es codi font, però tampoc es codi màquina, es un llenguatge que només Java el pot entendre, després, la **màquina virtual (JVM)** s'encarrega de interpretar i executar el codi.

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
       La curva d'aprenentatge de Java es **curta**, i la sintaxis es fàcil d'apendre, ademés, es pareix a C i C++.     
       
**3. Programació orientada a objectes**.                 
       Els conceptes **"OOP"** de Java ajuden a resoldre problemes del món real. També ajuda a mantenir el codi gran dividint-los en fragments amb nom més petits. 
       
**4. Java es d'alt nivell.**                
        Los llenguatges de baix sòn més dificils d'entendre, els de alt nivell tenen moltes paraules de **l'anglès**, lo qual el fa més fàcil d'apendre i de llegir.      
### Desavantatges

**1. Baix rendiment**                 
      Java consumeix més memòria en comparació amb els llenguatges de programació natius com **C i C++**. També és més lent en comparació amb ells, això es deu al             treball adicional de l'**intèrpret** per convertir el codi en llenguatge **màquina**.      
      
**2. Memoria**              
      L'administració de **memòria** de Java no es molt bona comparada amb altres llenguatges de programació com per exemple **Python, o C++**.    
      
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
Un salari considerat **"baix" per a un **Java Developer son 19.900 a l'any.**     
Un salari considerat **"mitjà"** per a un **Java Developer son 31.200 a l'any.**      
Un salari considerat **"alt"** per a un **Java Developer son 75.000 a l'any.**      

Informació extreta de "jobted" --> https://www.jobted.es/salario/programador-java      

### Webgrafia.  
https://es.wikipedia.org/wiki/Java_(lenguaje_de_programaci%C3%B3n)    
https://www.jobted.es/salario/programador-java    
https://www.infojobs.net    
https://ca.wikipedia.org/wiki/Programaci%C3%B3_orientada_a_objectes   
https://en.wikipedia.org/wiki/Object_(computer_science)   
