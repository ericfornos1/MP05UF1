# **Activitat 2 - Pràctica amb llenguatges.**

PER PARELLES:
Ara que ja coneixeu uns quants llenguatges de programació el que farem serà
crear un programa d’exemple.  

El programa simplement ha de generar un número aleatori de l’1 al 6 i
s’anomenarà “d6”, simula el llançament d’un dau de 6 cares. 
Heu de crear al repositori de GitHub MP05UF1 un fitxer de text nou anomenat
UF1Activitat2.md que confingui la següent informació: 

Escolliu 3 llenguatges de programació, un de compilat, un d’interpretat i un de MV. 

---
**Per al llenguatge compilat:**

● Utilitzant la línia de comandes, sense utilitzar un IDE de desenvolupament  
escriureu el programa en un fitxer de text que sigui el codi font, el codi font 
l’adjunteu dins el document.    

Abans de res, hem de **instal·lar** el següent paquet, per a poder utilitzar el comando **"gcc"**, que es el que ens permetrà transformar un arxiu en extensió **".c"** a executable mitjançant el comando **./(nom_de_l'arxiu)** a **Ubuntu**. 

  ![image](https://user-images.githubusercontent.com/113585897/194006531-4a53f241-13ff-487b-a149-15e41f7b7168.png)      



El programa simplement genera un número aleatori de **l’1 al 6** i, simula el llançament d’un **dau de 6 cares**
```
#include <stdio.h>
#include <stdlib.h>

int main()

{
    int randomnumber;
    srand(time(NULL));
    randomnumber = rand() % 6;
    printf("%d\n", randomnumber);
    return 0;
}
```

  ![image](https://user-images.githubusercontent.com/113585897/194005594-2839c610-5947-4af5-83f7-fe6fd06b823e.png)  

La comanda **gcc dado.c -o prova2.c** serveix per transformar l'arxiu a executable. D'aquesta manera podrem utilitzar el **./(nom_de_l'arxiu)** i executar-lo 

  ![image](https://user-images.githubusercontent.com/113585897/194005507-4c9f0de7-c0cf-4f1a-ba04-8194e4348bf4.png)  

Si l'executem mes d'una vegada, podem veure que dona resultats diferents. 

  ![image](https://user-images.githubusercontent.com/113585897/194005840-380ab257-262e-4f06-baa3-c4e928946617.png)  

● Identifiqueu el compilador real que utilitzeu (nom de l’executable) i la
comanda per utilitzar-lo per passar de codi font a codi objecte.  

● Descriviu com passar de codi font a codi objecte. 

● Mostreu les extensions dels fitxers de codi font i codi objecte.  

● Descriviu com passar de codi objecte a executable.  

● Expliqueu els avantatges d’utilitzar un llenguatge compilat i els punts febles. 

● Busqueu 3 IDEs de desenvolupament pel llenguatge.   

---
**Per al llenguatge interpretat:**

● Utilitzant la línia de comandes, sense utilitzar un IDE de desenvolupament
escriureu el programa en un fitxer de text que sigui el codi font, el codi font
l’adjunteu dins el document.  

● Identifiqueu l'intèrpret del llenguatge (l’executable). 

● Descriviu com funciona l’intèrpret. 

● Mostreu les extensions dels fitxers de codi font. 

● Expliqueu els avantatges d’utilitzar un llenguatge interpretat i els punts febles.  

● Busqueu 3 IDEs de desenvolupament pel llenguatge. 

---
**Per al llenguatge de MV:**  

● Utilitzant la línia de comandes, sense utilitzar un IDE de desenvolupament  
escriureu el programa en un fitxer de text que sigui el codi font, el codi font 
l’adjunteu dins el document.  

● Identifiqueu el compilador real (nom d’executable) que utilitzeu i la comanda 
per utilitzar-lo per passar de codi font a ByteCode.  

● Descriviu com passar de codi font a ByteCode. 

● Mostreu les extensions dels fitxers de codi font i ByteCode.  

El fitxer predeterminat **C** es **".c"** 

![image](https://user-images.githubusercontent.com/113585897/194008617-101b499a-f6c0-437c-993e-3319c727e8ef.png)

● Descriviu com executar el programa. 

● Expliqueu els avantatges d’utilitzar un llenguatge de MV i els punts febles.  

● Busqueu 3 IDEs de desenvolupament pel llenguatge.   


