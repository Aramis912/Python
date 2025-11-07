# 📚 Biblioteca CLI (MongoDB NoSQL)

Este es un administrador de biblioteca personal implementado en Python utilizando la base de datos NoSQL MongoDB. Permite a los usuarios registrar, listar y gestionar sus libros.

## ⚙️ Consideraciones Técnicas

### 1. Instalación de MongoDB

Para ejecutar esta aplicación, necesitas tener un servidor MongoDB corriendo.

**Opción A: Instalación Local**
1. Descarga e instala el Servidor MongoDB.
2. Inicia el servicio `mongod` (el proceso por defecto escucha en `mongodb://localhost:27017/`).

**Opción B: MongoDB Atlas (Nube)**
1. Crea una cuenta gratuita en MongoDB Atlas.
2. Crea un clúster y obtén la cadena de conexión (URI).

### 2. Configuración del Entorno Python

1. **Clonar/Descargar** este repositorio.
2. **Crear y Activar** un entorno virtual (recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   .\venv\Scripts\Activate   # Windows
