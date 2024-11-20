# **Procesamiento Café - Backend**

Este repositorio contiene el backend del sistema para la automatización del procesamiento de camiones y clasificación de sacos de café. El backend está desarrollado en **FastAPI** y utiliza **SQLite** como base de datos para el almacenamiento de registros.

---

## **Características del Backend**

- **Procesamiento de camiones:**
  - Calcular el peso de la carga.
  - Determinar la cantidad de sacos clasificados como "Especiales" o "Defectuosos".
  - Registrar el peso vacío, peso cargado y otros datos relacionados con el camión.
- **Gestión de agenda:**
  - Almacenar registros de camiones procesados.
  - Consultar registros por fecha.
  - Filtrar registros para facilitar la búsqueda.

---

## **Tecnologías Utilizadas**

- **FastAPI:** Framework ligero y rápido para construir APIs RESTful.
- **SQLite:** Base de datos embebida para el almacenamiento de registros.
- **Uvicorn:** Servidor ASGI para ejecutar la aplicación FastAPI.
- **Pydantic:** Para la validación y gestión de datos.

---

## **Requisitos Previos**

- Python 3.8 o superior instalado.
- Git instalado para clonar el repositorio.
