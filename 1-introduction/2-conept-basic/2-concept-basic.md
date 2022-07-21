## Inicio

- Para iniciar una aplicacion en **Dart** se utiliza en metodo `main()` sin parametros.

```kotlin
fun main(){
    println("Hola mundo");
}
```

- Tambien el metodo `main()` puede tener parametros.

```kotlin
fun main(args: Array<String>){
    println("Hola mundo");
}
```

## Tipos de datos
- Los tipos de datos en kotlin son todos Objetos.
    - Byte
    - Short
    - Int
    - Long
    - Enteros sin signo
      - UByte
      - UShort 
      - UInt
      - ULong
    - Double
    - Float
    - Boolean
    - String
    - Array
- Conversion de tipos
    - toByte()
    - toShort()
    - toInt()
    - toLong()
    - toFloat()
    - toDouble()
    - toChart()
- [Data types](../examples/2-basic/1-data-types/main/README.md)


# Conceptos basicos
- Variables Podemos almacenar un dato
- Objetos 
- En kotlin todo sera un objetos

## Tipos de datos
 - Primitivos
 - Objetos

### Primitivos
- No debemos declarar tipos de datos primitivos en kotlin
- Se puede utilizar pero no es recomendable
- Son definidos cuando no lo usamos como objeto
```kotlin
// En este modo Kotlin lo toma como dato primitivo
var i = 10
i = i * 2
println(i)
```
- Kotlin utiliza **wrappers** para los numeros se llama **boxing**

## Operadores
