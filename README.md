# Naramarilla Software

# APP Toy Story
Para realizar la aplicación podrás utilizar:
- [https://jsfiddle.net/](https://jsfiddle.net/)
- O hacer fork y clonar este repositorio y resolverlo en Visual Studio Code

### Descripción
Deberás crear una interfaz como se muestra en la pantalla 1 del siguiente prototipo:
- [https://www.figma.com/file/kwKwQk0vEeDyRLmZi78FHH/Toy-Story-%2F-Naramarilla-Software?node-id=0%3A1&t=bnzAOb855n1hRFQ9-1](https://www.figma.com/file/kwKwQk0vEeDyRLmZi78FHH/Toy-Story-%2F-Naramarilla-Software?node-id=0%3A1&t=bnzAOb855n1hRFQ9-1)

### Challenge
Si terminaste la primera parte, deberas implementar la segunda pantalla del prototipo ( en donde se encuentra el botón amarillo)

- Al dar click en el botón `CHANGE POSITION` se deberá cambiar la posición de los personajes, los de la izquierda a la derecha y viceversa

### Listado de juguetes

```js
const toys = [
        {
            "name": "Woody" ,
            "isVillain": false,
            "imageUrl": "https://static.wikia.nocookie.net/disney/images/a/ab/Woody_4.png/revision/latest?cb=20161125135228&path-prefix=es" 
        },
        {
            "name": "Slinky" ,
            "isVillain": false,
            "imageUrl": "https://static.wikia.nocookie.net/toy-story/images/5/56/Slinky_dog.png/revision/latest/scale-to-width-down/252?cb=20141230153751&path-prefix=es"
        },
        {
            "name": "Sargento",
            "isVillain": false,
            "imageUrl": "https://cutt.ly/E1oLOAS"
        },
        {
            "name": "Zurg" ,
            "isVillain": true,
            "imageUrl": "https://static.wikia.nocookie.net/toy-story/images/3/35/Tumblr_static_zurg_%281%29.png/revision/latest?cb=20150121193343&path-prefix=es"
        },
        {
            "name": "Oloroso Pete" ,
            "isVillain": true,
            "imageUrl": "https://1.bp.blogspot.com/-PuqcdRTr_Oc/YFIVbg6WzqI/AAAAAAAAjiw/cOGPA7Q2-7wDcQpqfTTM8qqe0aQUA6B6ACNcBGAsYHQ/s2048/mattel-stinky-pete-figure.jpg"
        },
        {
            "name": "Lotso" ,
            "isVillain": true,
            "imageUrl": "https://i.pinimg.com/originals/31/78/a7/3178a7c81361f71a3e6dc2594f67a641.jpg"
        }
  ];
```