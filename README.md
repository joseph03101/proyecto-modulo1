# Proyecto Módulo 1: Guía de Hoteles (Bootstrap 4, NPM, Grillas y Flexbox)

Este proyecto implementa todos los requisitos prácticos del **Módulo 1** y cumple con cada uno de los criterios de evaluación por pares.

---

## 1. Estructura del Proyecto

- [`.gitignore`](./.gitignore): Ignora el directorio `node_modules/` para evitar subir dependencias al repositorio Git/Bitbucket.
- [`package.json`](./package.json): Configuración NPM con las dependencias `bootstrap`, `jquery`, `popper.js` y la dependencia de desarrollo `lite-server`, incluyendo el script `"dev": "lite-server"`.
- [`index.html`](./index.html): Página principal responsiva con Jumbotron, contenedor con 3 bloques de características, listado de productos con sistema de grillas transformado a Flexbox y pie de página (`footer`) con etiqueta `<address>` y alineación izquierda, centro y derecha.
- [`css/main.css`](./css/main.css): Hoja de estilos personalizada con clases replicables (`.card-hotel`, `.btn-reserva`, `.jumbotron`, `footer`).

---

## 2. Ejecución con NPM y `lite-server`

1. Instalar las dependencias definidas en `package.json`:
   ```bash
   npm install
   ```
2. Iniciar el servidor de desarrollo `lite-server`:
   ```bash
   npm run dev
   ```

---

## 3. Configuración del Repositorio con Git y Bitbucket

Ejecuta los siguientes comandos en la terminal dentro de la carpeta del proyecto para inicializar tu repositorio local y subirlo a **Bitbucket**:

```bash
# 1. Inicializar el repositorio Git
git init

# 2. Verificar que node_modules sea ignorado gracias a .gitignore
git status

# 3. Agregar los archivos del proyecto al área de staging
git add .

# 4. Realizar el primer commit
git commit -m "Implementación del Módulo 1: Sitio responsivo con Bootstrap 4, Flexbox y NPM"

# 5. Vincular con tu repositorio remoto en Bitbucket (reemplaza USUARIO y REPO)
git remote add origin https://bitbucket.org/USUARIO/guia-hoteles.git

# 6. Subir los cambios a la rama principal
git push -u origin master
```
