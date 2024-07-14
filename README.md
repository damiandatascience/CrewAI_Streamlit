# Generador de Artículos con CrewAI y Streamlit

## Descripción

El Generador de Artículos con CrewAI y Streamlit es una aplicación web innovadora que utiliza inteligencia artificial para crear artículos completos sobre cualquier tema. Esta herramienta combina la potencia de CrewAI para la generación de contenido con la simplicidad de Streamlit para ofrecer una interfaz de usuario intuitiva y fácil de usar.

## Características Principales

- **Generación de Artículos Personalizados**: Introduce un tema y obtén un artículo completo generado por IA.
- **Interfaz Amigable**: Diseñada con Streamlit para una experiencia de usuario fluida y accesible.
- **Proceso de Tres Etapas**: Utiliza un equipo de IA compuesto por un investigador, un escritor y un editor para producir contenido de alta calidad.
- **Descarga Fácil**: Opción para descargar los artículos generados en formato de texto.
- **Personalizable**: Utiliza tu propia clave API de OpenAI para un control total sobre el proceso de generación.

## Cómo Funciona

1. **Investigación**: Un agente de IA recopila información relevante sobre el tema proporcionado.
2. **Redacción**: Otro agente utiliza la investigación para escribir un borrador inicial del artículo.
3. **Edición**: Un tercer agente revisa y refina el artículo para mejorar su calidad y coherencia.

## Requisitos

- Python >=3.10 and <=3.13 installed on your system:
- Poetry (para gestión de dependencias y entornos virtuales)
- Una clave API válida de OpenAI

## Instalación

1. Clona este repositorio:
   ```
   git clone https://github.com/damiandatascience/CrewAI_Streamlit.git
   
   ```
2. Navega al directorio del proyecto:
   ```
   cd CrewAI_Streamlit
   ```
3. Instala las dependencias usando Poetry:
   ```
   poetry install --no-root.
   ```

## Uso

1. Activa el entorno virtual de Poetry:
   ```
   poetry shell
   ```
2. Ejecuta la aplicación:
   ```
   poetry run streamlit run app.py
   ```
3. Abre tu navegador y ve a `http://localhost:8501`.
4. Ingresa tu clave API de OpenAI y el tema sobre el que deseas generar un artículo.
5. Haz clic en "Generar Artículo" y espera a que se complete el proceso.
6. Lee el artículo generado y descárgalo si lo deseas.

## Estructura del Proyecto

```
├── pyproject.toml    # Configuración de Poetry y metadatos del proyecto
├── poetry.lock       # Archivo de bloqueo de dependencias de Poetry
├── README.md         # Este archivo
├── app.py            # Código principal de la aplicación Streamlit
```

## Desarrollo

Para añadir nuevas dependencias al proyecto:

```
poetry add nombre-del-paquete
```

Para actualizar las dependencias:

```
poetry update
```

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue para discutir cambios mayores antes de hacer un pull request.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## Contacto

Para preguntas o soporte, por favor contacta a soporte@inteligenciartificialgenerativa.online.


---

Desarrollado con ❤️ por [Tu Nombre/Organización]
