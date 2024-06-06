# Aprende Go en castellano 🇪🇸

![mascota de golang estudiando](./images/pet.jpeg)

Aprende Go en castellano con ejemplos tutoriales y ejercicios.

## Summary

- [Strings](./strings/strings.md#1-strings-en-go)
  - [Longitud de un string](./strings/strings.md#11-longitud-de-un-string)
  - [Accediendo a bytes individuales de un string](./strings/strings.md#12-accediendo-a-bytes-individuales-de-un-string)
  - [Usando un loop for/range en un string](./strings/strings.md#13-usando-un-loop-forrange-en-un-string)
  - [Que es una runa](./strings/strings.md#14-que-es-una-runa)
  - [Strings son inmutables](./strings/strings.md#15-strings-son-inmutables)
  - [Strings usando backtick comillas invertidas](./strings/strings.md#16-strings-usando-backtick-comillas-invertidas)
  - [Comparacion de caracteres](./strings/strings.md#17-comparacion-de-caracteres)
  - [Comparacion de strings](./strings/strings.md#18-comparacion-de-strings)
  - [Crear un string a partir de un slice de bytes](./strings/strings.md#19-crear-un-string-a-partir-de-un-slice-de-bytes)
  - [Creando un string a partir de un slice de runas](./strings/strings.md#110-creando-un-string-a-partir-de-un-slice-de-runas)
  - [Concatenacion de strings](./strings/strings.md#111-concatenacion-de-strings)
- [Arrays](./arrays/arrays.md#1-arrays-en-go)
  - [Que es un array](./arrays/arrays.md#11-que-es-un-array)
  - [Como declarar un array](./arrays/arrays.md#12-como-declarar-un-array)
  - [Asignacion de valores a un array](./arrays/arrays.md#13-asignacion-de-valores-a-un-array)
  - [Inicializacion de un array](./arrays/arrays.md#14-inicializacion-de-un-array)
  - [Inicializacion de un array multilinea](./arrays/arrays.md#15-inicializacion-de-un-array-multilinea)
  - [Declaracion automatica de la longitud de un array](./arrays/arrays.md#16-declaracion-automatica-de-la-longitud-de-un-array)
  - [Encuentra la longitud de un array](./arrays/arrays.md#17-encuentra-la-longitud-de-un-array)
  - [Comparacion de arrays](./arrays/arrays.md#18-comparacion-de-arrays)
  - [Iteracion de arrays](./arrays/arrays.md#19-iteracion-de-arrays)
  - [Arrays multidimensionales](./arrays/arrays.md#110-arrays-multidimensionales)
  - [Pasar un array a una funcion](./arrays/arrays.md#111-pasar-un-array-a-una-funcion)
- [Slices](./slices/slices.md#1-slices-en-go)
  - [Introducción, que es un slice](./slices/slices.md#11-introducci%C3%B3n-que-es-un-slice)
  - [El Slice es una referencia a un array](./slices/slices.md#12-el-slice-es-una-referencia-a-un-array)
  - [Longitud y capacidad de un slice](./slices/slices.md#13-longitud-y-capacidad-de-un-slice)
  - [Slice es una Struct](./slices/slices.md#14-slice-es-una-struct)
  - [Append function](./slices/slices.md#15-append-function)
  - [Anonymous array slice](./slices/slices.md#16-anonymous-array-slice)
  - [Funcion copy](./slices/slices.md#17-funcion-copy)
  - [Funcion make](./slices/slices.md#18-funcion-make)
  - [Unpack operator](./slices/slices.md#19-unpack-operator)
  - [Extract operator](./slices/slices.md#110-extract-operator)
  - [Slice iteration](./slices/slices.md#111-slice-iteration)
  - [Pasado por referencia](./slices/slices.md#112-pasado-por-referencia)
  - [Delete slice elements](./slices/slices.md#113-elete-slice-elements)
  - [Comparacion de slices](./slices/slices.md#114-comparacion-de-slices)
  - [Slices multi-dimensionales](./slices/slices.md#115-slices-multi-dimensionales)
  - [Optimizacion de memoria](./slices/slices.md#116-optimizacion-de-memoria)
- [Condicionales](./conditionals/conditionals.md#1-condicionales)
  - [Condicional if](./conditionals/conditionals.md#11-condicional-if)
  - [Condicional if-else](./conditionals/conditionals.md#12-condicional-if-else)
  - [Condicional if else if](./conditionals/conditionals.md#13-condicional-if-else-if)
    - [Estado inicial](./conditionals/conditionals.md#131-estado-inicial)
    - Ternary condition
  - [Condicional switch](./conditionals/conditionals.md#14-condicional-switch)
    - The syntax of the switch statement
    - [Default case](./conditionals/conditionals.md#141-default-case)
    - [Múltiples valores en el case](./conditionals/conditionals.md#142-multiples-valores-en-el-case)
    - [Inicial statement](./conditionals/conditionals.md#143-inicial-statement)
    - [Expressionless switch statement](./conditionals/conditionals.md#144-expressionless-switch-statement)
    - [Fallthrough statement](./conditionals/conditionals.md#145-fallthrough-statement)
- [Iteradores](./iterators/iterators.md#1-Iteradores)
  - [Bucles for](./iterators/iterators.md#11-bucles-for)
    - [Sintaxis del bucle for](./iterators/iterators.md#111-sintaxis-del-bucle-for)
    - [Variantes del bucle for](./iterators/iterators.md#112-variantes-del-bucle-for)
      - [Opcional init statment](./iterators/iterators.md#1121-opcional-init-statment)
      - [Opcional post statment](./iterators/iterators.md#1122-opcional-post-statment)
      - [Opcional init y statment](./iterators/iterators.md#2123-opcional-init-y-post-statment)
      - [Sin ningún statment](./iterators/iterators.md#1124-sin-ningun-statment)
      - [El break statment](./iterators/iterators.md#1125-el-break-statement)
      - [El continue statment](./iterators/iterators.md#1126-el-continue-statement)
      - [El return statment](./iterators/iterators.md#1127-el-return-statement)
      - [Range](./iterators/iterators.md#1128-range)
        - [Range sobre un array](./iterators/iterators.md#11281-range-sobre-un-array)
        - [Range sobre un map](./iterators/iterators.md#11282-range-sobre-un-map)
          - [Range sobre un map usando keys](./iterators/iterators.md#112821-range-sobre-un-map-usando-keys)
          - [Range sobre un map usando key value](./iterators/iterators.md#112822-range-sobre-un-map-usando-key-value)
- [Maps](./maps/maps.md#1-maps-en-go)
  - [Que es un map](./maps/maps.md#11-que-es-un-map)
  - [Crear un map vacio](./maps/maps.md#12-crear-un-map-vacio)
  - [Inicializar un map](./maps/maps.md#13-inicializar-un-map)
  - [Accediendo a los datos de un map](./maps/maps.md#14-accediendo-a-los-datos-de-un-map)
  - [Longitud de un map](./maps/maps.md#15-longitud-de-un-map)
  - [Eliminar un elemento de un map](./maps/maps.md#16-eliminar-un-elemento-de-un-map)
  - [Comparacion de maps](./maps/maps.md#17-comparacion-de-maps)
  - [Iteracion sobre un map](./maps/maps.md#18-iteracion-sobre-un-map)
  - [Map con otros tipos de datos](./maps/maps.md#19-map-con-otros-tipos-de-datos)
  - [Maps son tipos de referencia](./maps/maps.md#110-maps-son-tipos-de-referencia)
  - [Copiar un map](./maps/maps.md#111-copiar-un-map)
- [Punteros](./pointers/pointers.md#1-punteros-en-go)
  - [Cómo acceder a la dirección de memoria de una variable?](./pointers//pointers.md#11-c%C3%B3mo-acceder-a-la-direcci%C3%B3n-de-memoria-de-una-variable)
  - [Que es un puntero?](./pointers//pointers.md##12-que-es-un-puntero)
  - [Desreferenciar un puntero](./pointers//pointers.md##13-desreferenciar-un-puntero)
  - [Cambiar el valor de la variable usando un puntero](./pointers//pointers.md##14-cambiar-el-valor-de-la-variable-usando-un-puntero)
  - [La función new](./pointers//pointers.md##15-la-funci%C3%B3n-new)
  - [Pasar un puntero a una función](./pointers//pointers.md##16-pasar-un-puntero-a-una-funci%C3%B3n)
  - [Aritmética de punteros](./pointers//pointers.md##17-aritm%C3%A9tica-de-punteros)a-función)
- [Estructuras en go (structs)](./structs/structs.md)
  - [¿Qué es una estructura?](./structs/structs.md#1-qu%C3%A9-es-una-estructura)
  - [Declarar un tipo de estructura](./structs/structs.md#11-declarar-un-tipo-de-estructura)
  - [Creando una estructura](./structs/structs.md#12-creando-una-estructura)
  - [Obtener y establecer campos de estructura](./structs/structs.md#13-obtener-y-establecer-campos-de-estructura)
  - [Inicializando una estructura](./structs/structs.md#14-inicializando-una-estructura)
  - [Estructura anónima](./structs/structs.md#15-estructura-an%C3%B3nima)
  - [Puntero a una estructura](./structs/structs.md#16-puntero-a-una-estructura)
  - [Campos anónimos](./structs/structs.md#17-campos-an%C3%B3nimos)
  - [Estructura anidada](./structs/structs.md#18-estructura-anidada)
  - [Campos promocionados](./structs/structs.md#19-campos-promocionados)
  - [Campos de función](./structs/structs.md#110-campos-de-funci%C3%B3n)
  - [Comparación de estructuras](./structs/structs.md#111-comparaci%C3%B3n-de-estructuras)
  - [Metadatos de campo de estructura](./structs/structs.md#112-metadatos-de-campo-de-estructura)
- [Funciones](./functions/functions.md)
  - [Qué es una función?](./functions/functions.md#11-qu%C3%A9-es-una-funci%C3%B3n)
  - [Convención de nombres para funciones](./functions/functions.md#12-convenci%C3%B3n-de-nombres-para-funciones)
  - [Parámetros en funciones](./functions/functions.md#13-par%C3%A1metros-en-funciones)
  - [Valor de retorno](./functions/functions.md#14-valor-de-retorno)
  - [Multiples valores de retorno](./functions/functions.md#15-multiples-valores-de-retorno)
  - [Valores de retorno nombrados](./functions/functions.md#16-valores-de-retorno-nombrados)
  - [Función recursiva](./functions/functions.md#17-funci%C3%B3n-recursiva)
  - [`defer` keyword](./functions/functions.md#18-defer-keyword)
  - [Función como tipo](./functions/functions.md#19-funci%C3%B3n-como-tipo)
  - [Función como valor (función anónima)](./functions/functions.md#110-funci%C3%B3n-como-valor-funci%C3%B3n-an%C3%B3nima)
  - [Función como valor (función anónima)](./functions/functions.md#111-expresi%C3%B3n-de-funci%C3%B3n-invocada-inmediatamente-iife)
- [Variadic functions in go](./functions/variadic-functions.md#1-variadic-functions-in-go)
  - [Que es una variadic function](./functions/variadic-functions.md#11-que-es-una-variadic-function)
    - [Append es una variadic function](./functions/variadic-functions.md#111-append-es-una-variadic-function)
  - [Crear una variadic function](./functions/variadic-functions.md#12-crear-una-variadic-function)
  - [Como pasar un slice a una variadic function](./functions/variadic-functions.md#13-como-pasar-un-slice-a-una-variadic-function)
  - [Slice arguments o Variadic arguments](./functions/variadic-functions.md#14-slice-arguments-o-variadic-arguments)
- [Métodos](./methods/methods.md#1-métodos-en-go)
  - [Que es un método?](./methods/methods.md#11-que-es-un-método)
  - [Métodos con el mismo nombre](./methods/methods.md#12-métodos-con-el-mismo-nombre)
  - [Pointer receivers](./methods/methods.md#13-pointer-receivers)
    - [Métodos de llamada con receiver de puntero en valores](./methods/methods.md#131-métodos-de-llamada-con-receiver-de-puntero-en-valores)
  - [Métodos en estructuras anidadas](./methods/methods.md#14-métodos-en-estructuras-anidadas)
    - [Métodos en estructuras anidadas](example-methods/methods.md#141-métodos-en-estructuras-anidadas)
    - [Estructuras anidadas anónimamente](./methods/methods.md#142-estructuras-anidadas-anónimamente)
    - [Métodos promocionados](./methods/methods.md#143-métodos-promocionados)
  - [Métodos pueden aceptar ambos, punteros y valores](./methods/methods.md#15-métodos-pueden-aceptar-ambos-punteros-y-valores)
  - [Métodos en no struct type](./methods/methods.md#16-métodos-en-no-struct-type)
- [Interfaces](./interfaces/interfaces.md)
  - [Que es una interfaz?](./interfaces/interfaces.md#1-que-es-una-interfaz)
  - [Declaración de interfaz](./interfaces/interfaces.md#12-declaración-de-interfaz)
  - [Implementación de interfaz](./interfaces/interfaces.md#13-implementación-de-interfaz)
  - [Interfaz vacía](./interfaces/interfaces.md#14-interfaz-vacía)
  - [Interfaces multiples](./interfaces/interfaces.md#15-interfaces-multiples)
  - [Type assertion](./interfaces/interfaces.md#16-type-assertion)
  - [Type switch](./interfaces/interfaces.md#17-type-switch)
  - [Interfaces embebidas](./interfaces/interfaces.md#18-interfaces-embebidas)
  - [Pointer vs Value receiver](./interfaces/interfaces.md#19-pointer-vs-value-receiver)
  - [Comparación de interfaces](./interfaces/interfaces.md#110-comparación-de-interfaces)
  - [Uso de interfaces](./interfaces/interfaces.md#111-uso-de-interfaces)
- [Introduction to Streams and Buffers](https://medium.com/rungo/introduction-to-streams-and-buffers-d148c0cda0ad)
  - What are a stream and a buffer
  - Reading from a Data Source
    - io.Reader
    - strings.NewReader
    - ioutil.ReadAll
    - io.ReadFull
    - io.LimitReader
  - Writing to a Data Store
    - io.Writer
    - io.WriteString
    - Standard I/O Streams
  - Closing I/O Operations
  - Transferring Data between streams
    - io.Copy
    - io.Pipe
  - Buffered streams
- [Trabajando con JSON](./work-with-json/work-with-json.md#1-trabajando-con-json)
  - [Introducción](./work-with-json/work-with-json.md#11-introduccion)
  - [Codificando JSON](./work-with-json/work-with-json.md#12-codificando-json)
    - [Manejo de tipos de datos](./work-with-json/work-with-json.md#121-manejo-de-tipos-de-datos)
    - [Tipos de datos abstractos](./work-with-json/work-with-json.md#122-tipos-de-datos-abstractos)
    - [Conversión de tipos de datos](./work-with-json/work-with-json.md#123-conversion-de-tipos-de-datos)
    - [Codificando usando structure tags](./work-with-json/work-with-json.md#124-codificando-usando-structure-tags)
    - [Codificar trabajando con maps](./work-with-json/work-with-json.md#125-codificar-trabajando-con-maps)
  - [Decodificando JSON](./work-with-json/work-with-json.md#13-decodificando-json)
    - [Manejando estructuras de datos complejas](./work-with-json/work-with-json.md#131-manejando-estructuras-de-datos-complejas)
    - [Campos promocionados](./work-with-json/work-with-json.md#132-campos-promocionados)
    - [Decodificando usando structure tags](./work-with-json/work-with-json.md#133-decodificando-usando-structure-tags)
    - [Decodificar trabajando con maps](./work-with-json/work-with-json.md#134-decodificar-trabajando-con-maps)
    - [Usando Unmarshaler and TextUnmarshaler](./work-with-json/work-with-json.md#135-usando-unmarshaler-and-textunmarshaler)
  - [Codificador y Decodificador](./work-with-json/work-with-json.md#14-codificador-y-decodificador)
    - [Codificador](./work-with-json/work-with-json.md#141-codificador)
    - [Decodificador](./work-with-json/work-with-json.md#142-decodificador)
- [Goroutines](./goroutines/goroutines.md#1-goroutines-en-go)
  - [Introducción](./goroutines/goroutines.md#11-introducci%C3%B3n)
  - [Corrutinas en Go](./goroutines/goroutines.md#12-corrutinas-en-go)
  - [WaitGroups en Go](./goroutines/goroutines.md#13-waitgroups-en-go)
    - [El método Add](./goroutines/goroutines.md#131-el-m%C3%A9todo-add)
    - [El Método Done](./goroutines/goroutines.md#132-el-m%C3%A9todo-done)
  - [Funciones anónimas en goroutines](./goroutines/goroutines.md#14-funciones-an%C3%B3nimas-en-goroutines)
- Katas
  - [Leap Year](./katas/leapyear/leapyear.md)
  - [String Calculator](./katas/stringcalculator/stringcalculator.md)
