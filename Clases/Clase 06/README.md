Para que Github muestre código en su formato debemos usar las comillas invertidas ```

``` Processing ```
```
// Click within the image and press
// the left and right mouse buttons to 
// change the value of the rectangle

void draw() {
  if (mousePressed && (mouseButton == LEFT)) {
    fill(0);
  } else if (mousePressed && (mouseButton == RIGHT)) {
    fill(255);
  } else {
    fill(126);
  }
  rect(25, 25, 50, 50);
}
```

Apuntes:
Curso de objeto es una caja de herramientas, repaso del marco conceptual de la clase: ¿qué es un objeto?
Todo objeto tiene composición (de lo que está hecho) y relación (para qué es), la idea de la tercera mesa propone que existe un tercer aspecto; la esencia. Humanidades = relación, Ciencias = composición, Arte y Filosofía = esencia.
la afectación (relación entre objetos) ocurre a través de las cualidades, que pueden cambiar a través del tiempo y son determinadas por sus circunstancias. Se puede realizar una operación reflexiva desde el arte y la filosofía para aproximarse a la esencia de los objetos; la metáfora (combinar las cualidades no esenciales de elementos disímiles), por ejemplo como dice Nicanor Parra " a los zapatos se les debería llamar ataúdes de pies", trae a la mente la imagen de un "ataúd-zapato" que combina cualidades de ambos objetos para crear algo nuevo.