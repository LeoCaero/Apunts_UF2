# Apunts_UF2

## Proves

### Objectius de les proves a realitzar
  - Per fer una bona prova, ens hem de fixar en 2 objectius:
    - Provar si el software no fa el que ha de fer.
    - Provar si el software fa el que no ha de fer.

### Estratègies de prova
  - **Caixa negra**:
    - Fa un estudi del sisema desde l'exterior.
    - Es treballa directament sobre l'interfaç.
    - NO es tenen en compte els detalls interns del funcionament del programa.
    - Es proporcionen entrades i s'estudïen les sortides.
    
  - **Caixa blanca**:
    - S'examina el codi font i la seva execució.
    - Es comprova la execució de cada unitat: funcions, classes, moduls...

### Tipus de proves
  - **Funcionals**: Fan una evaluació del cumpliment dels requisits previs.
  - **No funcionals**: Fan una evaluació dels aspectes addicionals, ara com, el rendiment, la seguretat...

## Framework

### Què és un Framework?
Framework és una estructura adaptable conformada per un conjunt d'elements que permeten executar projectes de diversa índole d'una forma més organitzada i eficient, especialment en l'àrea de la programació. (Espai de treball)

### Per a què serveix un framework?
Un framework serveix tant per escriure codi font com per desenvolupar tota una aplicació o programari. Permet emmagatzemar i organitzar recursos essencials per al desenvolupament com el codi font, els fitxers de configuració o les llibreries de l'aplicació.

### De què està compost un framework?
  - **Controlador**: És la part del framework que gestiona l'accés a l'aplicació. Inclou els programaris necessaris perquè l'aplicació funcioni, els scripts (arxius per a l'execució de múltiples tasques) i altres tipus d'arxius.
  - **Model**: És la part del framework que gestiona les operacions lògiques.
  - **Vista**: És la interfície, és a dir, la part gràfica o visible amb la qual interactua l'usuari.

## Integració

### Tipus d'integració
  - Continua
  - Ascendent
  - Descendent
  
### Servidors 
  - Jenkins
  - Bamboo
  - Travis CI
  ...

### Cobertura del codi
  - Indica el percentatge de la prova realitzada(execució)
  - Es aconsellable que el percentatge arribi al 100%
  - Possibilitat de realitzar les cobertures a diferents IDE's que es basin en java.

## Qualitat

### Control de qualitat
  - Aconseguir una mesura de calidad del producte/programa
  - Realització de proves


### Tipus de qualitat
  - QA(Quality Assurance): conjunt d'activitats per garantir la qualitat al processos.
  - QC(Quality Control): conjunt d'activitats per garantir la qualitat dels productes.
  
### Factors de qualitat
  - **Operació del producte** (estructurar del producte):
    - Correcció
    - Fiable
    - Codi eficient
    - Codi segur
    - Facilitat a l'hora de fer-ne ús

  - **Revisió del producte** ():
    - Que es pugui fer manteniment al producte
    - La flexibilitat del producte
    - Facilitat a l'hora de fer proves al producte
    
  - **Transició del producte** ()
    - Portabilitat del producte(USB..)
    - Codi reutilitzable
    - Operatiu de forma interna

