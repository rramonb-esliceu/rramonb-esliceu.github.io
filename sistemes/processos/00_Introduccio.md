!["SO"](sistemes.png)
# Gestió de Processos en Sistemes Operatius
## INDEX
1. [Definició de procés](https://github.com/rramonb-esliceu/rramonb-esliceu/blob/master/sistemes/processos/01_Definicio_de_proces.md)
2. [Tasques fonamentals dels Sistemes Operatius](https://github.com/rramonb-esliceu/rramonb-esliceu/blob/master/sistemes/processos/02_Tasques_Fonamentals_dels_Sistemes_Operatius.md)
3. [Estats d'un procés](https://github.com/rramonb-esliceu/rramonb-esliceu/blob/master/sistemes/processos/03_Estats_d_un_Proces.md)
4. [Operacions amb processos](https://github.com/rramonb-esliceu/rramonb-esliceu/blob/master/sistemes/processos/04_Operacions_amb_Processos.md)
5. [Execució de processos](https://github.com/rramonb-esliceu/rramonb-esliceu/blob/master/sistemes/processos/05_Execucio_de_Processos.md)
6. [Planificaió de processos](https://github.com/rramonb-esliceu/rramonb-esliceu/blob/master/sistemes/processos/06_Planificacio_de_processos.md)
7. [Informació necessaria per a la Gestió del procés](https://github.com/rramonb-esliceu/rramonb-esliceu/blob/master/sistemes/processos/07_Informacio_Necessaria_per_a_la_Gestio_del_Proces.md)
8. [Conclusió](https://github.com/rramonb-esliceu/rramonb-esliceu/blob/master/sistemes/processos/08_Conclusio.md)
> - [Torna a l'inici](https://github.com/rramonb-esliceu/rramonb-esliceu/tree/master)
> - [Torna a sistemes](https://github.com/rramonb-esliceu/rramonb-esliceu/tree/master/sistemes)
## Introducció
La gestió de processos constitueix l'espina dorsal dels sistemes operatius, proporcionant un marc fonamental per a la supervisió i control eficient de les diverses tasques que s'executen en un sistema. Aquesta disciplina abasta una àmplia gamma d'operacions i funcionalitats que permeten al sistema operatiu organitzar i optimitzar l'execució dels processos.
### Definició de Procés
Un procés pot ser definit com un conjunt d'instruccions o tasques que s'executen dins del sistema operatiu. És important entendre que aquests processos poden requerir l'execució de diversos programes i que un mateix programa pot formar part de diferents processos. Aquesta interconnexió complexa entre programes i processos posa de manifest la necessitat d'una gestió diligent.
### Tasques Fonamentals dels Sistemes Operatius
1. **Gestió dels Processos (E/S):** Inclou operacions com la creació, destrucció, bloqueig i despertar d'un procés. Aquesta gestió és vital per a mantenir l'equilibri i l'eficiència en l'execució de múltiples tasques.
2. **Gestió de la Memòria:** Responsable de gestionar l'espai de memòria assignat a cada procés, utilitzant tècniques avançades com la paginació i la segmentació.
3. **Gestió del Sistema de Fitxers:** Controla l'accés i l'organització dels fitxers al sistema, assegurant la integritat i la disponibilitat de les dades.
4. **Interfície d'Usuari:** Proporciona una interfície intuïtiva i funcional per a la interacció entre l'usuari i el sistema operatiu.
### Estats d'un Procés
Els processos poden passar per diversos estats, des dels actius fins als inactius. El coneixement d'aquests estats és crucial per a una gestió eficient:
- **Estats Actius:** Inclouen els estats d'execució, preparat i bloquejat.
- **Estats Inactius:** Inclouen els estats de suspès bloquejat i suspès preparat.
### Operacions amb Processos
1. **Crear un Procés:** Implica la creació d'un nou procés en el sistema, que requereix assignació de recursos i configuració inicial.
2. **Destruir un Procés:** Involucra la finalització i eliminació d'un procés existent, alliberant els recursos associats.
### Execució de Processos
L'execució d'un procés implica la càrrega del mateix a la memòria RAM i l'ocupació del processador per a la seva execució. El temps d'execució abasta el temps d'espera i el temps dedicat a la CPU.
### Planificació de Processos
Amb diversos processos en execució, el sistema operatiu ha de prendre decisions sobre quin procés s'executa en cada moment. Aquesta tasca és duta a terme pel planificador, que utilitza algorismes com FIFO, Round Robin, SJF, SRT i prioritats per a optimitzar la gestió.
### Informació Necessària per a la Gestió del Procés
- **PID (Identificador del Procés):** Identifica de manera única cada procés en el sistema.
- **Estat del Procés:** Indica l'estat actual del procés (preparat, en execució, en espera, etc.).
- **PC (Comptador de Programa):** Manté el registre de l'adreça de la següent instrucció a executar.
- **Registres de la UCP:** Contenen els valors dels registres de la unitat central de processament necessaris per a l'execució del procés.
- **Estadístiques:** Recopilen informació sobre l'ús del procés (temps d'execució, temps d'espera, etc.).
- **Informació de Planificació:** Conté dades rellevants per a la planificació del procés.
En resum, la gestió de processos en un sistema operatiu és essencial per a garantir un funcionament eficient i equitatiu. Aquesta àmplia gamma d'operacions i funcions contribueix al bon rendiment i a la coordinació efectiva dels processos en l'entorn operatiu.