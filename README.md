# ARTE

## Descripción
ARTE es un proyecto desarrollado en el contexto de la exposición permanente de La Alcudia en el Museo de la Universidad de Alicante. El objetivo de este proyecto es ofrecer una experiencia enriquecida a los visitantes del museo a través de la integración de tecnologías avanzadas como la realidad aumentada y asistentes virtuales. El proyecto está compuesto por varios módulos, cada uno con una función específica.

## Estructura del Proyecto

### Angular
- **Descripción**: Este es el proyecto FrontEnd que incluye el sistema de administración y gestión de datos para el museo.
- **Características**:
  - **Sistema de administración**: Herramientas para la gestión de datos del museo.
  - **Plataforma de realidad aumentada**: Utiliza un motor gráfico propio que permite a los usuarios interactuar con las piezas del museo a través del escaneo de códigos QR.

### Manual
- **Descripción**: Manual de uso de la herramienta, creado con exeLearning.
- **Objetivo**: Proporcionar una guía detallada para los usuarios sobre cómo utilizar las diferentes funcionalidades del sistema.

### Node
- **Descripción**: Proyecto BackEnd que incluye la API y las llamadas necesarias para los servicios ofrecidos en el proyecto Angular.
- **Características**:
  - **API REST**: Facilita la comunicación entre el FrontEnd y la base de datos.
  - **Servicios**: Manejo de autenticación, gestión de datos, y otras funcionalidades críticas para el funcionamiento del sistema.

### Rasa
- **Descripción**: Contiene el código del asistente virtual llamado Alcudio.
- **Características**:
  - **Asistente Virtual**: Diseñado para guiar al público infantil durante su visita al museo.
  - **Interactividad**: Responde preguntas y proporciona información educativa y entretenida sobre las exhibiciones.

## Instalación y Configuración

### Prerrequisitos
- Node.js
- Angular CLI
- exeLearning (para el manual)
- Rasa

### Pasos de Instalación

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/tu_usuario/ARTE.git
   cd ARTE
