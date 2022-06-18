# Lógica

{% hint style="info" %}
**Lógica de Boole:** Repasar Leyes de Morgan, tautologías y falacias.
{% endhint %}

## Variables

1. Hacer un programa que dado una variable a = true o a = false, y una variable b, siempre logremos que b = true sin escribir explícitamente b = true (b debe ser igual a una operación que involucre a a).
2. Ídem punto anterior, pero con b = false.
3. Reduzca la expresión a = !(b || (c || false)).
4. ¿Cuáles son los elementos neutros de la sentencia OR y AND?
5. ¿Cómo queda invertida la sentencia a > b?

## Condicionales

1. Dado el siguiente código, indique cómo puede simplificarse.
```java
if(a > b) {
    if(b > c) {
        System.out.println("OK");
    }
}
```
2. Dado el siguiente código, indique cómo puede simplificarse.
```java
if(a > b) {
    System.out.println("OK");
}
if(b > c) {
    System.out.println("OK");
}
```
3. Dado el siguiente código, indique cómo puede simplificarse.
```java
if(a > b) {
    System.out.println("OK");
    System.out.println("OK1");
} else {
    System.out.println("OK");
    System.out.println("OK2");
}
```
4. Dado el siguiente código, indique cómo puede simplificarse.
```java
if(a > b || a <= b) {
    System.out.println("OK");
    System.out.println("OK1");
} else {
    System.out.println("OK");
    System.out.println("OK2");
}
```
5. Dado el siguiente código, indique cómo puede simplificarse.
```java
if(a > b && a <= b) {
    System.out.println("OK");
    System.out.println("OK1");
} else {
    System.out.println("OK");
    System.out.println("OK2");
}
```