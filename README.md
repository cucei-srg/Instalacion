# :octocat: CuceiSRG Proyecto Modular - Sistema de Reportes Generales Repositorio :octocat:

### Configuración entorno para el desarrollo del proyecto:

__Instalar Git__
- __[Descargar Git](https://git-scm.com/downloads)__ -Descargar e instalarlo.

__Instalar NodeJS__
- __[Descargar NodeJS](https://nodejs.org/es/)__ -Descargar e instalar la versión 10.15.0 o inferior.

### Configuración de Git:
```
Abrir el CMD y escribir los siguientes comandos:
git config --global user.name "TU NOMBRE"
git config --global user.email "TU EMAIL"
```

__Instalación de un editor de texto__
- __[Descargar Atom](https://atom.io/)__ -Descargar Atom.
- __[Descargar Visual Studio Code](https://code.visualstudio.com/)__ -Descargar VS Code.
> No importa cual se elije, los dos sirven para lo mismo.

### Instalación de los frameworks a utilizar APLICACIÓN MÓVIL ÚNICAMENTE:
En este paso se debe abrir __Como modo administrador__ el CMD para que permita la instalación.

### 1.- ANGULAR CLI:
`npm install -g @angular/cli`

### 2.- TYPESCRIPT:
`npm install -g typescript`

### 3.- IONIC:
`npm install -g ionic`

#### Instalación y Configuracion Symfony Framework para la Base de Datos
Primeramente tener instalado XAMPP con la version de PHP __versión 7.2 (NO VERSION 7.3)__.
Ejecutar el cmd __Como modo administrador__ y dirigirse a la ruta: `C:\xampp\php` para ejecutar los siguientes comandos:
- `php -r "file_put_contents('symfony', file_get_contents('https://symfony.com/installer'));"`
- `(echo @ECHO OFF & echo php "%~dp0symfony" %*) > symfony.bat`
- `symfony`

Al haber ejecutado estos comandos __uno por uno__ ahora, se instalará Composer (Manejador de dependencias de PHP) del siguiente enlace: https://getcomposer.org/Composer-Setup.exe
Al instalar, en un CMD se dirige hacia el directorio de AdminModulosCucei en donde se haya guardado en el computador y ejecutar la sig. Sentencia: __composer install__
Al finalizar le pedirá distintos datos, solo presione enter para omitirlos y que esten por defecto las configuraciones,solamente modificar cuando pida el nombre de la BD siendo: __cuceisrgdb__.

### Creando la BD
En el mismo CMD teniendo el XAMPP activado el APACHE Y MYSQL ejecutar las siguientes 2 sentencias:
- `php app/console doctrine:database:create` Para crear la Base de Datos.
- `php app/console doctrine:schema:update --force` Para crear las tablas.

__NOTA: En dado caso que mande mensaje de que no reconozca php solo agreguen php a las variables del entorno__

Simplemente es agregar datos genéricos en las tablas (Preguntar cuales tablas son para no hacer tan grande este documento y que datos son).

### Usar el Dashboard
Para ingresar al sistema CUCEI-SRG se debe tener un correo gmail y registrarse en el Sistema, donde al momento de registrarse les pedirá verificar su cuenta para ingresar en ella.

__Documentacion sobre cada Framework y lenguajes a utilizar__
- __[Documentacion de Angular](https://angular.io/docs)__
- __[Documentacion de Ionic](https://ionicframework.com/docs/)__
- __[Documentacion de TypeScript](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)__
- __[Documentacion de JavaScript](https://www.w3schools.com/jS/default.asp)__
- __[Documentacion de jQuery](https://www.w3schools.com/jquery/default.asp)__
- __[Documentacion de Bootstrap 4](https://www.w3schools.com/bootstrap4/)__
- __[Documentacion de CSS](https://www.w3schools.com/css/default.asp)__
- __[Documentacion de HTML](https://www.w3schools.com/html/default.asp)__

# Manual de Uso de Git y GitHub.
- __[Manual de Uso de Git](https://git-scm.com/book/es/v1/Empezando)__ -Manual Git.
```
Sobre Git tomen en cuenta saber:
+ Empezando ( Manual desde el punto 1 al 7)
+ Fundamentos de Git (Manual desde el punto 1 al 8)
+ Git en entornos distribuidos (Manual desde el punto 1 al 4)
```
- __[Manual de Uso de GitHub](https://guides.github.com/)__ -Manual GitHub.
```
Sobre GitHub tomen en cuenta Hacer:
+ Understanding the GitHub Flow
+ Hello World
+ Forking Projects
+ Mastering Issues
+ Mastering Markdown
```
                    SERVIDOR CTA
root:  eSd+T2a4
usuario: +VY6Ksf!
                          MySQL
Password Root: mRdK95!+
                          INGRESO
mysql -u root -p

   FORTICLIENT

IP: 148.202.253.30
User: Miguel_Angel
Password: Segur1dad2018

__-Actualización:20/05/2020-__
