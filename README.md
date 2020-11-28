# Apunts

---

## Introducció


#### Tipus de Software

- **De sistema**
    - *Es el software mes base, s'utilitza per poder interaccionar amb la maquina i fer que funcioni en general* 
    - Sistema Operatiu
    - Drivers
- **De aplicació**
    - *Es el software que s'utilitza per fer cualsevol cosa que no sigui "crear" ni sigui funcionament basic del sistema o els seus dispositius*
    - Suite ofimatica
    - Navegador
    - Edició d'imatge
- **De desenvolupament**
    - *Es el software utilitzat per crear una cosa completament diferent* 
    - Editors
    - Compiladors
    - Interpretes

#### Relació Hardware-Software
+ **Disc Dur**
    + Guarda permanentment executables i fitxers de dades
+ **RAM**
    + Guarda temporalment el codi binari dels executables i els fitxers de dades necessaris
+ **CPU**
    + Llegeix i executa instruccions guardades en la memoria **RAM**
+ **E/S**
    + Agafa *input* del usuari i li torna *outputs*

#### Codi font, objecte i executalbe

* **Codi Font**
    * Fitxer de text escrit en un llenguatge de programació
* **Codi Objecte**
    * Fitxer binari no executable
* **Codi executable**
    * Fitxer binari executable

---

## Cicle de vida del Software
Ingenieria de software
: Disciplina que estudia els principis i metodologies per el desenvolupament i manteniment de sistemes softwere

Hi ha gent que sugereix que el terme "*Desenvolupament de software*" es mes apropiat ja que no implica els nivells de 
prova exhaustiva que implica "*Ingenieria de software*"


#### Desenvolupament de Software
+ #### Fases Principals
    + **Analisi**
        + *Es determina i defineix clarament les necesitats del client i s'especifica els requisits que tenen que cumplir el software a desenvolupar*
        + La especificacio ha de ser:
            + Ha de evitar detalls de diseny o implementaci   
            + El client ha de ser capaç d'entendre-ho
            + Concís
            + Separar requisits funcionals i no funcionals
            + Dividiir i jerarquitzar el model
            + Posar criteris de validació
    + **Diseny**
        + *S'organitza el sistema d'elements  que poden ser desenvolupats per separats*
        + *S'especifica la realcio i funcionalitat de tots els elements*
        + Les activitats habituals son:
            + Diseny arquitectonic
            + Diseny detallat
            + Diseny de dades
            + Diseny de interfaç
    + **Codificació**
        + *S'escriu el codi font de cada component*
        + Es poden utilitzar llenguatges de programació o llenguatges informatics d'un altre tipus
    + **Proves**
        + *L'objectiu de les proves es conseguir que el programa funcioni incorrectement per aixi arreglar-ho* 
    + **Manteniment**
        + *Una vegada estigui en utilització tindrem que repetir diverses tasques anteriors per realitzar canvis quan sigui necessari*
        + Tipus de manteniment:
            + Correctiiu: Corretgeix defectes 
            + Perfectiu: Milora la funcionalitat
            + Evolutiu: Afegeix funcionalitats noves
            + Adaptatiu: S'adapta a nous entorns
#### Models de desenvolupament de software

+ #### Models clásics(*Predictius*)
    + **Model en cascada**
        + Les fases es fan en ordre, fins que no acabes una no es fa la seguent, una vegada a la seguent no tornes enrrere
        + De menys a mes detall
        + Rigid
        + Anticuat
    + **Model en V**
        + Les fases es fan en ordre, fins que no acabes una no es fa la seguent, una vegada a la seguent no tornes enrrere 
        + Fases jerarquiques amb els nivells superiors indicant major abstracció
        + Rigid
        + Anticuat
+ **Model de contstrucció de prototips**
    + Raóns per protptipar
        + Manca d'experiencia previa
        + Falta de concrecó del client
    + Proces
        + Es creat a la fase de análisi
        + Es presentat al client per refinar inperfeccións
        + Repetir
    + Tipus
        + Rapids
            + D'un sol us
            + Normalment en un llenguatge o eina diferent al final
        + Evolutius
            + En el mateix llenguatge que el producte final
            + S'utilitza com a base per el projecte
+ **Models evolutius o incrementals**
    + Model en espiral (*Iteratius*)
        + Es pasa per els mateixos pasos de desenvolupament de software reiteradament fins tenir el producte desitjat 
    + Metodologíes agils (*Adaptatius*)
        + Basat en el desenvolupament iteratiu e incremental
        + Metodologíes mes conegudes
            + Kanban
                + Tambe anomenat "Sistema de targetas"
                + Enfocat a treure el valor maxim pels clients utilitzant el minim de recursos
            + Scrum
                + Iteracións cada 2, 3 o 4 setmanes
                + Al inici de cada iteració es posen objectius prioritaris
                + Al final de cada iteració s'obte una entrega parcial utilizable pel client
                + Reunions diaries per tractar el ritme de les iteracións (*sprint*)
            + XP(eXtreme Programming)
                + Diseny simple
                + Millores petites
                + Probes
                + Integració continua
                + Programació per parelles
                + El client es par del equip de desenvolupament
                + 40 hores seemanals

---

#### Llenguatges de Programació

+ ##### Tipus de llenguatges
    + **Segons obtenció del codi executable**
        + Compilats
            + Caracteristiques 
                + Mes eficients
                + Mes lents en el process de desenvolupament
            + Agafa el codi complet i el pasa a binari 
                + Exemples
                    + C
                    + C++
        + Interpretats
            + Caracteristiques
                + Menys eficients
                + Mes rapids en el process de desenvolupament
            + Interpreta seccions de codi independentment se les altres 
            + Exemples
                + PHP
                + Javascript
    + **Segons forma que operen**
        + Declaratius
            + *Li demanes un output al programa i es ell que s'encarregua de buscar i utilitzar el metode correcte* 
            + Exemples
                + Prolog
                + Lisp
                + Haskell
                + SQL
            + Normalment son interpretats
        + Imperatius
            + *Li dius al programa quins pasos seguir per conseguir el resultat que vols*
            + Exemples
                + C
                + Java
                + C++
                + Javascript
            + Molts son compilats
    + **Segons nivell**
        + Com mes aprop estan de la interacció amb la maquina mes baix nivell son
        + Baix nivell
            + Ensamblador    
        + Mig nivell
            + C
        + Alt nivell
            + Java





 



