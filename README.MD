# Cabecera H1

## Cabecera h2

### Cabecera h3

#### Cabecera h4

##### Cabecera h5

###### Cabecera h6

## Underline 1

# Underline 2

# Formatos

<!-- - Formato *italica*, primer forma. -->

- Formato _italica_, segunda forma.
- Formato **bold**, primera forma.
<!-- - Formato __bold__, segunda forma. -->
- formato ~~tachado~~, formato normal.
- texto de `color`.

# Listas

1. Esto es un item
2. Esto es un item
3. Esto es un item

# Links

[Esto es un link en MD](http://www.google.com)

# Imagenes

![Logo GitHub](https://image.flaticon.com/icons/png/512/25/25231.png)

# Code snipets

Codigo JS

```JavaScript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

Codigo JSON

```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```

# Tablas

| Nombre  | Apellido | Documento |
| ------- | -------- | --------- |
| Maxi    | Pelaes   | 111616    |
| Roberto | Yobabas  | 231684    |

# Citas

Esto es un texto referente al texto debajo:

> Esto es una cita

Esto esta fuera de la cita

# Lineas divisoras

Texto dividido

---

Otro texto dividido

# Saltos de linea

Parrafo 1

Parrafo 2
