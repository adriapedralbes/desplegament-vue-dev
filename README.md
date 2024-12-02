# 🐳 Proyecto con Vue, nodejs + laravel 🐳

**Levanta los servicios de forma sencilla**
- Ejecuta esto dentro de la carpeta Proyecto
    ```bash
    cd Proyecto #Aquí está el Makefile principal
    make start_all
Este proyecto utiliza Docker y `make` para gestionar de manera sencilla los servicios del frontend y backend. A continuación, encontrarás las instrucciones para instalar `make`, configurar el entorno y utilizar los comandos disponibles para desarrollo.

---

## 🚀 Requisitos

Antes de comenzar, asegúrate de tener instalados los siguientes componentes:

- **Docker**: [Guía de instalación oficial](https://docs.docker.com/get-docker/)
- **Make**: Es posible que ya esté preinstalado en tu sistema Linux. Si no, puedes instalarlo fácilmente siguiendo las instrucciones a continuación.

---

## ⚙️ Instalación de `make` en Linux

1. **Verificar si `make` está instalado**:
   ```bash
   make --version
2. **Instalar `make` en caso de no tenerlo instalado (LINUX)**
    ```bash
    sudo apt update && sudo apt install -y make
---

# 🛠️ Comandos disponibles

Este proyecto se gestiona mediante un archivo Makefile. 

1. **Listar comandos disponibles**
    ```bash
    cd Proyecto
    make help
2. **Ejemplo de salida**
    ```bash
    🐳 Makefile para gestión de proyectos Docker 🐳

    Ordenes disponibles:
    help  Target de ayuda por defecto
    start_all  Levanta todos los servicios en desarrollo
    stop_all  Detiene todos los servicios en desarrollo
    restart_all  Reinicia todos los servicios en desarrollo
## Descripción de los comandos principales
1. **Levantar todos los servicios**
    Inicia el entorno completo de desarrollo (frontend y backend) desde la carpeta ./Proyecto/:

    ```bash
    cd Proyecto #Donde se encuentra el Makefile
    make start_all
2. **Detener todos los servicios**
    Detiene todos los servicios de desarrollo:

    ```bash
    cd Proyecto
    make stop_all
3. **Reiniciar todos los servicios:**
    Reinicia el entorno de desarrollo:

    ```bash
    cd Proyecto
    make restart_all
4. **Obtener ayuda**
    Muestra la lista de comandos disponibles en el Makefile:

    ```bash
    cd Proyecto
    make help # o "make" como abreviatura
---

# 📂 Estructura del proyecto
El proyecto está dividido en dos directorios principales:

- **Back/:** Contiene el código y los servicios para el backend.
- **Front/:** Contiene el código y los servicios para el frontend.

Cada directorio tiene su propio **Makefile** con comandos específicos para gestionar sus servicios de forma independiente.
