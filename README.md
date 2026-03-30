# 🏥 Alarma Código Azul: Sistema de Gestión de Emergencias Hospitalarias 🏆

## 📋 Contexto y Motivación
[cite_start]Este proyecto, denominado **"Alarma Código Azul"**, fue desarrollado para las **Olimpiadas Nacionales de Educación Técnica (INET 2023)**. [cite: 4, 30] [cite_start]La solución se diseñó bajo el contexto de una licitación pública para optimizar la atención de emergencias críticas en entidades de salud, buscando reducir tiempos de respuesta y mejorar la calidad de atención al paciente. [cite: 33, 34, 37]

---

## 📝 Descripción del Proyecto
[cite_start]Se desarrolló una plataforma **Full-stack** y **Mobile** de gestión de emergencias que permite la administración centralizada de recursos hospitalarios. [cite: 49, 50, 318] [cite_start]El sistema implementa un motor de **Triage Automático** basado en estándares médicos internacionales para la priorización de pacientes. [cite: 63, 67, 143]

---

## 📐 Diseño y Arquitectura de la Solución
[cite_start]El desarrollo siguió un modelado exhaustivo para garantizar la integridad y escalabilidad de los datos. [cite: 57, 440]

### 🔹 Modelo Entidad-Relación (DER)
[cite_start]Diseño conceptual que define las interacciones entre pacientes, personal médico, enfermeros y el sistema de alertas. [cite: 249, 251]
![Diagrama Entidad-Relación](Diseño/diagrama-entidad-relacion.jpeg)

### 🔹 Esquema Relacional de Base de Datos
[cite_start]Estructura técnica de tablas optimizada para el motor de **Django**, gestionando relaciones complejas y persistencia de datos. [cite: 278, 324]
![Modelo Relacional](Diseño/modelo-relacional-detallado.png)

### 🔹 Simulación de Infraestructura e IoT
[cite_start]Arquitectura de red diseñada en **Cisco Packet Tracer** para simular la conectividad inalámbrica entre el Gateway central, botones de pánico, sirenas y luces de emergencia en salas críticas. [cite: 366, 367, 370]
![Arquitectura de Red e IoT](Diseño/arquitectura-red-iot.png)

---

## 🚀 Funcionalidades Clave
* **Gestión de Triage Multitono:** Clasificación de pacientes por niveles de gravedad:
  * [cite_start]🔴 **Prioridad 1 (Roja):** Emergencia con amenaza de vida inmediata. [cite: 68]
  * [cite_start]🟡 **Prioridad 2 (Amarilla):** Urgencia grave que requiere atención a corto plazo. [cite: 69]
  * [cite_start]🟢 **Prioridad 3 (Verde):** Afección semi-urgente. [cite: 71]
  * [cite_start]🔵 **Prioridad 4 (Azul) / ⚪ Blanca:** Casos no urgentes o llamados desde boxes. [cite: 72, 73]
* [cite_start]**Control de Áreas Críticas:** Gestión (ABM) de Shock Room, Quirófanos, Salas de Traumatismos y Boxes. [cite: 156, 159]
* [cite_start]**Gestión de Roles (RBAC):** Accesos diferenciados para Médicos, Recepcionistas, Enfermeros y Administradores (Superusuario). [cite: 123, 229, 281]
* [cite_start]**App Móvil para Médicos:** Desarrollada en **Flutter Flow**, permite recibir notificaciones en tiempo real y visualizar llamados activos. [cite: 50, 152, 357]
* [cite_start]**Exportación de Datos:** Generación de registros individuales de pacientes en formatos **PDF** y **CSV**. [cite: 184, 197]

---

## 📊 Dashboard de Análisis y BI
[cite_start]El sistema integra un panel estadístico interactivo (**Chart.js**) para la toma de decisiones basada en datos: [cite: 171, 336]
* [cite_start]**Rendimiento de Respuesta:** Gráficos de tendencias en el tiempo de atención. [cite: 178, 180]
* [cite_start]**Distribución de Llamados:** Desglose circular por tipo de emergencia y criticidad. [cite: 179]

---

## 🛠️ Tech Stack & Metodología
* [cite_start]**Metodología:** Gestión ágil bajo el marco de trabajo **Scrum** y organización en **Trello**. [cite: 44, 309]
* [cite_start]**Backend:** Python & Django (ORM y lógica de negocio). [cite: 49, 324, 346]
* [cite_start]**Frontend:** HTML5, CSS3, JavaScript. [cite: 49]
* [cite_start]**Mobile:** Flutter Flow. 
* [cite_start]**Base de Datos:** SQLite3 (Entorno de desarrollo). [cite: 49, 306]
* [cite_start]**Herramientas:** Git, GitHub, VS Code, Cisco Packet Tracer. [cite: 51, 52, 305, 367]

---

## ⚙️ Desarrollo Técnico
* [cite_start]**Optimización:** Uso de clases y métodos genéricos de Django para garantizar código mantenible. [cite: 345, 347, 348]
* [cite_start]**Control de Versiones:** Historial detallado en Git para trazabilidad de cambios y gestión de migraciones de DB. [cite: 51, 404]
