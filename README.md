![css](https://lineadecodigo.com/wp-content/uploads/2014/04/css.png)
# css
lenguaje de diseño gráfico para definir y crear la presentación de un documento estructurado escrito en un lenguaje de marcado.​ 

* [Specificity graph](https://jonassebastianohlsson.com/specificity-graph/)
* [Normalize (Es importante ponerlo por encima)](https://necolas.github.io/normalize.css/)
* [Autoprefixer](https://autoprefixer.github.io/)
* [Prepros (sudo dpkg -i Prepros-7.3.48.deb)](https://prepros.io/)
* [10 amazing effects](https://www.codesdope.com/blog/article/10-amazing-effects-you-can-create-using-box-shadow/)
* [Animaciones y formas](https://bennettfeely.com/)
* []()
* []()
* []()
* []()
* []()
* []()
* []()
* []()

### Ordenar las propiedades es importante, no existe ninguna norma ni especificación sobre como hacerlo, pero la mayoría de expertos coninciden en los mismos puntos.  

1- Propiedades de posicionamiento  
2- Propiedades del box model  
3- Propiedades texto  
4- Propiedades visuales (colores, bordes, background, ...)  
5- El resto  

```
body {
  /*Position*/
  position: relative;
  top: 0;
  left: 0;

  /*Box model*/
  display: block;
  width: 300px;
  height: 600px;
  padding: 10px;
  margin: 10px;
  overflow: hidden;

  /*Texto*/
  font-size: 16px;
  text-align: center;

  /*Visual*/
  color: blue;
  border: 2px solid red;
  border-radius: 20px;
  
  /* Varios */
  opacity: 1;

}

```  

