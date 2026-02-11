# Apartado I — Especificación del proyecto

## A) Conversación simulada con el cliente
**Contexto:** entrevista inicial entre el ingeniero de campo y el dueño/gerente de la óptica.

**Ing. de campo:** ¿Cuál es su giro del negocio o de qué trata su negocio?  
**Cliente (Dr. Óptica):** Somos una óptica. Contamos con optometristas y un gerente. Realizamos exámenes de la vista y vendemos armazones, micas, accesorios y otros productos.

**Ing. de campo:** ¿Cuántas sucursales tienen y cómo se organizan?  
**Cliente:** Actualmente tenemos 2 sucursales. En cada una hay optometristas, un encargado y personal de ventas. El gerente general supervisa inventario y ventas.

**Ing. de campo:** ¿Qué procesos son los más importantes en el día a día?  
**Cliente:** Registro de pacientes, consulta optométrica completa, receta final, ventas, control de inventario y agenda de citas.

**Ing. de campo:** ¿Qué problemas o necesidades tienen hoy?  
**Cliente:** Usamos hojas clínicas en papel y hojas de Excel. Se pierde información, tardamos en encontrar historiales y no tenemos reportes confiables. También queremos sugerir armazones según el tipo de rostro.

**Ing. de campo:** ¿Qué información necesitan consultar con frecuencia?  
**Cliente:** Historial clínico por paciente, ventas por periodo, inventario disponible, y desempeño de cada optometrista.

**Ing. de campo:** ¿Qué esperan del sistema?  
**Cliente:** Un sistema centralizado para pacientes, consultas y ventas; que nos ayude a tomar decisiones; y que incorpore IA para sugerir diagnósticos y armazones.

**Ing. de campo:** ¿Hay restricciones o consideraciones éticas?  
**Cliente:** Sí, proteger datos personales y no guardar fotos faciales sin consentimiento.

**Ing. de campo:** ¿Quiénes usarán el sistema?  
**Cliente:** Administrador/gerente, optometristas y personal de ventas.

---

## A.1) Entrevista simulada ampliada (complementaria)

### 1) Contexto general del negocio
**Ing. de campo:** ¿Cuál es la historia del negocio y cuánto tiempo llevan operando?  
**Cliente:** Llevamos 8 años. Empezamos con una sucursal y ahora ya tenemos dos.

**Ing. de campo:** ¿Cuál es su principal diferencia frente a otras ópticas?  
**Cliente:** La atención personalizada y el seguimiento clínico. Queremos reforzar eso con tecnología.

**Ing. de campo:** ¿Cuál es el volumen promedio de pacientes por día?  
**Cliente:** Entre 15 y 25 por sucursal, depende de la temporada.

**Ing. de campo:** ¿Qué temporadas tienen mayor demanda?  
**Cliente:** Regreso a clases y fin de año.

### 2) Áreas del negocio
**Ing. de campo:** ¿Qué áreas forman parte de la óptica?  
**Cliente:** Administración, optometría, ventas, recepción y almacén.

**Ing. de campo:** ¿Cómo se coordinan entre áreas?  
**Cliente:** Todo se comunica por WhatsApp o de palabra, no tenemos un sistema único.

### 3) Roles y responsabilidades
**Ing. de campo:** ¿Qué hace el gerente general?  
**Cliente:** Supervisa sucursales, finanzas, inventario, proveedores y reportes.

**Ing. de campo:** ¿Qué hace el optometrista en el día a día?  
**Cliente:** Consulta, diagnóstico, receta, seguimiento del paciente y recomendaciones.

**Ing. de campo:** ¿Qué hace el personal de ventas?  
**Cliente:** Muestra productos, registra ventas, gestiona pagos y entrega.

**Ing. de campo:** ¿Qué hace recepción?  
**Cliente:** Agenda citas, registra pacientes nuevos y organiza expedientes.

**Ing. de campo:** ¿Quién administra el inventario?  
**Cliente:** El encargado de ventas y el gerente.

### 4) Actividades y procesos clínicos
**Ing. de campo:** ¿Cómo realizan una consulta completa?  
**Cliente:** Registro, antecedentes, pruebas visuales, diagnóstico y receta final.

