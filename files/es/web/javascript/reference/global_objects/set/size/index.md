---
title: Set.prototype.size
slug: Web/JavaScript/Reference/Global_Objects/Set/size
translation_of: Web/JavaScript/Reference/Global_Objects/Set/size
original_slug: Web/JavaScript/Referencia/Objetos_globales/Set/size
---

{{JSRef}}

La propiedad de acceso **`size`** devuelve el número de elementos que hay en el objeto {{jsxref("Set")}}.

## Descripción

El valor de `size` es un entero que representa cuantas entradas tiene el objeto `Set`. La función de accesso set para `size` es `undefined`; no se puede cambiar esta propiedad.

## Ejemplos

### Usando `size`

```js
var mySet = new Set();
mySet.add(1);
mySet.add(5);
mySet.add("un texto")

mySet.size; // 3
```

## Especificaciones

{{Specifications}}

## Compatibilidad de navegadores

{{Compat("javascript.builtins.Set.size")}}

## Ver también

- {{jsxref("Set")}}
