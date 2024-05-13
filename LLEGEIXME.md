**PROPÒSIT:**
El propòsit d’aquest codi és l’elaboració d’una barrera virtual de restricció que té forma d'esfera.

Aquest codi és el concepte d’una barrera virtual que podria ser utilitzada en una cirurgia per tal de limitar una zona de treball del robot dins el cos d’un pacient i aquesta 
proporcionaria un nivell més de seguretat, ja que, protegiria els òrgans i teixits del voltant de qualsevol possible contacte que pogués causar danys. 

**REQUERIMENTS D'INSTAL·LACIÓ:**
Per tal de poder executar aquest codi, és primordial haver-se descarregat prèviament una màquina virtual amb el simulador fora de línia d’Universal Robots. 

Tenint aquest pas previ, es pot descarregar el codi en format .urp que pot ser obert a partir del simulador fora de línia del cobot UR3e d’Universal Robots.

    1. Descarregar el fitxer .urp del repositori.
    2. Col·locar el fitxer descarregat dins la carpeta de fitxers del cobot UR3e de la màquina virtual (**Programs UR3**).
    3. Obrir el programa **URSim UR3**. 
    4. Obrir el fitxer .urp de la carpeta.

En aquest repositori també es pot trobar el codi en format .txt que permet llegir el codi sense la necessitat de ser descarregat i obert amb el simulador fora de línia. 

**MANUAL D'USUARI:**
En aquest manual d'usuari s'indica una petita guia per activar el funcionament del codi.

    1. Assegurar la correcta configuració del TCP i el Payload de l'eina utilitzada.
    2. Modificar els valors de les variables de l'inici del robot per personalitzar la barrera virtual (Opcional).
    3. Col·locar l'eina del robot a l'interior de la zona de treball (interior de la barrera virtual) tot prement el botó de moviment lliure de la consola del robot.
    4. Activar l'execució del codi de la consola del robot.
    5. Moure manualment el braç robòtic dins el volum limitat i observar com la barrera virtual limita la sortida dels límits.
