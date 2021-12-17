# ¿Qué es Haskell?

Es uno de los lenguajes líderes a la hora de enseñar programación funcional, permite escribir código simple y claro, enseña a como estructurar y razonar los programas.

> Nos olvidamos de la parte de hardware o manipular la memoria y simplemente nos enfocamos en solucionar el problema.

Haskell promueve:
* Un estilo de programación más abstarcto donde solo nos preocupamos por las operaciones.
* Un estilo basado en la idea de aplicar funciones

Podemos aprender:
* A crear programas más simples
* A obtener un conjunto de herramientas nuevas para estructurar y razonar sobre los programas
* Aprender conceptos de programación funcional

# ¿Qué es programación funcional?
Puede verse como un estilo de programación donde el método básico de computación es la aplicaión de funciones  a argumentos.
## Imperativo vs Funcional
```python
total = 0
for i in range(1, n+1):
	total += i
```
vs
```haskell
sum [1..n]
```

Los lenguajes de programación imperativos muchas veces soportan estas características pero no fomentan el uso de estilo funcional.

### Muchos lenguajes no soportan:
* almacenar funciones en listas
* hacer funciones tomen funciones y retornen funciones
