# 1-Intro

## 1-Intro/-Styling_a_biography_page
[Requisites](https://developer.mozilla.org/es/docs/Learn/CSS/First_steps/Styling_a_biography_page)
Usa CSS para cambiar el aspecto de la biografía, cambiando los valores de las propiedades iniciales.

* Coloca en rosado el nivel \<h1>, usando el color CSS hotpink.
* Da al encabezado un border-bottom de 10px con puntos (dotted), que use el color CSS purple.
* Coloca en cursiva el \<h2>.
* Al ul utilizado para los detalles de contacto un background-color #eeeeee, 
y un border de 5px solid purple. Usa algo de padding para empujar el texto lejos del borde.
* Cambia los enlaces a verde cuando pase el cursor sobre ellos.

- Propiedades que se pueden usar:
  - color
  - border-bottom
  - font-style
  - background-color
  - border 
  - padding

  - font-family
  - font-weight
  - font-size
  - text-decoration

- [html](../1-MDN/1-Intro/1-Biography/index.html)
- [css](../1-MDN/1-Intro/1-Biography/style.css)

# 2-Selectors

## 2-Selectors/1-tipo
[Requisites](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Selectors_Tasks#task_1)
- Dado un html:
  1. poner el texto de h1 en azul
  2. poner el fondo de h2 en azul y el texto en blanco
  3. poner un tamaño de letra del 200% en los span

- [html](../1-MDN/2-Selectors/1-Type/index.html)
- [css](../1-MDN/2-Selectors/1-Type/style.css)

## 2-Selectors/2- clase e id
[Requisites](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Selectors_Tasks#task_2)
- Dado un html:
  1. el elemento con id special -> color de fondo amarillo
  2. elementos con clase alert -> borde gris de 1px
  3. elemtos con clase alert y stop -> fondo rojo
  4. elemtos con clase alert y go -> fondo verde

- [html](../1-MDN/2-Selectors/2-Class_Id/index.html)
- [css](../1-MDN/2-Selectors/2-Class_Id/style.css)

## 2-Selectors/3- pseudo
[Requisites](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Selectors_Tasks#task_3)
- Dado un html:
  1. los links: no visitados color naranja, cuando visitados en verde, eliminar subrayado cuando el usuario interactua (hover)
  2. primer elemento dentro del 'container' con tamaño de fuente 150% y su primera línia de color rojo. 
  3. alternar las filas de la tabla, y estilar {las pares} con fondo casi negro #333 y color de texto blanco {y sin separación entre celdas}

- [html](../1-MDN/2-Selectors/3-pseudo/index.html)
- [css](../1-MDN/2-Selectors/3-pseudo/style.css)

## 2-Selectors/4- relaciones de parentesco
[Requisites](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Selectors_Tasks#task_4)
- Dado un html:
  1. poner en rojo los paragrafos que sean primer hermanos de h2
  2. eliminar bullets y poner un borde inferior de 1px gris, solo en los items de lista que són hijos (1er grado, no descendientes) de un ul que tiene la clase list.

- [html](../1-MDN/2-Selectors/4-relateds/index.html)
- [css](../1-MDN/2-Selectors/4-relateds/style.css)

## 2-Selectors/4- atributos
[Requisites](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Selectors_Tasks#task_5)
- Dado un html y algo de css ya hecho:
  1. Poner los \<a> que tengan un atributo title con borde rojo.
  2. Poner los \<a> que tengan el atributo href cuyo valor contenga la cadena contact en alguna parte con borde naranja.
  2. Poner los \<a> que tengan el atributo href cuyo valor empieze con la cadena https con borde verde.

- [html](../1-MDN/2-Selectors/5-atributtes/index.html)
- [css](../1-MDN/2-Selectors/5-atributtes/style.css)