# 📋 TEST PLAN – DemoQA / Practice Form

## 1. Información General
* **Proyecto:** DemoQA – Automation Practice Form
* **Módulo:** Practice Form
* **Rol:** QA Manual
* **Responsable QA:** Carlos Manuel Rojano Camargo
* **Fecha de inicio:** 24/12/2025
* **Objetivo:** Validar el correcto funcionamiento del formulario Practice Form, garantizando que cumple con las reglas funcionales, validaciones, usabilidad y comportamiento esperado.

---

## 2. Alcance del Testing

### ✅ Incluye:
* **Validación de campos:** First Name, Last Name, Email, Gender, Mobile, Date of Birth, Subjects, Hobbies, Picture Upload, Address, State & City, Submit button.
* **Validaciones:** Campos obligatorios, formatos, valores inválidos, comportamientos por técnica de pruebas y mensajes esperados.
* **Tipos de prueba:** Funcionales, Negativas, Exploratorias, Validaciones UI y Regresión básica.

### ❌ No incluye:
* Pruebas de Backend, Performance, Seguridad, Móviles o Automatización.

---

## 3. Tipos de Pruebas
| Tipo | ¿Se incluye? | Descripción |
| :--- | :---: | :--- |
| **Funcional** | ✔️ | Confirmar que cada campo haga lo esperado. |
| **Validaciones** | ✔️ | Formatos, reglas, valores obligatorios. |
| **Negativas** | ✔️ | Intentar romper el formulario con datos incorrectos. |
| **Exploratorias** | ✔️ | Buscar comportamientos inesperados. |
| **Regresión** | ✔️ | Revisar que los flujos principales funcionen. |

---

## 4. Entorno de Pruebas
* **URL:** [DemoQA - Practice Form](https://demoqa.com/automation-practice-form)
* **Navegador sugerido:** Google Chrome
* **Datos de prueba:** Creación propia (DataSet específico)
* **Limitaciones:** Página demo, puede presentar fallos aleatorios de carga.

---

## 5. Criterios de Calidad
### 🏁 Criterios de Aceptación
* Toda la funcionalidad principal validada.
* Sin defectos **Críticos** o **Bloqueantes** abiertos.
* 100% de los casos de prueba ejecutados.
* Reporte de ejecución generado y documentado.

### 🛑 Criterios de Suspensión
* El sitio web no carga (Down).
* Más del 40% de los casos fallan por defectos bloqueantes.

---

## 6. Gestión de Riesgos
* Inestabilidad del servidor de DemoQA.
* Comportamientos inestables en el renderizado de anuncios (Ads) que tapan el botón Submit.
* Lag en los campos de autocompletado (State & City).

---

## 7. Herramientas y Artefactos
* **Gestión de Defectos:** Jira (Historias de usuario, trazabilidad).
* **Documentación:** Microsoft Excel (Casos de prueba y reportes).
* **Evidencias:** Capturas de pantalla (Screenshots).
* **Navegador:** Google Chrome.
