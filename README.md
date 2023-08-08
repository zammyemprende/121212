# Angular CRUD By [Sotobotero](https://sotobotero.com)

**Content**   
1. [Como contribuir con este proyecto](#como-contribuir-con-este-proyecto)
2. [Como empezar a usar la aplicación](#como-empezar)
3. [How contribute to this project](#how-contribute-to-this-project)
4. [Getting Started](#getting-started)

## Como contribuir con este proyecto. 
1. Primero, necesitas hacer un fork del repositorio al que deseas contribuir. Esto creará una copia del repositorio en tu cuenta de GitHub. Puedes hacer un fork de un repositorio haciendo clic en el botón "Fork" en la esquina superior derecha de la página del repositorio. 

2. A continuación, necesitas clonar tu repositorio bifurcado en tu máquina local. Esto te permitirá trabajar en los archivos del proyecto sin conexión. Puedes clonar tu repositorio bifurcado utilizando el comando git clone con la URL de tu bifurcación.

3. Después de clonar tu repositorio bifurcado, necesitas crear una rama para trabajar en tus cambios. Una rama es una versión separada del código que puedes modificar sin afectar la rama principal. Puedes crear una rama utilizando el comando git branch con el nombre de tu rama.

4. Una vez que hayas creado una rama, necesitas cambiar a ella utilizando el comando git checkout con el nombre de tu rama. Esto hará que tu rama sea la activa y cualquier cambio que hagas se aplicará a ella. 

5. Ahora puedes empezar a trabajar en tus cambios. Puedes editar, agregar o eliminar cualquier archivo en tu rama como desees. Puedes utilizar cualquier editor de código o IDE que prefieras. 

6. Después de hacer tus cambios, necesitas hacer commit de ellos en tu rama. 

7. A continuación, necesitas enviar tus cambios a tu repositorio bifurcado en GitHub. Esto subirá tu rama y sus commits a tu repositorio en línea. Puedes enviar tus cambios utilizando el comando git push con el nombre de tu remoto (normalmente origin) y el nombre de tu rama.

8. Por último, necesitas crear una solicitud de extracción (pull request) desde tu rama al repositorio original del que hiciste la bifurcación. Una solicitud de extracción es una solicitud para que los mantenedores del repositorio original revisen y fusionen tus cambios en su rama principal. Puedes crear una solicitud de extracción haciendo clic en el botón "Pull Request" en la página de tu repositorio bifurcado en GitHub. 
## Como empezar
### Requisitos
1. Instalar [Node.js LTS](https://nodejs.org/es/) (v18.16.0) o superior y [Angular CLI](https://cli.angular.io/) (v13) o superior.
2. Opcional: Clonar e iniciarlizar el backend de la aplicación [customer-back](https://github.com/sotobotero/customer-back), si no se tiene el backend, la aplicación solo cargrá el front pero no tendra conexión a un back.
### Instalación
1. Clonar el repositorio
2. Entrar a la carpeta del proyecto
3. Instalar los paquetes de npm con el comando `npm install`.
4. Ejecutar el comando `ng serve --configuration=production` para un servidor de desarrollo. Navegar a `http://localhost:4200/customers`. 
La aplicación se recargará automáticamente si se cambia alguno de los archivos de origen.


## How contribute to this project. 
1. First, you need to fork the repository that you want to contribute to. This will create a copy of the repository under your own GitHub account. You can fork a repository by clicking the Fork button on the top right corner of the repository page.

2. Next, you need to clone your forked repository to your local machine. This will allow you to work on the project files offline. You can clone your forked repository by using the git clone command with the URL of your fork. 

3. After cloning your forked repository, you need to create a branch to work on your changes. A branch is a separate version of the code that you can modify without affecting the main branch. You can create a branch by using the git branch command with the name of your branch. 

4. Once you have created a branch, you need to switch to it by using the git checkout command with the name of your branch. This will make your branch the active one and any changes you make will be applied to it.

5. Now you can start working on your changes. You can edit, add, or delete any files in your branch as you wish. You can use any code editor or IDE that you prefer. 

6. After making your changes, you need to commit them to your branch. A commit is a snapshot of your changes that records what you have done and why. You can commit your changes by using the git commit command with a message that describes your changes. 

7. Next, you need to push your changes to your forked repository on GitHub. This will upload your branch and its commits to your online repository. You can push your changes by using the git push command with the name of your remote (usually origin) and the name of your branch. 

8. Finally, you need to create a pull request from your branch to the original repository that you forked from. A pull request is a request for the maintainers of the original repository to review and merge your changes into their main branch. You can create a pull request by clicking the Pull Request button on your forked repository page on GitHub.

## Getting Started

## Requirements
1. Install Node.js LTS (v18.16.0) or later and Angular CLI (v13) or later.
2. Optional: Clone and start the backend of the [customer-back](https://github.com / sotobotero / customer-back) application, if you don't have the backend, the application will only load the front but will have no connection to a backend.


## Installation
1. Clone the repository
2. Enter the project folder
3. Install npm packages with the command npm install.
4. Run the command ng serve --configuration=production for a development server. Navigate to http://localhost:4200/customers.
The application will reload automatically if any of the source files are changed.


## Angular 2+ - Environment Variables
Due to this app are execute on web browser, you can't use environment variables on environments/environment.ts, becuase this file are execute on server side, and enviroment variables are not available on server side.

If you want to use environment variables on environments/environment.prod.ts, you need to change the aporach for use dotenv lib and  dotenv-webpack plugin for webpack. 