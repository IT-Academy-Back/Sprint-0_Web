# Repte final · Tic-Tac-Toe

En aquest mòdul connectarem el que has treballat durant el sprint: el frontend, els llenguatges backend que has practicat durant els exercicis d'algoritmia, i els conceptes de comunicació client-servidor que has vist al bloc de fonaments de la web.

Et proposem dos reptes:

**[Tic-Tac-Toe — Java](./repte-java/tic-tac-toe-backend.md)**

Implementar la lògica pendent d'un backend Spring Boot com: validar jugades, detectar guanyador i empat, entre d'altres.

**[Tic-Tac-Toe — PHP](./repte-php/tic-tac-toe-backend.md)**

Llegir i entendre el codi d'un backend PHP: detectar per què el joc no acaba, corregir un bug i proposar millores.

## Punt de control

Aquest punt de control és una conversa breu amb el mentor/a per revisar el que has fet i assegurar que entens el funcionament del projecte. No es tracta només d'ensenyar que el joc funciona, sinó de poder explicar com el frontend i el backend treballen junts.

Abans de fer el punt de control, comprova que pots:

- Executar el projecte.
- Explicar la separació entre frontend i backend.
- Explicar què passa quan el frontend fa una request al backend.
- Identificar on viu la lògica del joc.
- Explicar com es representa el tauler.
- Interpretar els valors `0`, `1` i `2` del tauler.
- Explicar com es valida una jugada.
- Explicar com es detecta un guanyador o un empat.
- Provar el joc des del navegador.
- Mirar una petició amb DevTools o explicar què retorna la response JSON.

### Java

En el repte Java, hauràs de poder explicar:

- On és `GameService.java`.
- Quines parts del projecte no havies de modificar: frontend, controller, models o endpoints.
- Què fa `playMove(...)`.
- Què fa `isValidMove(...)`.
- Què fa `hasWinner(...)`.
- Què fa `isDraw()`.
- Com has comprovat que el joc detecta jugades fora del tauler, caselles ocupades, victòries i empats.

### PHP

En el repte PHP, hauràs de poder explicar:

- Què hi ha a `public/` i què hi ha a `src/`.
- Quin codi pertany al client i quin al backend.
- Per què el joc no acaba correctament.
- Per què la CPU continua jugant després d'una jugada guanyadora.
- On es podrien canviar els símbols `X` i `O`.
- Una millora que faries al codi o un dubte concret que t'hagi sorgit.

### Què has d'ensenyar

Quan facis el punt de control, prepara:

- El joc funcionant.
- El codi modificat.
- Una explicació breu del flux frontend → backend → frontend.
- Una response JSON o una petició vista amb DevTools.
