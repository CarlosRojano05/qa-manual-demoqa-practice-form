# INFORME FINAL – DemoQA / Automation Practice Form

### 1. Información General
* **Proyecto:** DemoQA – Automation Practice Form
* **Módulo:** Practice Form
* **Rol:** QA Manual
* **Responsable QA:** Carlos Manuel Rojano Camargo
* **Fecha de inicio:** 24/12/2025
* **Fecha de cierre:** 04/01/2026
* **URL evaluada:** https://demoqa.com/automation-practice-form

### 2. Objetivo del Testing
Validar el correcto funcionamiento del formulario Student Registration Form (Practice Form), asegurando que cumpla con las reglas funcionales, validaciones de campos, comportamiento esperado, usabilidad básica e integridad visual, de acuerdo con el Test Plan definido.

### 3. Alcance del Proyecto
**Incluido**
* Validación funcional de todos los campos del formulario:
  * First Name
  * Last Name
  * Email
  * Gender
  * Mobile
  * Date of Birth
  * Subjects
  * Hobbies
  * Picture Upload
  * Address
  * State & City
  * Botón Submit
* **Tipos de pruebas:**
  * Funcionales
  * Negativas
  * Exploratorias
  * Validaciones de UI
  * Regresión básica

**Excluido**
* Pruebas backend
* Pruebas de performance
* Pruebas de seguridad
* Pruebas móviles
* Automatización

### 4. Estrategia de Pruebas
Las pruebas fueron ejecutadas de forma manual, utilizando datos de prueba creados específicamente para validar:
* Campos obligatorios
* Formatos inválidos
* Límites inferiores y superiores
* Dependencias entre campos (State & City)
* Comportamiento visual del formulario
* Flujo completo de envío exitoso

### 5. Casos de Prueba
* **Total de casos de prueba:** 12
* **Estado de ejecución:**
  * Ejecutados: 12
  * Pendientes: 0
* Todos los casos de prueba definidos para la historia de usuario US-001 – Student Registration Form fueron ejecutados.

### 6. Ejecución de Pruebas
**Resultado general**
* PASS: 10
* FAIL: 2

**Casos validados exitosamente**
* Restricciones de campos obligatorios
* Validaciones de formato (email, longitud de números)
* Dependencias entre State & City
* Envío exitoso del formulario con datos válidos
* Correcta visualización y alineación de la interfaz

### 7. Defectos Encontrados
* **Total de defectos reportados:** 2
* **Herramienta:** Jira

**Defectos identificados**
1. El campo First Name permite el ingreso y envío de caracteres numéricos, incumpliendo las reglas esperadas de validación.
2. El campo Date of Birth permite registrar fechas inválidas (fecha actual), permitiendo el registro de estudiantes sin una edad válida.

**Ambos defectos fueron:**
* Correctamente documentados
* Evidenciados con capturas
* Asociados a la historia de usuario correspondiente en Jira

### 8. Riesgos y Limitaciones
* El sitio DemoQA es una plataforma demo, con inestabilidad ocasional.
* Algunos campos con autocompletado presentan retardo en la respuesta.
* Los resultados pueden variar debido a la naturaleza no productiva del entorno.

### 9. Criterios de Cierre
* ✔️ Todos los casos de prueba fueron ejecutados
* ✔️ Defectos identificados y reportados correctamente
* ✔️ Evidencias de ejecución documentadas
* ✔️ Reporte de ejecución generado
* ✔️ Informe final de QA elaborado

### 10. Conclusión
El formulario Practice Form cumple en gran medida con los requisitos funcionales definidos. No obstante, se identificaron defectos funcionales en validaciones clave, los cuales no bloquean el flujo principal, pero impactan la calidad y consistencia de los datos. El proyecto se considera APTO PARA CIERRE DE QA, quedando los defectos documentados como hallazgos para corrección en un entorno productivo. Este proyecto demuestra la aplicación práctica del ciclo de vida del testing (STLC): planificación, diseño de casos de prueba, ejecución, documentación y cierre.