**Ing. de campo:** ¿Usan un formato clínico estándar?  
**Cliente:** Sí, una hoja clínica en papel.

**Ing. de campo:** ¿Qué pruebas son obligatorias?  
**Cliente:** Agudeza visual, refracción y exploración básica.

**Ing. de campo:** ¿Guardan el historial clínico?  
**Cliente:** Sí, pero en archivos físicos, por eso se pierde fácil.

**Ing. de campo:** ¿Cómo realizan el seguimiento del paciente?  
**Cliente:** Con notas en el expediente y llamadas cuando toca revisión.

### 5) Actividades y procesos de ventas
**Ing. de campo:** ¿Cómo se registra una venta?  
**Cliente:** En una hoja de Excel y a veces en papel.

**Ing. de campo:** ¿Qué tipos de productos venden?  
**Cliente:** Armazones, micas, lentes de contacto, líquidos y accesorios.

**Ing. de campo:** ¿Cómo se calcula el precio final?  
**Cliente:** Depende del producto, material, tratamiento y promociones.

**Ing. de campo:** ¿Se maneja factura?  
**Cliente:** Sí, pero no está automatizado.

### 6) Agenda y citas
**Ing. de campo:** ¿Cómo se agenda una cita?  
**Cliente:** Por teléfono o WhatsApp, se anota en una libreta.

**Ing. de campo:** ¿Cómo evitan choques de horario?  
**Cliente:** No siempre se evita, por eso queremos un sistema.

**Ing. de campo:** ¿Tienen recordatorios de citas?  
**Cliente:** Manualmente, por mensaje.

### 7) Inventario y proveedores
**Ing. de campo:** ¿Cómo controlan el inventario?  
**Cliente:** Con Excel, pero no siempre se actualiza a tiempo.

**Ing. de campo:** ¿Qué problemas tienen con el stock?  
**Cliente:** Faltantes, productos caducados o duplicados.

**Ing. de campo:** ¿Cómo gestionan proveedores?  
**Cliente:** El gerente hace pedidos según necesidad.

### 8) Información y reportes
**Ing. de campo:** ¿Qué reportes necesitan con frecuencia?  
**Cliente:** Ventas por mes, productos más vendidos, citas atendidas y productividad.

**Ing. de campo:** ¿Qué indicadores usan para decisiones?  
**Cliente:** Ingresos, tickets promedio, rotación de inventario.

**Ing. de campo:** ¿Qué reportes clínicos les interesan?  
**Cliente:** Historial de pacientes, diagnósticos recurrentes y frecuencia de visitas.

### 9) Tecnología actual
**Ing. de campo:** ¿Qué sistemas usan hoy?  
**Cliente:** Excel, WhatsApp y papel.

**Ing. de campo:** ¿Qué problemas les genera eso?  
**Cliente:** Pérdida de información, duplicidad y poca trazabilidad.

**Ing. de campo:** ¿Qué nivel de tecnología manejan los empleados?  
**Cliente:** Básico. Necesitamos algo fácil de usar.

### 10) Necesidades específicas
**Ing. de campo:** ¿Qué es lo más urgente a resolver?  
**Cliente:** Historial clínico digital y control de inventario.

**Ing. de campo:** ¿Qué procesos quieren automatizar primero?  
**Cliente:** Registro de pacientes, consultas y ventas.

**Ing. de campo:** ¿Qué esperan mejorar con el sistema?  
**Cliente:** Tiempo, orden y atención al paciente.

### 11) IA y valor agregado
**Ing. de campo:** ¿Qué esperan de la IA?  
**Cliente:** Ayuda en diagnóstico y sugerencia de armazones.

**Ing. de campo:** ¿Qué tipo de sugerencias serían útiles?  
**Cliente:** Diagnósticos probables y recomendaciones de armazones.

**Ing. de campo:** ¿Qué tan confiables deben ser?  
**Cliente:** Como apoyo, no para sustituir al optometrista.

### 12) Seguridad y privacidad
**Ing. de campo:** ¿Qué datos consideran sensibles?  
**Cliente:** Historial clínico, recetas y datos personales.

