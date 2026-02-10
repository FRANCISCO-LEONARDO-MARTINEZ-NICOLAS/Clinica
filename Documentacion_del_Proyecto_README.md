# Sistema Inteligente de Gestión para Óptica con IA y PostgreSQL

Documentación del proyecto en formato README, basada en el contenido original.

---

## 📌 Nombre del Proyecto
**Sistema Inteligente de Gestión para Óptica con IA y PostgreSQL**

## 👨‍💻 Desarrollador
**Francisco Leonardo Martínez Nicolás**

## 🎯 Objetivo General
Desarrollar una aplicación web integral para una óptica, que permita gestionar pacientes, historiales clínicos, productos y ventas, incorporando inteligencia artificial para facilitar diagnósticos optométricos y sugerencias de armazones basadas en reconocimiento facial.

---

## ✅ Justificación del Proyecto
El avance tecnológico permite integrar IA y bases de datos relacionales en PYMES. Este sistema busca mejorar la experiencia del cliente, apoyar decisiones clínicas y servir como proyecto de aprendizaje profesional.

---

## 🧰 Tecnologías a Utilizar
- **Base de Datos:** PostgreSQL
- **Backend:** Node.js + Express.js (Arquitectura Hexagonal + Vertical Slicing)
- **Frontend:** React.js + TailwindCSS
- **Reconocimiento Facial:** Python (OpenCV + Mediapipe, API Flask)
- **IA Clínica:** OpenAI API (GPT)
- **Autenticación:** JWT + Roles
- **Documentación API:** Swagger
- **Control de Versiones:** Git + GitHub
- **Contenedores:** Docker y Docker Compose (no se usarán en este proceso)

---

## 🧩 Arquitectura del Proyecto
- **Arquitectura Hexagonal** para separar la lógica de negocio.
- **Vertical Slicing** para dividir por funcionalidades completas.
- **Microservicios** para módulos de IA si se requiere escalabilidad.

---

## 🧑‍⚕️ Módulos del Sistema
### 1) Módulo de Pacientes
- Registro y actualización de pacientes
- Consulta de historial clínico
- Búsqueda avanzada

### 2) Módulo de Historial Clínico
- Registro de síntomas, diagnósticos y tratamientos
- Generación de reportes
- Sugerencia automática de diagnósticos (IA)

### 3) Módulo de Productos y Ventas
- Gestión de armazones, lentes y accesorios
- Registro de ventas
- Sugerencia de armazón con IA

### 4) Módulo de Usuarios
- Autenticación
- Gestión de permisos

---

## 🤖 Funcionalidades con IA
### Diagnóstico Optométrico Asistido
- Envío de síntomas a microservicio de IA (GPT o modelo entrenado)
- Sugerencias de diagnósticos y tratamientos

### Sugerencia de Armazones con Reconocimiento Facial
- Detección de facciones y forma de rostro con OpenCV/Mediapipe
- Recomendación de armazones en tiempo real

---

## 🗺️ Flujo de Trabajo Propuesto
**Fase 1: Planeación y Requerimientos**
- Definición de objetivos
- Selección de tecnologías
- Diagramas de casos de uso y entidad-relación

**Fase 2: Diseño**
- Diseño de base de datos
- Arquitectura de carpetas y rutas
- Diagramas de arquitectura y flujos

**Fase 3: Desarrollo Backend**
- Configuración de Express y conexión a PostgreSQL
- CRUD de pacientes e historial clínico
- API de diagnóstico (GPT)

**Fase 4: Desarrollo Frontend**
- UI con TailwindCSS
- Componentes funcionales en React
- Integración con backend

**Fase 5: Implementación de IA**
- Integración de reconocimiento facial
- Lógica de recomendación de armazones

**Fase 6: Pruebas y Documentación**
- Pruebas unitarias e integración
- Documentación Swagger
- Manual de usuario

---

## 🗄️ Modelado de Base de Datos (Resumen)
### Entidades Principales
- **Paciente**
- **Examen Clínico**
- **Historial Clínico**
- **Producto (Armazón/Lente)**
- **Venta**
- **Usuario**

### Ejemplo de Tablas (PostgreSQL)
```sql
-- Pacientes
CREATE TABLE pacientes (
  id SERIAL PRIMARY KEY,
  nombre VARCHAR(100),
  genero VARCHAR(10),
  edad INT,
  estado_civil VARCHAR(20),
  escolaridad VARCHAR(50),
  ocupacion VARCHAR(50),
  domicilio VARCHAR(150),
  email VARCHAR(100),
  telefono VARCHAR(20),
  tutor VARCHAR(100)
);

-- Exámenes Clínicos
CREATE TABLE examenes (
  id SERIAL PRIMARY KEY,
  paciente_id INT REFERENCES pacientes(id),
  fecha DATE,
  prediagnostico TEXT,
  diagnostico TEXT,
  plan_tratamiento TEXT,
  pronostico TEXT,
  proximacita DATE
);

-- Antecedentes
CREATE TABLE antecedentes (
  examen_id INT REFERENCES examenes(id),
  familiares TEXT,
  no_patologicos TEXT,
  patologicos TEXT,
  padecimiento_actual TEXT
);

-- Productos
CREATE TABLE productos (
  id SERIAL PRIMARY KEY,
  nombre VARCHAR(100),
  tipo VARCHAR(50),
  descripcion TEXT,
  precio DECIMAL,
  stock INT
);

-- Ventas
CREATE TABLE ventas (
  id SERIAL PRIMARY KEY,
  paciente_id INT REFERENCES pacientes(id),
  producto_id INT REFERENCES productos(id),
  fecha DATE,
  cantidad INT,
  total DECIMAL
);
```

---

## 🔌 Endpoints/API Sugeridos
- `/api/pacientes` (CRUD)
- `/api/examenes` (CRUD, vinculado a pacientes)
- `/api/productos` (CRUD)
- `/api/ventas` (registro de venta)
- `/api/diagnostico-ia` (síntomas → sugerencia GPT)
- `/api/armazon-ia` (reconocimiento facial → sugerencia)

---

## 🔐 Seguridad y Ética
- Protección de datos personales
- Consentimiento explícito para uso de IA
- No almacenar imágenes faciales sin cifrado o consentimiento

---

## 🧭 Metodología de Trabajo
- **SCRUM** (sprints semanales)
- **Gestión de tareas:** Trello o Notion
- **Revisión de avances:** GitHub + Issues + Pull Requests

---

## 🚀 Futuras Mejoras
- Entrenamiento de modelo propio de diagnóstico
- Predicción automática de stock
- IA para recomendaciones de tratamiento

---

## ✅ Conclusión
Proyecto completo, moderno, escalable y ético para la gestión inteligente de una óptica, integrando IA y mejores prácticas de desarrollo profesional.

---

## 📞 Contacto
Para dudas, sugerencias o colaboración:
**Francisco Leonardo Martínez Nicolás**
