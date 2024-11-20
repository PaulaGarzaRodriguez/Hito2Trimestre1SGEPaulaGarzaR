# Hito2Trimestre1SGEPaulaGarzaR
# Análisis del Consumo de Alcohol y su Impacto en la Salud

## Introducción
El consumo de alcohol y sus efectos en la salud constituyen un tema relevante para investigadores y responsables de políticas de salud pública. Este proyecto se enfoca en el análisis de patrones de consumo y su relación con diversas condiciones de salud. Al explorar datos relacionados con el consumo semanal de diferentes tipos de bebidas (cervezas, vinos, destilados) y factores demográficos como edad y género, buscamos identificar comportamientos de riesgo y áreas potenciales de intervención.

El objetivo del proyecto es proporcionar herramientas de análisis y visualización que faciliten la toma de decisiones basadas en datos.

## Características Principales
- **Base de Datos**: Incluye encuestas con datos demográficos y patrones de consumo de alcohol. Cada registro es único y autoincremental para facilitar la gestión y análisis.
- **Interfaz Gráfica**: Aplicación creada con `TKinter` para interactuar con la base de datos MySQL de forma amigable.
- **Visualización de Datos**: Generación de gráficos y tablas mediante `Matplotlib` y `Pandas`.

## Tecnologías y Librerías
Este proyecto utiliza las siguientes tecnologías y librerías:
- **TKinter**:
  - `messagebox`: Para mensajes emergentes (alertas y errores).
  - `Toplevel`: Ventanas secundarias dentro de la aplicación.
  - `ttk`: Widgets mejorados como tablas y comboboxes.
- **Collections.defaultdict**: Para la manipulación eficiente de datos estructurados.
- **MySQL Connector**: Para la conexión y manipulación de la base de datos `ENCUESTAS`.
- **Pandas**: Para el análisis y manejo de datos tabulares.
- **Matplotlib.pyplot**: Para la generación de gráficos basados en los datos analizados.

## Función Principal: Conexión a la Base de Datos
La función de conexión establece una relación con la base de datos `ENCUESTAS` en un servidor MySQL. Credenciales:
- **Host**: `localhost`
- **Usuario**: `root`
- **Contraseña**: `password`
- **Base de Datos**: `ENCUESTAS`

En caso de error (como credenciales incorrectas o problemas de conexión), la aplicación notificará al usuario con mensajes claros.

## Estructura del Proyecto
- **Base de Datos**:
  - Diseño optimizado para asegurar que cada registro sea único y se gestione eficientemente.
- **Interfaz**:
  - Intuitiva, con funcionalidades para consultar, analizar y visualizar los datos.
- **Gráficos y Tablas**:
  - Representación clara de las tendencias y patrones de consumo.

## Instalación de Dependencias
Antes de ejecutar la aplicación, asegúrate de instalar las librerías necesarias. Sigue estos pasos en la terminal:

1. Asegúrate de tener instalado [Python 3](https://www.python.org/downloads/).
2. Instala las librerías requeridas ejecutando el siguiente comando en la terminal:

   ```bash
   pip install tkinter mysql-connector-python pandas matplotlib

## Repositorio
Encuentra el código fuente y documentación completa en [GitHub](https://github.com/PaulaGarzaRodriguez/Hito2Trimestre1SGEPaulaGarzaR).

---

Este proyecto fue desarrollado como parte del Hito 2 del 1er Trimestre en la asignatura SGE por Paula Garza Rodríguez.
