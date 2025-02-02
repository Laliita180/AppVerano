AppVerano

AppVerano es una aplicación desarrollada en Angular que tiene como objetivo facilitar la comunicación de personas con dificultades en el habla. Utiliza una interfaz accesible con letras grandes, simbología y sonidos para mejorar la experiencia del usuario.

Requisitos previos

Antes de ejecutar la aplicación, asegúrate de tener instalados los siguientes requisitos:

Node.js (versión recomendada: 16 o superior)

Angular CLI (se puede instalar con npm install -g @angular/cli)

Instalación

Clona el repositorio y accede al directorio del proyecto:

git clone https://github.com/Laliita180/AppVerano.git
cd AppVerano

Instala las dependencias del proyecto:

npm install

Ejecución del proyecto

Para ejecutar la aplicación en modo de desarrollo, usa el siguiente comando:

ng serve

Luego, abre tu navegador y accede a http://localhost:4200/.

Subir README a GitHub

Para subir el README.md al repositorio, sigue estos pasos:

git add README.md
git commit -m "Agregando README.md con información del proyecto"
git push origin main

(Nota: Si la rama principal se llama master o develop, reemplaza main con el nombre correcto).

Estructura del proyecto

El proyecto sigue la estructura típica de Angular:

AppVerano/
│-- src/
│   │-- app/
│   │   │-- components/   # Componentes de la aplicación
│   │   │-- services/     # Servicios y lógica de negocio
│   │-- assets/          # Recursos estáticos
│   │-- index.html       # Archivo principal HTML
│   │-- main.ts          # Punto de entrada de la aplicación
│   │-- styles.scss      # Estilos globales
│-- angular.json        # Configuración de Angular
│-- package.json        # Dependencias del proyecto
│-- README.md           # Este archivo

Contribución

Si deseas contribuir al proyecto, sigue estos pasos:

Realiza un fork del repositorio.

Crea una nueva rama (git checkout -b feature-nueva).

Realiza tus cambios y haz un commit (git commit -m "Descripción del cambio").

Sube tus cambios (git push origin feature-nueva).

Abre un Pull Request en GitHub.

Licencia

Este proyecto está bajo la licencia MIT. Puedes ver más detalles en el archivo LICENSE.

¡Gracias por tu interés en AppVerano! 😊