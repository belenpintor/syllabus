# Tarea 02: DCCumbia:


## Consideraciones generales :octocat:

<Mi tarea está muy incompleta por obstáculos que me dejaron falta de tiempo, 
las clases se encuentran modeladas en sus funciones principales, sin embargo 
no todas está
<Mi tarea está muy incompleta por obstáculos que me dejaron falta de tiempo, y 
queda muy evidenciado en la tarea. 
Las clases se encuentran modeladas, sin embargo no todas se instancian y algunas 
se encuentran incompletas, como la de pinguinos. En el backend se encuentran las
clases creadas fuera de los menús. Lo principal que trabajé en el menú de juego 
fue la aparición y movimiento de las flechas. Hay funciones que están implementadas
pero no son visibles en el frontend, esto irá especificado con mayor detalle en 
los items de la pauta posterior. 


### Cosas implementadas y no implementadas :white_check_mark: :x:

* <<Ventana de inicio sub>1</sub>>: Hecha completa
* Vventana de ranking<sub>2</sub>>: Me faltó hacerla funcional  <insertar qué cosa faltó>
    * <Ventana se muestra correctamente<sub>2.1</sub>>: Lo visual esta hecho 
    * <Se muestra la cntidad correcta de puntaje <sub>2.2</sub>>: No lo hace 

* <Ventana de Juego<sub>2</sub>>: Me faltó hacerla funcional  <insertar qué cosa faltó>
    * <Generales<sub>2.1</sub>>: No se muestra el precio de los pinguinos
    * <Fase de pre-ronda <sub>2.2</sub>>: No se selecciona un pinguino, no se puede comprar pinguino, no tiene funcionalidad elección de niveles y canciones. 
    * <Fase ronda <sub>2.3</sub>>: De la dstribucó de puntae de esta sección, solo esta completo la marca de la zona de captura al apretar las letras. 
    * <Fase post ronda <sub>2.4</sub>>: Totalmente incompleta.
* <Mecánicas<sub>3</sub>>: Me faltó hacer <insertar qué cosa faltó>
   * <Pinguirin <sub>3.1 La clase solo se encuentra odelada en el codigo 
   * <Flechas <sub>3.2 Solo está implementada correctamente la flecha normal, la captura de flechas no funciona bien vsualmente, si se agregan a un cotador a nivel de código. 
* <Funcionalidades extras<sub>4</sub>>: No están implementadas
* ...
* <General<sub>5</sub>>: Me faltó agregar todos los parámetros pedidos, como parametrizar las rutas. 

## Ejecución :computer:
El módulo principal de la tarea a ejecutar es  ```main.py```. Además se debe crear los siguientes archivos y directorios adicionales:
1. ```backend.py``` en la carpeta que contenga main . ```T02```
2. ```frontend.py``` en ```T02```
3. ```parametros.py``` en ```T02```


## Librerías :books:
### Librerías externas utilizadas
La lista de librerías externas que utilicé fue la siguiente:

1. ```sys```: ```función() / random```
2. ```time```: ```función() time.sleep / módulo``` (debe instalarse)
3. ```PyQt5.Widgets```: ```funciónes QApplication, QWidget, QPushButton, QLabel, QLineEdit, QHBoxLayout, QVBoxLayout, QMessageBox```
4. ```PyQt5.QtGui```: ```QPixmap```
5. ```PyQt5.QtCore ```: ```función pyqtSignal ```


### Librerías propias
Por otro lado, los módulos que fueron creados fueron los siguientes:

1. ```fronted```: Contiene a ```Ventana_de_inicio```, ```Ventana_de_juego```, ```Ventana_de_ranking``` (Ventanas visuales diseñadas principalmente en qtdesigner con sus señales correspondientes que son conectadas en el main )...
2. ```backend```:  Contiene a ```Pinguino ```, ```Flechas1``` , ```AI```.
4. ```parametros```: Hecho para guardar parametros que serán utilizados en los distintos módulos y poder cambiarlos facilmente


## Referencias de código externo :book:

Para realizar mi tarea saqué código de:
1. Ayudantía 2020-1 syllabus para crear el ´Qthread llamada clase AI en el backend que guiaría el flujo del juego. se encuentra desde la linea 151
2. https://www.geeksforgeeks.org/pyqt5-how-to-change-background-color-of-main-window/ para cambiar los colores de lazoa de captura en el modulo fronted.py desde la linea 167 a 190.

## Descuentos
La guía de descuentos se encuentra [link](https://github.com/IIC2233/syllabus/blob/master/Tareas/Descuentos.md).
