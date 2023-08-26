### ¿Qué es JSX?
Es una extensión de JavaScript la cual también se podría decir que es JavaScript + XML
### Node
*Entorno de desarrollo que permite utilizar JS de manera Nativa*

![[Pasted image 20230822124421.png]]
### Instalación de React
- npm: gestor de paquetes (Construye de manera diferente)
- npx: Ejecutor de paquetes (Optimiza)
- yarn: gestor de paquetes  {Instalación en consola: corepack enable}

-Comando para crear proyecto
```
 yarn create vite
 ```

> Estructuración de Carpetas

- Public: Son archivos estáticos {imágenes, documentos de Word, Excel, scripts que no reciban cambios}
- src (fuente): Todo lo que se valla a programar esta en esta carpeta, todo el código fuente
	* assets: son recursos
- .eslintrc.cjs: Programa que te ayuda a ver los errores de programación
- .gitignore: Configuración de git que nos ayudan a ignorar archivos o carpetas que no se utilizan 
- index.html: Archivo principal, es la entrada a la aplicación, todo lo que hagamos en la aplicación se va a renderizar dentro de 
```
<div id="root"></div>
```
- package.json: Este archivo son las dependencias que se utilizaran dentro del archivo
- README.md: 
- vite.config.js: archivo de configuración de como lo estamos instalando

> Para instalar las dependencias
~~~
yarn
~~~

#### Para ejecutar el proyecto
~~~
yarn dev
~~~

### Variables

- Regularmente se van a utilizar constantes por que así no v a mutar el tipo de dato
- let y var dependen del tipo de Scope
