# Shopifybase

Este es un Dev Container para el desarrollo de temas en Shopify.

## Pasos para comenzar

1. **Creaun nuevo repositorio a partir de la plantilla de este.**
   Para hacer esto, haz clic en el botón "Use this template" en la parte superior derecha de la página del repositorio, y selecciona "Create new repository"

2. **Clona el repositorio en tu disco.**
   Puedes hacer esto con el comando `git clone`.

3. **Abre el repositorio con Visual Studio Code en un Dev Container.**
   Para hacer esto, selecciona "Reopen in Container" en la notificación de VS Code o usa el comando "Remote-Containers: Reopen in Container" desde la paleta de comandos (F1).

4. **Verifica si tienes instalada la última versión del CLI de Shopify.**
   Para hacer esto, ejecuta el siguiente comando en la terminal:
   ```bash
   shopify version
   
5. **Si la versión del CLI de Shopify está obsoleta, actualízala.**
   Para hacer esto, ejecuta el siguiente comando en la terminal:
   ```bash
   npm install @shopify/cli -g

 6. **Ejecuta el comando de Shopify CLI para descargar el repositorio del tema Dawn y dale un nombre.**
   Para hacer esto, ejecuta el siguiente comando en la terminal:
	```bash
    shopify theme init

 7. **Mueve todos los archivos que hay dentro de la carpeta recien creada al directorio raiz.**

 8. **Elimina la carpeta vacia.**

 9. **Haz un commit en el repositorio con los nuevos archivos del tema descargados.**
   Asegurate de tener configurados tu nombre y correo en git:
   	```bash
	   git config --global user.name <tu nombre>
	   git config --global user.email <you@example.com>

8. **Deslogate de shopify**
      ```bash
   shopify auth logout
   
10. **Conecta el entorno a la tienda se shopify par poder ver los cambios en local**
```bash
   shopify theme dev --store=<dirección url de la tienda sin http://>
