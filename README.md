
# Ahorros Inteligentes

Ahorros Inteligentes es una aplicación móvil desarrollada en **Ionic** que permite gestionar ingresos y egresos, proporcionando análisis y tips financieros para mejorar el ahorro, especialmente diseñada para menores de 18 años.

## Requisitos Previos

Antes de comenzar, asegúrate de tener instalado lo siguiente:

- **Node.js** (https://nodejs.org/)
- **Ionic CLI**:
  ```bash
  npm install -g @ionic/cli
  ```
- **Git** (https://git-scm.com/)

## Instrucciones para Clonar y Ejecutar el Proyecto

### 1. Hacer Fork del Repositorio
   Si eres un colaborador, haz un **fork** del repositorio original para trabajar en tu propio repositorio:

   1. Visita el repositorio principal en GitHub: [Ahorros Inteligentes](https://github.com/MiguelAdolfoV/Ahorros-Inteligentes).
   2. Haz clic en el botón **Fork** en la esquina superior derecha.
   3. Esto creará una copia del repositorio en tu cuenta de GitHub.

### 2. Clonar el Repositorio
   Clona tu fork del proyecto en tu máquina local:

   ```bash
   git clone https://github.com/tu-usuario/Ahorros-Inteligentes.git
   ```

   Luego, entra en el directorio del proyecto:
   ```bash
   cd Ahorros-Inteligentes
   ```

### 3. Instalar las Dependencias
   Instala las dependencias de npm necesarias para ejecutar el proyecto:

   ```bash
   npm install
   ```

### 4. Sincronizar Ionic con Capacitor
   Asegúrate de que la aplicación esté sincronizada con las plataformas nativas (Android o iOS):

   ```bash
   ionic capacitor sync
   ```

### 5. Ejecutar la Aplicación en el Navegador
   Para desarrollo rápido, puedes correr la aplicación en el navegador:

   ```bash
   ionic serve
   ```

   Esto abrirá la aplicación en tu navegador predeterminado.

## Colaboración y Contribución (agregar código)

### 1. Crear una Nueva Rama para tus Cambios
   Crea una rama nueva para trabajar en tu feature o corrección de bugs:

   ```bash
   git checkout -b nombre-de-tu-rama
   ```

### 2. Realizar Cambios y Cometerlos
   Asegúrate de realizar tus cambios y guardarlos correctamente en tu repositorio local:

   ```bash
   git add .
   git commit -m "Descripción de los cambios"
   ```

### 3. Sincronizar con el Repositorio Principal (Opcional)
   Si el proyecto principal ha avanzado mientras trabajabas, es posible que quieras sincronizar tu fork con los últimos cambios:

   ```bash
   git remote add upstream https://github.com/MiguelAdolfoV/Ahorros-Inteligentes.git
   git fetch upstream
   git merge upstream/master
   ```

### 4. Enviar Cambios a GitHub
   Sube tus cambios a tu fork en GitHub:

   ```bash
   git push origin nombre-de-tu-rama
   ```

### 5. Crear un Pull Request
   Ve a GitHub, selecciona tu fork y haz clic en el botón **New Pull Request** para solicitar que tus cambios sean revisados e integrados en el proyecto principal.

## Buenas Prácticas

- Haz **commits frecuentes** y descriptivos.
- Asegúrate de que tu código esté correctamente **testeado** y funcione antes de crear un **Pull Request**.
- Revisa si hay actualizaciones en el repositorio principal frecuentemente.

## Problemas Comunes

- **Error al agregar plataformas**: Si ves un error relacionado con Capacitor o Cordova, asegúrate de haber ejecutado `ionic capacitor sync`.
- **Fallo en la instalación de dependencias**: Si `npm install` falla, intenta eliminar `node_modules/` y ejecutar `npm install` nuevamente.

---
