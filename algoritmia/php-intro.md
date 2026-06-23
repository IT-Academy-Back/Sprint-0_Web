# Introducció a PHP per a alumnes que venen de Python

## Objectiu

En aquesta secció no treballarem encara les funcionalitats de PHP amb detall sino que traslladarem els coneixements que heu adquirit a fonaments al llenguatge PHP.

---

## Què és PHP?

PHP és un llenguatge d'ús extés a desenvolupament web, que és on és realment fort.
Això no vol dir que no es pugui fer servir en altres tipus de projectes(principalment pel creixement de [NativePHP](https://nativephp.com/) però és gens dubte, el desenvolupament web backend, on és especialment útil.

PHP és un llenguatge multiparadigma, que vol dir que permet diversos estils de programació. Per exemple, permet la creació de classes/objectes, però no és obligatori fer-les servir per a programar en PHP.

Algunes de les principals diferències entre PHP i Python son:

- Les instruccions acaben amb `;`,
- Els blocs de codi es marquen amb `{}`,
- Tota variable/paràmetre/atribut en PHP comença amb "$".
- Les *keywords* per declarar funcions,classes, varien.
- Hi ha més tipus de bucle a PHP i també més tipus de sentències condicionals.
- Tota porció de codi font que vulgui ser interpretada en PHP ha de començar pero "<?php"


---

## Primer programa

Aquest és un programa mínim en Java:

```php 
<?php
    echo "Hola,mòn\n"
>
```
---

## Diferències ràpides amb Python

| Python | PHP |
| ------ | ---- |
| `print("Hola")` | `echo "Hola\n";` |
| `age = 20` | `$age = 20;` |
| `name = "Anna"` | `$name = "Anna";` |
| `if age >= 18:` | `if ($age >= 18) { ... }` |
| `elif` | `else if` |
| La indentació defineix blocs | Les claus `{}` defineixen blocs |
| Pots escriure scripts simples directament | Pots organitzar el codi font dins de classes o no |
| Llistes | Arrays |
| `def` o `function` | function |

---

## Què has de saber buscar a la documentació?

Per fer els primers exercicis, hauràs de buscar com es fan aquestes coses en PHP:

### Variables i tipus

Preguntes guia:

- Com declaro un número enter?
- Com declaro un número decimal?
- Com declaro un text?
- Com declaro un booleà?

Paraules clau per buscar:

- `int`
- `float`
- `string`
- `boolean`

### Condicionals

Preguntes guia:

- Com s'escriu un `if` en PHP?
- Com s'escriu un `else`?
- Com s'escriu un `else if`?
- Quina diferència hi ha entre `=`,`==`?

### Bucles

Preguntes guia:

- Com faig un bucle `while`?
- Com faig un bucle `for`?
- Puc declarar bucles de més maneres?
- Com puc repetir una acció 10 vegades?
- Com puc recórrer un array?

### Arrays 

Preguntes guia:

- Quina diferència hi ha entre un array i un array associatiu?
- Com creo un array?
- Com afegeixo elements?
- Com llegeixo un element?
- Com sé quants elements té?

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

En PHP normalment parlem de **mètodes**(si son funcions dins una classe) o **funcions**(si no estan declarades dins una classe)

```php
function saludar(string $nom): void {
    echo "Hola ".$nom."\n";
}
```

Exemple amb retorn:

```php
function sumar(int $a, int $b): int {
    return $a + $b;
}
```

Comparació ràpida:

| Python | JavaScript | PHP |
| ------ | ---------- | ---- |
| `def saludar(nom):` | `function saludar(nom) {}` | `function saludar(string $nom):void {}` |
| `return a + b` | `return a + b;` | `return $a + $b;` |

Preguntes guia:

- Com creo un mètode que retorna un número?
- Com creo un mètode que no retorna res?
- On escric els mètodes dins d'una classe?
- Quin tipus retorna el mètode?
- Quins paràmetres rep?

### Comparar

A PHP tenim operadors d'igualtat entre variables "=="(compara valors) 
i d'igualtat estricta "==="(compara valors i tipus de variable)

## Errors típics venint de Python

- Oblidar el `;`.
- Escriure `elif` en lloc de `else if`.
- Fer servir `print()` en lloc de `echo `.
- Oblidar les claus `{}`.
- Fer servir llistes en lloc d'arrays.
- Pensar que la indentació defineix els blocs. A PHP ajuda a llegir, però els blocs reals els marquen les claus.

---

## Documentació recomanada

- [PHP Data Types](https://www.w3schools.com/php/php_datatypes.asp)
- [PHP Conditions](https://www.w3schools.com/php/php_if_else.asp)
- [PHP Loops](https://www.w3schools.com/php/php_looping.asp)
- [PHP Arrays](https://www.w3schools.com/php/php_arrays.asp)
- [PHP Functions](https://www.w3schools.com/php/php_functions.asp)
- [PHP POO](https://www.w3schools.com/php/php_oop_classes_objects.asp)


