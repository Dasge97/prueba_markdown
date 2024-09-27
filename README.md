# MUNCHKIN, EL COMIENZO DEL FIN
Munchkin es un juego de cartas de `rol` diseñado por Steve Jackson e ilustrado por John Kovalic para Steve Jackson Games. El lema que resume el objetivo del juego es ***"Mata a los monstruos, roba el tesoro, apuñala a tus amigos"***. 

## Objetivo del juego

En Munchkin, un jugador empieza siendo un **humano** de `nivel 1` sin *clase* y su objetivo consiste en alcanzar el `nivel 10` antes de que los demás consigan hacerlo. Para ello, cada jugador debe enfrentarse a **monstruos** encontrados en la `mazmorra` con la ayuda de `armas`, superar maldiciones que podrían molestar enormemente y emplear sabiamente el equipamiento encontrado en las `mazmorras`.

## Caso práctico

>Nos encontramos casi al final de la partida, quedan 3 personajes potenciales para llevarse la partida, uno de ellos se encuentra en el nivel 9, los otros dos en el nivel 8.

>El amigo `B` es el que se encuentra en el nivel 9, a un nivel de la victoria, lo que no sabe es que `A` y `B`estan cargados de cartas para evitarlo.

Vamos a presentar un poco a los personajes:

### `A`

Se trata de un humano, guerrero, hombre:

![GUERRERO HUMANO](https://img.freepik.com/fotos-premium/guerrero-medieval-espada-armadura-caminando-bosque_124507-189137.jpg)

***Equipamiento:***
+ Espada
+ Botas
+ Armadura

### `B`

Se trata de una enana, maga, mujer:

![ENANA MAGA](https://tse2.mm.bing.net/th?id=OIG3.wziALuEs27aypawheXLM&pid=ImgGn)

***Equipamiento:***
+ Bastón
+ Gorro mágico

### `C`

Se trata de un centauro, bardo, sin sexo:
![CENTAURO BARDO](https://tse1.mm.bing.net/th?id=OIG3.quhvzgoLWU2n8mhNxZpC&pid=ImgGn)

***Equipamiento:***

+ Arpa
+ Montura

## **Tabla de atributos de los personajes**

|ATRIBUTO|A|B|C
| --- | --- | --- | --- |
|Fuerza|10|2|7
|Inteligencia|1|10|3
|Carisma|7|0|10

## **DESARROLLO DE LA PARTIDA**

>Aunque parezca que la partida se ha acabado, y que `B` esta a punto de terminar, aun le faltan 3-4 horas a la partida, porque ahora es el momento en el que todo el mundo empeiza a utilizar sus ases bajo la manga para hacer que el otro no gane, y si! Se que te ha parecido interesante, aqui abajo te dejo un link de compra para que pruebes el juego con tus amigos:

[JUEGO DE MESA "MUNCHKIN"](https://outlet-pc.es/products/munchkin-embalaje-deteriorado?utm_source=google&utm_medium=cpc&utm_campaign=ES%20-%20Performance%20Max%20-%20General&utm_content=Performance%20Max&utm_term=&gad_source=1&gclid=Cj0KCQjwr9m3BhDHARIsANut04ZD8R4t_Dwkh8wKLxMsafhVjD3E5VATDmJXoNefIBSlFDr-WUcy1ysaAneuEALw_wcB)

## **FICHAS TÉCNICAS (yaml)**

```yaml
Nombre: A
  Nivel: 8
  Raza: Humano
  Clase: Guerrero
  Sexo: Hombre
  Equipado: true

Nombre: B
  Nivel: 9
  Raza: Enano
  Clase: Mago
  Sexo: Mujer
  Equipado: true

Nombre: C
  Nivel: 8
  Raza: Centauro
  Clase: Bardo
  Sexo: null
  Equipado: true
```
## FICHA TÉCNICA (json) 

```json
{
    "Personajes":
    [
    {
        "Nombre": "A",
        "Nivel": 8,
        "Raza": "Humano",
        "Clase": "Guerrero",
        "Sexo": "Hombre",
        "Equipado": true,
        "Atributos":
        {
            "Fuerza":10,
            "Inteligencia":1,
            "Carisma":7
        },
        "Equipamiento":
        [
            "Espada",
            "Botas",
            "Armadura"
        ]
    },
    {
        "Nombre": "B",
        "Nivel": 9,
        "Raza": "Enano",
        "Clase": "Mago",
        "Sexo": "Mujer",
        "Equipado": true,
        "Atributos":
        {
            "Fuerza":2,
            "Inteligencia":10,
            "Carisma":0
        },
        "Equipamiento":
        [
            "Baston",
            "Gorro magico"
        ] 
    },
    {
        "Nombre": "C",
        "Nivel": 8,
        "Raza": "Centauro",
        "Clase": "Bardo",
        "Sexo": null,
        "Equipado": true,
        "Atributos":
        {
            "Fuerza":7,
            "Inteligencia":3,
            "Carisma":10
        },
        "Equipamiento":
        [
            "Arpa",
            "Montura" 
        ]
    }
    ]
}


```










