# Project_3
# Project 3: Spots

### Overview  

* Intro  
* Figma  
* Images  
  
**Intro**
  
This project is made so all the elements are displayed correctly on popular screen sizes. We recommend investing more time in completing this project, since it's more difficult than previous ones.  
  
**Figma**  
  
* [Link to the project on Figma](https://www.figma.com/file/BBNm2bC3lj8QQMHlnqRsga/Sprint-3-Project-%E2%80%94-Spots?type=design&node-id=2%3A60&mode=design&t=afgNFybdorZO6cQo-1)
  
**Images**  
  
The way you'll do this at work is by exporting images directly from Figma — we recommend doing that to practice more. Don't forget to optimize them [here](https://tinypng.com/), so your project loads faster. 
Good luck and have fun!



## Diseño responsivo de las tarjetas

En el archivo `blocks/cards.css`, se utiliza la siguiente propiedad para el layout de las tarjetas:

```css
grid-template-columns: repeat(auto-fill, minmax(413px, 1fr));
```

**¿Qué hace esta línea?**

- Usa CSS Grid para crear tantas columnas como quepan en el contenedor.
- Cada columna tiene un ancho mínimo de 413px y puede expandirse hasta ocupar el espacio disponible.
- Esto permite que el número de columnas se adapte automáticamente al tamaño de la pantalla, haciendo el diseño responsivo.
- Si el espacio es insuficiente para otra columna de 413px, las columnas existentes se expanden para llenar el contenedor, evitando espacios vacíos.

Esta técnica asegura que las tarjetas se vean bien tanto en pantallas grandes como pequeñas, manteniendo un diseño flexible y moderno.


