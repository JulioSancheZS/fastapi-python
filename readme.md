# Aprendiendo FastAPI con Python

Este repositorio es parte de mi proceso de aprendizaje de FastAPI con Python. Por ahora solo esta el GET, POST, PUT y DELETE, crud básico con arreglos en python.

## ¿Qué es FastAPI?

FastAPI es un moderno framework web de Python para construir APIs de forma rápida y sencilla, con un rendimiento excepcional. Algunas características importantes de FastAPI incluyen:

- **Rápido y eficiente:** Basado en Starlette para manejar peticiones asíncronas y Pydantic para validación de datos.
- **Autodocumentación interactiva:** Genera automáticamente una documentación interactiva (Swagger UI) para tu API.
- **Tipado estático:** Utiliza Python tipo-hinting para proporcionar validación de datos y autocompletado en editores de código compatibles.
- **Fácil de usar:** Proporciona una sintaxis clara y expresiva para definir rutas, parámetros y respuestas de la API.

# Proceso para crear un Pull Request

Este documento describe los pasos necesarios para crear un pull request en este repositorio.

## Paso 1: Hacer un Fork del Repositorio

Haz clic en el botón "Fork" en la esquina superior derecha de la página para crear una copia del repositorio en tu propia cuenta.

## Paso 2: Clonar el Repositorio

Clona tu repositorio forked en tu computadora local utilizando el siguiente comando:

```
git clone URL_del_repositorio_forked
```

## Paso 3: Crear una Nueva Rama

Crea una nueva rama donde realizarás tus cambios utilizando el comando:

```
git checkout -b mi_nueva_rama
```

## Paso 4: Realizar Cambios

Realiza los cambios necesarios en tu copia local del repositorio utilizando tu editor de código favorito.

## Paso 5: Confirmar Cambios

Confirma tus cambios utilizando los siguientes comandos:

```
git add .
```
```
git commit -m "Descripción breve de tus cambios"
```

## Paso 6: Sincronizar con el Repositorio Original

Sincroniza tu repositorio forked con el repositorio original para asegurarte de trabajar con la última versión:

```
git remote add upstream URL_del_repositorio_original
```
```
git fetch upstream
```
```
git checkout main
```
```
git merge upstream/main

```

## Paso 7: Enviar el Pull Request

Empuja tu rama al repositorio forked en GitHub y luego ve a la página del repositorio original para crear un pull request desde tu rama hacia el repositorio original. Asegúrate de incluir una descripción clara de tus cambios.

```
git push origin mi_nueva_rama
```

¡Listo! Se a enviado un pull request al repositorio original.