**Ing. de campo:** ¿Quieren control por roles?  
**Cliente:** Sí, cada rol con permisos claros.

**Ing. de campo:** ¿Guardarán imágenes faciales?  
**Cliente:** Solo con consentimiento.

### 13) Alcance y expectativas
**Ing. de campo:** ¿En cuántas sucursales se usará?  
**Cliente:** En las dos actuales, con posibilidad de crecer.

**Ing. de campo:** ¿Qué esperan a corto plazo?  
**Cliente:** Un sistema estable y fácil de usar.

**Ing. de campo:** ¿Qué esperan a largo plazo?  
**Cliente:** Reportes avanzados y más automatización.

### 14) Requerimientos no funcionales
**Ing. de campo:** ¿Necesitan acceso desde cualquier lugar?  
**Cliente:** Sí, desde navegador.

**Ing. de campo:** ¿Qué nivel de disponibilidad requieren?  
**Cliente:** Horario laboral completo.

**Ing. de campo:** ¿Qué tan rápida debe ser la respuesta?  
**Cliente:** Menos de 2–3 segundos por operación.

### 15) Implementación y capacitación
**Ing. de campo:** ¿Quién capacitará al personal?  
**Cliente:** Nosotros, pero necesitamos manuales.

**Ing. de campo:** ¿Cómo prefieren el despliegue?  
**Cliente:** En la nube, si no es muy complejo.

**Ing. de campo:** ¿Qué apoyo necesitan?  
**Cliente:** Guía paso a paso.

---

## B) Especificación del proyecto (Apartado I)

### 1.1 Giro y actividad del negocio
**Giro:** Servicios de salud visual y venta de productos ópticos.  
**Actividad:** Exámenes optométricos, generación de receta, venta de armazones, micas y accesorios, y seguimiento de pacientes.

### 1.2 Estructura / arquitectura del negocio
- **Gerente general / Administrador**
  - Supervisa sucursales, ventas e inventario
- **Optometristas**
  - Realizan consultas y generan diagnósticos
- **Personal de ventas**
  - Gestiona venta de productos y cobros
- **Soporte administrativo**
  - Agenda de citas, recepción y atención básica

### 1.3 Procesos del negocio (nombre y descripción)
1. **Registro de pacientes**: alta, actualización y consulta de datos personales y clínicos.
2. **Consulta optométrica**: captura de antecedentes, pruebas clínicas y diagnóstico.
3. **Receta y plan de tratamiento**: generación de receta óptica y recomendaciones.
4. **Agenda de citas**: programación y seguimiento de visitas.
5. **Ventas**: registro de ventas, productos vendidos y cobros.
6. **Inventario**: control de stock de armazones, micas y accesorios.
7. **Reportes**: estadísticas clínicas y comerciales (ventas, productividad, etc.).

### 1.4 Necesidades de desarrollo de sistemas de información
- Centralizar el historial clínico y datos del paciente.
- Digitalizar la hoja clínica completa para evitar pérdida de información.
- Automatizar reportes de ventas e inventario.
- Mejorar tiempos de búsqueda y seguimiento de pacientes.
- Integrar sugerencias con IA para diagnóstico y armazones.
- Control de acceso por roles (administrador, optometrista, ventas).

### 1.5 Propuesta del sistema a desarrollar
**Sistema inteligente de gestión para óptica** que permita:
- Gestión integral de pacientes, consultas y recetas.
- Registro y control de ventas e inventario.
- Agenda de citas y seguimiento clínico.
- Reportes administrativos y clínicos.
- Módulo de IA para sugerir diagnósticos y armazones.
- Seguridad con roles y protección de datos.

### 1.6 Justificación del desarrollo del sistema
El sistema es necesario porque la operación actual depende de papel y hojas de cálculo, lo que causa pérdida de información, baja eficiencia y falta de reportes confiables. Al digitalizar los procesos clínicos y comerciales se mejora la calidad del servicio, la toma de decisiones y la productividad. Además, la integración de IA aporta valor diferencial al recomendar diagnósticos y armazones, incrementando la satisfacción del cliente y la competitividad del negocio.
