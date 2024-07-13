
# AluraFlix

AluraFlix es una aplicación web desarrollada en React que permite a los usuarios visualizar, agregar, eliminar, actualizar y editar videos. El proyecto está inspirado en plataformas de streaming de video y está diseñado para ser una herramienta de gestión de contenido simple y efectiva.

## Tabla de Contenidos

- [Instalación](#instalación)
- [Uso](#uso)
- [Características](#características)
- [Contribuciones](#contribuciones)


## Instalación

Para instalar y ejecutar el proyecto localmente, sigue estos pasos:

1. Clona el repositorio:
    ```sh
    git clone git@github.com:pedro-damian/AluraFlix.git
    ```
2. Navega al directorio del proyecto:
    ```sh
    cd AluraFlix
    ```
3. Instala las dependencias:
    ```sh
    npm install
    ```
4. Instala react-router-dom:
    ```sh
     npm i react-router-dom
    ```
5. Instala react-icons:
    ```sh
     npm install react-icons
    ```
6. Instala styled components:
    ```sh
      npm i styled-components
    ```
7. Instala json-server:
    ```sh
      npm install json-server
    ```
8. Inicia json-server:
    ```sh
      npx json-server --watch db.json --port 3000
    ```

9. Inicia la aplicación:
    ```sh
    npm run dev
    ```

## Uso

Una vez que la aplicación esté en funcionamiento, puedes:
- **Visualizar videos**: La página principal muestra una lista de videos disponibles.
- **Agregar videos**: Utiliza el formulario para agregar nuevos videos.
- **Editar videos**: Haz clic en el ícono de editar en cualquier video para modificar su información.
- **Eliminar videos**: Haz clic en el ícono de borrar en cualquier video para eliminarlo de la lista.

## Características

- **Visualización de Videos**: Muestra una lista de videos con su título y descripción.
- **Agregar Videos**: Permite añadir nuevos videos mediante un formulario.
- **Editar Videos**: Funcionalidad para modificar la información de videos existentes.
- **Eliminar Videos**: Posibilidad de borrar videos de la lista.
- **Interfaz Intuitiva**: UI sencilla y fácil de usar.

## Contribuciones

¡Las contribuciones son bienvenidas! Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Realiza un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añadir nueva funcionalidad'`).
4. Haz push a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

¡Gracias por usar AluraFlix! Si tienes alguna pregunta o sugerencia, no dudes en abrir un issue o enviar un pull request.