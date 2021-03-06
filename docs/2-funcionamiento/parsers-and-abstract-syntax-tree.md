# Parsers y el Abstract Syntax Tree

El JS Engine recibe el código fuente y lo procesa de la siguiente manera:

- El **parser** descompone y crea tokens que integran el AST.
- Se compila a **bytecode** y se ejecuta.
- Lo que se pueda se **optimiza a machine code** y se reemplaza el código base.

**Un SyntaxError** es lanzado cuando el motor JavaScript encuentra partes que no forman parte de la sintaxis del lenguaje y esto lo logra gracias a que se tiene un AST generado por el parser.

El _parser_ es del 15% al 20% del proceso de ejecución por lo que hay que usar parser del código justo en el momento que lo necesitamos y no antes de saber si se va a usar o no.

![](../../assets/images/funcionamiento/parsers-and-abstract-syntax-tree.webp)

## Lecturas recomendadas

1. [https://esprima.org/](https://esprima.org/)
2. [https://astexplorer.net/](https://astexplorer.net/)
