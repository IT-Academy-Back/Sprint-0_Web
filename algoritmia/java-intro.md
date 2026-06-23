# Introducció a Java per a alumnes que venen de Python

## Objectiu

Ja has treballat conceptes bàsics de programació amb Python i JavaScript: variables, condicionals, bucles, llistes i funcions.

Ara començarem a treballar amb Java. L'objectiu no és memoritzar tota la sintaxi, sinó entendre què canvia respecte a Python i aprendre a buscar a la documentació allò que necessites per resoldre exercicis.

---

## Què és Java?

Java és un llenguatge de programació molt utilitzat en aplicacions d'empresa, aplicacions web, serveis backend, aplicacions Android i sistemes grans.

Java és un llenguatge fortament tipat i orientat a objectes. Això vol dir que el codi s'acostuma a organitzar en classes i objectes, que representen conceptes del problema que volem resoldre.

Per exemple, en una aplicació podríem tenir classes com `User`, `Product`, `Order` o `Student`.

En aquesta introducció encara no entrarem a fons en programació orientada a objectes. De moment només cal entendre que en Java gairebé tot el codi viu dins d'una classe, fins i tot els primers exercicis senzills.

A diferència de Python, Java és un llenguatge més estricte:

- cal indicar el tipus de les variables,
- el codi s'organitza dins de classes,
- les classes tenen un paper central,
- les instruccions acaben amb `;`,
- els blocs de codi es marquen amb `{}`,
- abans d'executar el programa, el codi es compila.

Això pot semblar més incòmode al principi, però ajuda a detectar errors abans d'executar el programa i és molt habitual en projectes professionals.

---

## Primer programa

Aquest és un programa mínim en Java:

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hola, món");
    }
}
```

Idees importants:

- Si la classe es diu `Main`, el fitxer normalment s'ha d'anomenar `Main.java`.
- `main` és el punt d'entrada del programa.
- `System.out.println()` serveix per mostrar informació per pantalla.
- Les claus `{}` indiquen on comença i acaba un bloc.
- El `;` marca el final de moltes instruccions.

De moment no cal entendre cada paraula de `public static void main(String[] args)`. Només cal reconèixer aquesta estructura i saber on escriure el teu codi.

---

## Diferències ràpides amb Python

| Python | Java |
| ------ | ---- |
| `print("Hola")` | `System.out.println("Hola");` |
| `age = 20` | `int age = 20;` |
| `name = "Anna"` | `String name = "Anna";` |
| `if age >= 18:` | `if (age >= 18) { ... }` |
| `elif` | `else if` |
| La indentació defineix blocs | Les claus `{}` defineixen blocs |
| Pots escriure scripts simples directament | El codi normalment s'organitza dins de classes |
| Llistes | Arrays o `ArrayList` |
| `def` o `function` | Mètodes dins d'una classe |

---

## Què has de saber buscar a la documentació?

Per fer els primers exercicis, hauràs de buscar com es fan aquestes coses en Java:

### Variables i tipus

Preguntes guia:

- Com declaro un número enter?
- Com declaro un número decimal?
- Com declaro un text?
- Com declaro un booleà?

Paraules clau per buscar:

- `int`
- `double`
- `String`
- `boolean`

### Condicionals

Preguntes guia:

- Com s'escriu un `if` en Java?
- Com s'escriu un `else`?
- Com s'escriu un `else if`?
- Quina diferència hi ha entre `=` i `==`?

### Bucles

Preguntes guia:

- Com faig un bucle `while`?
- Com faig un bucle `for`?
- Com puc repetir una acció 10 vegades?
- Com puc recórrer una llista?

### Arrays i ArrayList

Preguntes guia:

- Quina diferència hi ha entre un array i un `ArrayList`?
- Com creo un `ArrayList`?
- Com afegeixo elements?
- Com llegeixo un element?
- Com sé quants elements té?

Pista important:

```java
import java.util.ArrayList;
```

Si fas servir `ArrayList`, hauràs d'importar-lo.

### Funcions i mètodes

En Python has fet servir `def` per definir funcions:

```py
def saludar(nom):
    print("Hola", nom)
```

En JavaScript has vist `function` o funcions semblants:

```js
function saludar(nom) {
    console.log("Hola " + nom);
}
```

En Java normalment parlem de **mètodes**, perquè el codi viu dins d'una classe.

```java
void saludar(String nom) {
    System.out.println("Hola " + nom);
}
```

Exemple amb retorn:

```java
int sumar(int a, int b) {
    return a + b;
}
```

Comparació ràpida:

| Python | JavaScript | Java |
| ------ | ---------- | ---- |
| `def saludar(nom):` | `function saludar(nom) {}` | `void saludar(String nom) {}` |
| `return a + b` | `return a + b;` | `return a + b;` |

Preguntes guia:

- Com creo un mètode que retorna un número?
- Com creo un mètode que no retorna res?
- On escric els mètodes dins d'una classe?
- Quin tipus retorna el mètode?
- Quins paràmetres rep?

### Comparar textos

En Java, per comparar textos (`String`), no farem servir `==`.

Busca com funciona:

```java
.equals()
```

---

## Errors típics venint de Python

- Oblidar el `;`.
- Oblidar indicar el tipus d'una variable.
- Escriure `elif` en lloc de `else if`.
- Fer servir `print()` en lloc de `System.out.println()`.
- Oblidar les claus `{}`.
- Comparar textos amb `==` en lloc de `.equals()`.
- Fer servir `ArrayList` sense importar-lo.
- Pensar que la indentació defineix els blocs. En Java ajuda a llegir, però els blocs reals els marquen les claus.

---

## Documentació recomanada

- [Java Data Types](https://www.w3schools.com/java/java_data_types.asp)
- [Java Conditions](https://www.w3schools.com/java/java_conditions.asp)
- [Java For Loop](https://www.w3schools.com/java/java_for_loop.asp)
- [Java While Loop](https://www.w3schools.com/java/java_while_loop.asp)
- [Java ArrayList](https://www.w3schools.com/java/java_arraylist.asp)
- [Java Classes](https://www.w3schools.com/java/java_classes.asp)
