References Storyboards
========

### Desde Xcode

<p align="justify">
	Cuando tenemos un proyecto tenemos muchas secciones como: login, menu, settings, perfil, home, etc. por lo que si queremos que otros equipos trabajen en una sección debemos dividir las vistas, para eso nos sirven las <i>Referencias</i> aparte de que mantiene nuestro código mejor ordenado. 
</p>

<p align="justify">
	En este proyecto tenemos: Login, Menu, y Settings y queremos separar lo para que otros equipos puedan trabajar.
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img1.png" width="1280" height="550">
</p>

<p align="justify">
	Seleccionamos la sección
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img2.png" width="1280" height="550">
</p>

<p align="justify">
	Le damos en Refactorizar
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img3.png" width="1280" height="550">
</p>

<p align="justify">
	Creamos un nuevo Storyboards, en mi caso le pondre el nombre de la sección Menú
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img4.png" width="1280" height="550">
</p>

<p align="justify">
	Nos moverá nuestros ViewControllers dentro del nuevo Storyboards
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img5.png" width="1280" height="550">
</p>

<p align="justify">
	Si regresamos a Main Storyboards podremos ver que nos creó una referencía a Menú Storyboards
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img6.png" width="1280" height="550">
</p>

<p align="justify">
	Lo mismo hacemos con la sección Settings
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img7.png" width="1280" height="550">
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img8.png" width="1280" height="550">
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img9.png" width="1280" height="550">
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img10.png" width="1280" height="550">
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img11.png" width="1280" height="550">
</p>

## Manual 

<p align="justify">
	Si nos fijamos en nuestra <i>Librería de Objetos</i> veremos el objeto <b>Srotyboard Reference</b> ¡usemos lo!	
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img12.png" width="1280" height="550">
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img13.png" width="1280" height="550">
</p>

<p align="justify">
	Agregamos un segundo Storyboards
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img14.png" width="1280" height="550">
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img15.png" width="1280" height="550">
</p>

<p align="justify">
	Nuestro Second Storyboards no contiene ningun ViewController, agreguemosle un par
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img16.png" width="1280" height="550">
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img17.png" width="1280" height="550">
</p>

<p align="justify">
	Regresamos a Main Storyboards
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img18.png" width="1280" height="550">
</p>

<p align="justify">
	Ligamos nuestro ViewController a la <i>Referencia</i>
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img19.png" width="1280" height="550">
</p>

<p align="justify">
	Seleccionamos Show
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img20.png" width="1280" height="550">
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img21.png" width="1280" height="550">
</p>

<p align="justify">
	Para asignarle un Storyboards lo seleccionamos y modificamos sus atributos desde el inspector
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img22.png" width="1280" height="550">
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img23.png" width="1280" height="550">
</p>

<p align="justify">
	Si construimos el proyecto fallará
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img24.png" width="1280" height="550">
</p>

<p align="justify">
	Nos marca que Second Storyboards no sabe, con que ViewController iniciar
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img25.png" width="1280" height="550">
</p>

<p align="justify">
	Nos regresamos a Secondstoryboards 
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img26.png" width="1280" height="550">
</p>

<p align="justify">
	Seleccionamos nuestro ViewController A y desde el Inspector le ponemos: <i>is initial ViewController</i>
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img27.png" width="1280" height="550">
</p>

<p align="justify">
	Volvemos a compilar
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img28.png" width="1280" height="550">
</p>

<p align="justify">
	Éxito
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img29.png" width="1280" height="550">
</p>

<p align="justify">
	Podemos regresarnos a Main Storyboards y trabajar allí, si queremos ir a Second storyboards bastará con clickear la <i>Referencia</i> para ir a Second Storyboards
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img30.png" width="1280" height="550">
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img31.png" width="1280" height="550">
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img32.png" width="1280" height="550">
</p>

<p align="justify">
	Para movernos desde código podemos checar el siguiente <a href="https://github.com/ginppian/Move-Between-Many-Storyboards">tutorial</a>.
</p>

## Corriendo el Proyecto desde un Storyboards Especifico

<p align="justify">
	Con un sólo clic en el Nombre del Proyecto nos vamos a la configuración General
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img39.png" width="1280" height="550">
</p>

<p align="justify">
	Podremos ver todos los Storyboards
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img40.png" width="1280" height="550">
</p>

<p align="justify">
	Seleccionamos Second Storyboards
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img41.png" width="1280" height="550">
</p>

<p align="justify">
	Si corremos el App nos marcará un error porque no tenemos un <i>ViewController Inicial</i> asignado a nuestro Storyboards
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img42.png" width="1280" height="550">
</p>

<p align="justify">
	Nos regresamos y ponemos nuestro Storyboards B como <i>Initial ViewController</i>
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img43.png" width="1280" height="550">
</p>

<p align="justify">
	Corremos el proyecto y todo irá bien!!! =D
</p>

<p align="center">
	<img src="https://github.com/ginppian/Storyboards-Reference/blob/master/imgs/img44.png" width="1280" height="550">
</p>

## Fuente

* <a href="https://www.youtube.com/watch?v=PRXjmuRYQdY">How to Use Storyboard References to Boost Workflow</a>

* <a href="https://useyourloaf.com/blog/refactoring-with-storyboard-references/">Refactoring with Storyboard References</a>


