## ANOTACIONES

### BACKEND

- **index.js**: *archivo principal del servidor*
- **database.js**: *archivo gestión conexión base de datos*
- npm init --yes *para inicializar package.json*
- npm install express *para instalar express dentro del proyecto*
- node server/index.js *para ejecutar el servidor directamente*
- process.env.PORT *para obtener puerto por defecto si existe*
- npm install nodemon -D *para instalar dependencia de desarrollo que reinicia el servidor tras realizar un cambio*
- npm run dev *para correr server con nodemon tras haber configurado script dev 'nodemon server/index.js'*
- npm install morgan *para instar dependencia que monstrará por consola las peticiones del usuario*
- npm install mongoose *para instalar dependencia que gestionará la conexión con MongoDB y que modelará los datos*

### FRONTEND

- npm install -g @angular/cli *para instalar herramienta de angular*
- ng new frontend *para generar proyecto*
- ng serve *para correr servidor angular despues de haber entrado en la carpeta*
- ng g c employees *para generar componente dentro de frontend/src/app/components*
- ng g class employee *para generar clase dentro de frontend/src/app/models*
- ng g s employee *para generar servicio dentro de frontend/src/app/services*
- **https://materializecss.com/**: *framework css*
- *Añadir CDN de materialize en index.html, iconos y todo lo que necesitemos*
- import { FormsModule } from '@angular/forms' *para formularios*