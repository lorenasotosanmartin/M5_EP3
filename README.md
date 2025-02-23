# Aprendizaje Basado en Proyectos: Uso de Hooks y Manejo de Errores en la Web del Hospital
## Descripción
En este proyecto, se implementan Hooks para la gestión de estado y efectos secundarios, además de manejar errores y excepciones dentro del sistema del hospital.
 ### Uso de useState para la Gestión de Estado
 A lo largo del proyecto, especificamente en sus componentes, se utiliza useState para gestionar los estados en el componente del sistema, un ejemplo de su uso es el formulario de registro de citas, disponible en la seccion del administrador.
Para acceder a las sección adminsitrador, los datos de accesos son los siguientes:
  - user: administrador, password: admin123!
 
 ### Uso de useEffect para la Gestión de Efectos Secundarios
 Para realizar las diferentes peticiones realizadas a la API y obtener los datos del sistema del hospital se utiliza useEffect opara manejar los egectos secundarios y controlar cuando y como se ejecutan ciertos procesos.
 ### Manejo de errores en la aplicación
 Para manejar errores asincronos en la aplicación se utiliza el mecanismo try-catch en gran parte de sus funcionalidades.

### Aplicación Correcta de las Reglas de los Hooks
Durante el desarrollo de esta aplicación se asegura un correcto uso de la regla de hooks, verificando que las llamadas no se utilizen en ciclos o de manera condicional y/o se realizan en el nivel superior del componente.

 ### Visualización del proyecto
Para visualizar este proyecto se necesita que previamente cuentes con la instalación de:
- **Git**: [sitio de descarga] (https://git-scm.com/downloads)
- **Node.js**: [sitio de descarga] (https://nodejs.org/en/download/package-manager)
- **Visual Studio Code**: [sitio de descarga] (https://code.visualstudio.com/download)
  
Una vez que ya cuentes con lo descrito anteriormente, debes clonar este repositorio en una carpeta local, mediante el siguiente comando:
```bash
git clone https://github.com/lorenasotosanmartin/M5_EP2.git
```
cuando ya este clonado, escribir el siguiente comando en la consola: 
```bash
npm  i
```
y ejecutar el comando, para inicializar el proyecto: 
```bash
npm run dev
```
Finalmente, para visualizar el proyecto en tu navegador debes abrir la url http://localhost:3000/ 
