# Tic-Tac-Toe PHP

Projecte base per practicar lògica i comprensió de codi backend amb una aplicació de 3 en ratlla.

El repositori esta organitzat com un workspace amb dues parts separades:

- `public/`: Part de client amb la que l'usuari/a interactua.
- `src/`: lògica backend de l'aplicació amb la qual l'usuari/a no interactua directament.

## Requisits

- PHP 8.1 o superior.

## Executar l'aplicació

Descarrega't el codi font. Dins de la carpeta  i mitjançant terminal
de comandes, executa:

```bash
php -S localhost:8000 -t public
```
Si obres un explorador web i hi indiques la direcció localhost:8000, hauries de veure l'aplicació.

## Descripció de l'exercici

Tens entre mans un miniprojecte sobre el joc tic-tac-toe("3 en ratlla") La problemàtica
és la mateixa que en Java. Tenim un projecte inacabat. Per acabar, hauràs d'entendre el codi font que es dona i fer les modificacions necessàries per a finalitzar-lo.

Totes les modificacions que hauràs de fer són a fitxers de la carpeta "src" i estan
senyalitzades amb comentaris. Un cop entès el codi font et demanen que ens expliquis:

- El joc ara es produeix però, no acaba mai. I no ens mostra qui guanya. Quina modificació hauries de fer al codi font perquè això passi?

- El joc té un petit *bug*. Si el jugador/a fa una jugada guanyadora, la CPU encara continua movent. Com ho podem evitar això?

- Les fitxes se simbolitzen al tauler com a "X" o "O". I si ens venen de gust altres caràcters, com els podríem canviar?

- Finalment, sobre el codi font donat, se t'acut alguna millora o tens dubtes concrets?

**Nota** Aquest és, fonamentalment, un exercici d'entendre codi aliè. Per tant, naturalitza passar un temps considerable fent-ho, sense agobiar-te :)