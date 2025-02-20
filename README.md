Torres de Hanoi
Este proyecto es una implementación del clásico juego de las Torres de Hanoi, desarrollado en C# utilizando Windows Forms. El juego consiste en mover una serie de discos de diferentes tamaños entre tres varillas, siguiendo ciertas reglas.

Contenido del Repositorio
El repositorio contiene los siguientes archivos y carpetas:

.git/: Carpeta que contiene la información de control de versiones de Git.
App.config: Archivo de configuración de la aplicación.
Form1.Designer.cs: Archivo generado automáticamente que define la interfaz gráfica del formulario principal.
Form1.cs: Código detrás del formulario principal, que contiene la lógica del juego.
Form1.resx: Archivo de recursos para el formulario principal.
Palos.cs: Clase que representa los palos del juego.
Palos.resx: Archivo de recursos para la clase Palos.
Plato.cs: Clase que representa los discos del juego.
Program.cs: Punto de entrada de la aplicación.
Torre.cs: Clase que representa las torres que contienen los discos.
Torres de Hanoi.csproj: Archivo de proyecto de Visual Studio.
Torres de Hanoi.sln: Archivo de solución de Visual Studio.
Requisitos
.NET Framework 4.7.2 o superior.
Visual Studio (cualquier versión que soporte .NET Framework).
Instalación
Clona el repositorio en tu máquina local:

bash
Run
Copy code
git clone https://github.com/SF90STRADEl/proyecto-torres-de-hanoy.git
Abre el archivo Torres de Hanoi.sln en Visual Studio.

Compila y ejecuta el proyecto.

Cómo Jugar
Al iniciar la aplicación, verás un formulario con tres torres y discos apilados en la primera torre.
Haz clic en el botón "Resolver" para que el programa resuelva automáticamente el juego.
El objetivo es mover todos los discos a la tercera torre, siguiendo las reglas del juego:
Solo se puede mover un disco a la vez.
Un disco solo puede ser colocado en una torre si está vacío o si el disco en la parte superior es más grande que el disco que se está moviendo.
Contribuciones
Las contribuciones son bienvenidas. Si deseas contribuir, por favor sigue estos pasos:

Haz un fork del repositorio.
Crea una nueva rama (git checkout -b feature/nueva-caracteristica).
Realiza tus cambios y haz un commit (git commit -m 'Añadir nueva característica').
Haz push a la rama (git push origin feature/nueva-caracteristica).
Abre un Pull Request.
