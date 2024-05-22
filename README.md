# PureScript

## Ficha Del lenguaje
###  **Propósito:**

Propósito general, puede ser usado tanto en backend como frontend.
###  **Paradigma:**

Programación funcional.

###  **Fortalezas y debilidades**

Fortalezas:
- Row polymorphism o polimorfismo por filas. Permite que diferentes tipos de datos compartan la misma interfaz.
- Reusar código existente de javascript.
Debilidades:
- Curva de aprendizaje


(PureScript, https://www.purescript.org)
###  **Implementación:**

Transpilado a javascript

###  **Runtime / Maquina Virtual**

El manejador de paquetes recomendado y herramienta de build:  spago
```
npm install -g spago
```

- Corre en el maquina virtual de nodejs

Ref: [Getting started](https://github.com/purescript/documentation/blob/master/guides/Getting-Started.md)

###  **Plataformas soportadas:**

- Win, Linux y Mac
- Cualquier plataforma ejecutando Nodejs

###  **Usuarios notables:**


Empresas :
- [Atomic IT Solutions](http://atomicits.com/)
- [Awake Security](http://awakesecurity.com/)
###  **Historia:**

PureScript fue inicialmente diseñado por  Phil Freeman en 2013 con el fin de hacer un Haskell que transpile (se transforme) a Javascript correctamente. Desde ese entonces ha sido tomado por la comunidad y mantenido en Github.

Ultima version: [v0.15.16-1](https://github.com/purescript/purescript/releases/tag/v0.15.16-1)
Referencia: [Wikipedia](https://en.wikipedia.org/wiki/PureScript)
###  **Estado:**

Activo

##### II) Realizar "Hello World" con el lenguaje asignado. (videos)

```
npm install -g purescript

npm install -g spago

spago init
spago build
spago test
spago repl

> import Main
> main
```

##### III) Demostrar como se interactúa con el Environment con el lenguaje asignado. (videos)

- Argumentos de linea de comando
```
spago init
spago build
spago test
spago repl
```

- Standard Streams: Standard Input, Output y Error



- Variables de ambiente  
    
- File I/O
- Network I/O