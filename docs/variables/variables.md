# **Variables Primitivas en C#**

## **Introducción**

En programación, las variables son contenedores que almacenan datos en la memoria RAM de la computadora. En C#, las variables primitivas representan los tipos de datos más básicos, como números, caracteres y valores booleanos. Estas variables son fundamentales para cualquier programa, ya que permiten realizar cálculos, tomar decisiones y almacenar información temporalmente.

Cuando declaramos una variable, el sistema operativo reserva un espacio en la memoria RAM para almacenar su valor. La cantidad de memoria reservada depende del tipo de dato de la variable.

---

## **Relación con la Memoria RAM**

Cada variable ocupa un espacio específico en la memoria RAM. Este espacio depende del tipo de dato:

- **int**: 4 bytes (32 bits)
- **float**: 4 bytes (32 bits)
- **bool**: 1 byte (8 bits)
- **char**: 2 bytes (16 bits)
- **string**: Variable (depende de la longitud del texto)
- **object**: Depende del tipo de dato almacenado

Por ejemplo, si declaramos una variable `int`, el sistema reservará 4 bytes en la memoria RAM para almacenar su valor.

>  ¿Por qué 4 bytes son 32 bits?

Un byte es una unidad de almacenamiento que equivale a 8 bits. Por lo tanto, cuando decimos que algo ocupa 4 bytes, estamos diciendo que ocupa 4 × 8 = 32 bits. Cada bit puede representar un valor binario (0 o 1), lo que significa que un espacio de 32 bits puede almacenar hasta 2³² valores diferentes. Esto es lo que permite que un `int` en C# represente un rango de valores desde -2,147,483,648 hasta 2,147,483,647.


> o sea... si por ejemplo...
> quiero almacenar el numero _6_ en un **Int32**.

| 1 byte |1 byte | 1 byte | 1 byte |
| :-: | :-: | :-: | :-: |
| 00000000 | 00000000 | 00000000 | 00000**11**0 |

>cada posicion de desde derecha a izquierda <-
es un exponente 2^X

ejemplo tomando el primer byte

| 2^7 |2^6 |2^5 |2^4 |2^3 |2^2 |2^1 |2^0 |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
| 0 | 0 | 0 | 0 |0 | **1** | **1** | 0 |

```
2^2     +   2^1   =     6
4       +   2     =     6
```


---

## **Definición de Variables**

Para definir una variable en C#, necesitamos especificar:

1. **Tipo de dato**: Define qué tipo de información almacenará la variable.
2. **Nombre**: Identificador único para referirse a la variable.
3. **Valor inicial (opcional)**: Podemos asignar un valor al momento de declarar la variable.

### Ejemplo:

```csharp
int edad = 25; // Tipo de dato: int, Nombre: edad, Valor inicial: 25
float altura = 1.75f; // Tipo de dato: float, Nombre: altura, Valor inicial: 1.75
bool esMayor = true; // Tipo de dato: bool, Nombre: esMayor, Valor inicial: true
```

---

## **Escritura y Lectura de Variables**

### Escritura (Asignación de Valores)

Podemos asignar un valor a una variable utilizando el operador `=`:

```csharp
int numero = 10; // Asignación inicial
numero = 20; // Reasignación
```

### Lectura (Uso de Valores)

Para leer el valor de una variable, simplemente usamos su nombre:

```csharp
print(numero); // Imprime el valor de la variable 'numero'
```

---

## **Buenas Prácticas**

1. Usa nombres descriptivos para las variables.
    ```csharp
    int p = 20; // que es p?
    int variable_para_sumar_perritos_en_el_nivel5_etapa4 = 20; //demasiado
    int perritos = 20; // se entiende en el contexto
    int dogs = 20 // es buena práctica escribirla en ingles
    ```
2. Declara las variables lo más cerca posible de donde se usan.
> [!NOTE]
> aprovechemos que en C# no necesitamos una estructura especifica de declaracion de variables como por ejemplo en c++ que tenemos que especificamente crear las variables en la zona de cabecera 
3. Inicializa las variables siempre que sea posible para evitar errores.

Con estas bases, puedes comenzar a trabajar con variables primitivas en C# y entender cómo interactúan con la memoria RAM.

### Referencias
[Documentacion oficial de Microsoft](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types)
[w3schools: variables](https://www.w3schools.com/cs/cs_variables.php)
[w3schools: tipos de datos](https://www.w3schools.com/cs/cs_data_types.php)

> #### [volver al inicio](../../README.md)
