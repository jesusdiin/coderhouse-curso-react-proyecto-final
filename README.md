# Proyecto Final del Curso de [React en CoderHouse](https://coderhouse.com.mx/collections/categoria-programacion-y-desarrollo/products/reactjs)

<h2 style='text-align: center;'>
	Hola a todos! <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Waving%20Hand.png" alt="Waving Hand" width="25" height="25" />
	<br> Bienvenid@s al Repositorio de mi proyecto final
</h2>

<p style='text-align:center'> <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Green%20Circle.png" alt="Green Circle" width="13" height="13" /> <b>Estado:</b> Primera pre-entrega</p>

<div>
	<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Thinking%20Face.png" alt="Thinking Face" width="25" height="25" style="float:left; margin-right:10px;">
	<details>
		<summary >
			<b>¿Que es Coder House?</b>
		</summary>
		<em>
			<br>
			<a href='https://coderhouse.com.mx/'>Coder House</a> es una escuela de habilidades digitales, con clases online en vivo.
			<br><br>
			Coderhouse tiene cursos y carreras online de diseño ux, community manager, publicidad en redes, programación, ecommerce, data analytics y más.
			<br><br>
			Las clases son virtuales, pero igualmente quedan grabadas en su plataforma virtual.
			Las clases están dictadas por profesores que trabajan en las mejores empresas de Latinoamérica.
			<br>
			Los alumnos son acompañados por tutores, quienes resuelven sus dudas y los ayudan a completar el proyecto final de la mejor manera.
		</em>
	</details>
		<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Atom%20Symbol.png" alt="Atom Symbol" width="25" height="25" height="20" style="float:left; margin-right:10px;"/>
		<details>
			<summary>
				<b>¿Por que un curso de React?</b>
			</summary>
			<br>
			<em>React es una biblioteca Javascript de código abierto diseñada para crear interfaces de usuario.
			<br><br>
			Actualmente es de las bibliotecas con mayor demanda dentro de la industria
			<br><br>
			En el <a href='https://www.talent-land.mx/'>Talent Land 2023</a> me obsequiaron el curso de React en la plataforma <a href='https://coderhouse.com.mx/'>Coder House</a>, así que estamos aprovecahando para reforzar nuestras habilidades en React
			</em>
		</details>
</div>

<h2 style='text-align: center;'><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Memo.png" alt="Memo" width="25" height="25" /> Documentación</h2>


### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Scroll.png" alt="Scroll" width="25" height="25" /> Requerimientos Generales
Desarrollar una app de un e-commerce para poder vender productos de un rubro
a elección.

-	Un usuario debe poder ingresar, navegar por los productos e ir a sus detalles.
- Desde el detalle se debe poder ver la descripción, foto y precio e ingresarlo al carrito.
- Una vez que el carrito tenga al menos un producto, se deberá visualizar un listado compacto de la orden con el precio total.
- Al ingresar su nombre, apellido, teléfono e e-mail (ingresándolo dos veces para corroborar que sea correcto), debe activarse el botón de ‘realizar compra’.
- Al clickear ‘realizar compra’ debe guardarse en la base de datos una orden que tenga todos los productos, la fecha y dar feedback del número de orden.

### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Spiral%20Calendar.png" alt="Spiral Calendar" width="25" height="25" /> Primera Pre-entrega

1. Crea una carpeta dentro de src llamada components que contenga la implementación del componente NavBar dentro del archivo `NavBar.js`. Su funcionalidad es la de renderizar una barra de menú (Navbar).
2. Crea un componente CartWidget con un ícono y una notificación mostrando un número hardcodeado (fijo). Este servirá luego para indicar la cantidad de elementos que tenemos en el carrito, pero por ahora, mostrará un número hardcodeado (colocado en el código). Ubica este componente (CartWidget) dentro de Navbar.. Agrega algunos estilos con bootstrap/materialize u otro.
3. Crea un componente contenedor `ItemListContainer.js` con una prop greeting, y muestra el mensaje dentro del contenedor con el styling integrado

### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" alt="Hammer and Wrench" width="25" height="25" /> Herramientas utilizadas
![Tools](https://skillicons.dev/icons?i=react,vite,js,html,css,tailwind,git,github)

### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Check%20Mark%20Button.png" alt="Check Mark Button" width="25" height="21" /> Clona e Instala el Repositorio
Utiliza este comando para clonar el repositorio del proyecto

```bash
git clone git@github.com:jesusdiin/proyecto-final-coderhosue-curso-react.git
```
Abre la carpeta clonada e instala las dependecias necesarias con
```bash
npm i
```
Corre el proyecto en modo desarrollo usando
```bash
npm run dev
```