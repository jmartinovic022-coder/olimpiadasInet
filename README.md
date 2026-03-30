# 🏥 Alarma Código Azul: Sistema de Gestión de Emergencias Hospitalarias 🏆

## 📋 Contexto y Motivación
Este proyecto, denominado **"Alarma Código Azul"**, fue desarrollado para las **Olimpiadas Nacionales de Educación Técnica (INET 2023)**. La solución se diseñó bajo el contexto de una licitación pública para optimizar la atención de emergencias críticas en entidades de salud, buscando reducir tiempos de respuesta y mejorar la calidad de atención al paciente.

---

## 📝 Descripción del Proyecto
Se desarrolló una plataforma **Full-stack** y **Mobile** de gestión de emergencias que permite la administración centralizada de recursos hospitalarios. El sistema implementa un motor de **Triage Automático** basado en estándares médicos internacionales para la priorización de pacientes.

---

## 📐 Diseño y Arquitectura de la Solución
El desarrollo siguió un modelado exhaustivo para garantizar la integridad y escalabilidad de los datos.

### 🔹 Modelo Entidad-Relación (DER)
Diseño conceptual que define las interacciones entre pacientes, personal médico, enfermeros y el sistema de alertas.
![Diagrama Entidad-Relación](Diseño/diagrama-entidad-relacion.jpeg)

### 🔹 Esquema Relacional de Base de Datos
Estructura técnica de tablas optimizada para el motor de **Django**, gestionando relaciones complejas y persistencia de datos.
![Modelo Relacional](Diseño/modelo-relacional-detallado.png)

### 🔹 Simulación de Infraestructura e IoT
Arquitectura de red diseñada en **Cisco Packet Tracer** para simular la conectividad inalámbrica entre el Gateway central, botones de pánico, sirenas y luces de emergencia en salas críticas.
![Arquitectura de Red e IoT](Diseño/arquitectura-red-iot.png)

---

## 🚀 Funcionalidades Clave
* **Gestión de Triage Multitono:** Clasificación de pacientes por niveles de gravedad:
  * 🔴 **Prioridad 1 (Roja):** Emergencia con amenaza de vida inmediata.
  * 🟡 **Prioridad 2 (Amarilla):** Urgencia grave que requiere atención a corto plazo.
  * 🟢 **Prioridad 3 (Verde):** Afección semi-urgente.
  * 🔵 **Prioridad 4 (Azul) / ⚪ Blanca:** Casos no urgentes o llamados desde boxes.
* **Control de Áreas Críticas:** Gestión (ABM) de Shock Room, Quirófanos, Salas de Traumatismos y Boxes.
* **Gestión de Roles (RBAC):** Accesos diferenciados para Médicos, Recepcionistas, Enfermeros y Administradores (Superusuario).
* **App Móvil para Médicos:** Desarrollada en **Flutter Flow**, permite recibir notificaciones en tiempo real y visualizar llamados activos.
* **Exportación de Datos:** Generación de registros individuales de pacientes en formatos **PDF** y **CSV**.

---

## 📊 Dashboard de Análisis y BI
El sistema integra un panel estadístico interactivo (**Chart.js**) para la toma de decisiones basada en datos:
* **Rendimiento de Respuesta:** Gráficos de tendencias en el tiempo de atención.
* **Distribución de Llamados:** Desglose circular por tipo de emergencia y criticidad.

---

## 🛠️ Tech Stack & Metodología
* **Metodología:** Gestión ágil bajo el marco de trabajo **Scrum** y organización en **Trello**.
* **Backend:** Python & Django (ORM y lógica de negocio).
* **Frontend:** HTML5, CSS3, JavaScript.
* **Mobile:** Flutter Flow.
* **Base de Datos:** SQLite3 (Entorno de desarrollo).
* **Herramientas:** Git, GitHub, VS Code, Cisco Packet Tracer.

---

## ⚙️ Desarrollo Técnico
* **Optimización:** Uso de clases y métodos genéricos de Django para garantizar código mantenible.
* **Control de Versiones:** Historial detallado en Git para trazabilidad de cambios y gestión de migraciones de DB.

---

## 📺 Demostración en Video
Para ver el sistema en acción, podés acceder a las presentaciones oficiales:
* 🖥️ **Plataforma Web/Desktop:** [Ver Demo en YouTube](https://www.youtube.com/watch?v=wT7_rz6IRCo)
* 📱 **Aplicación Móvil (Flutter Flow):** [Ver Demo en YouTube](https://www.youtube.com/shorts/5rqQNn9gy7k)

---

## 🖼️ Galería de Interfaces (UI/UX)
El sistema fue diseñado con una interfaz de alto contraste para facilitar la lectura en entornos hospitalarios de alta presión.

| **Dashboard de Analítica** | **Gestión de Llamados (Triage)** |
|:---:|:---:|
| ![Dashboard](screenshots/dashboard.png) | ![Llamados](screenshots/llamados.png) |
| [cite_start]*Visualización de estadísticas en tiempo real con Chart.js.* | [cite_start]*Monitorización de emergencias según niveles de criticidad[cite: 334].* |

| **Gestión de Pacientes (ABM)** | **Reporte Detallado de Emergencia** |
|:---:|:---:|
| ![Pacientes](screenshots/pacientes.png) | ![Reporte](screenshots/reporte.png) |
| [cite_start]*Administración centralizada de historias clínicas y patologías[cite: 341].* | [cite_start]*Exportación de datos críticos para seguimiento médico[cite: 335, 342].* |

---

## 👥 Investigación y Requisitos
El diseño de la solución no fue arbitrario; se basó en:
* **Entrevistas de Campo:** Consultas con personal médico y gerentes de entes hospitalarios para relevar necesidades críticas en salas de emergencias.
* **Metodología Centrada en el Usuario:** Análisis de historias de usuario para optimizar el flujo de trabajo de médicos y recepcionistas.


