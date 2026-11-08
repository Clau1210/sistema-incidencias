
# Sistema de Incidencias

## 1. Propósito del proyecto

Desarrollar un sistema básico para registrar y validar incidencias informáticas mediante JavaScript, aplicando pruebas automatizadas e integración continua con GitHub Actions.

## 2. Integrantes

- Claudia Morales - Clau1210
- Mariano Figueroa - marianofigueroa161-byte

## 3. Tecnologías utilizadas

- GitHub
- GitHub Actions
- JavaScript
- Node.js 22

## 4. Archivos del proyecto

- package.json: configuración del proyecto y comando de pruebas.
- incidencias.js: función para validar las incidencias.
- test.js: contiene las tres pruebas automatizadas.
- .github/workflows/ci.yml: configuración del workflow de integración continua.

## 5. Procedimiento realizado

1. Se creó el repositorio sistema-incidencias.
2. Se agregaron los integrantes como colaboradores.
3. Se desarrolló la función de validación de incidencias.
4. Se implementaron tres pruebas automatizadas.
5. Se configuró GitHub Actions para ejecutar las pruebas automáticamente.
6. Se provocó un error agregando la prioridad urgente.
7. Se comprobó que una prueba fallara.
8. Se corrigió el error y se verificó que las tres pruebas pasaran correctamente.

## 6. Preguntas

### ¿Qué evento activa el workflow?

Los eventos push y pull_request activan el workflow, ejecutando automáticamente las pruebas cuando se envían cambios o se realizan solicitudes de integración.

### ¿Qué verifica la prueba automatizada?

Verifica que la función validarIncidencia acepte incidencias válidas y rechace aquellas que tienen prioridades desconocidas o descripciones vacías.

### ¿Qué diferencia existe entre un commit y una ejecución de Actions?

Un commit registra los cambios realizados en el repositorio. Una ejecución de Actions ejecuta automáticamente las tareas configuradas en el workflow, como las pruebas del proyecto.

### ¿Qué ventaja ofrece detectar un error antes de integrar más cambios?

Permite identificar y corregir errores oportunamente, evitando que los problemas se acumulen y afecten otras funcionalidades del sistema.

## 7. Enlaces

- Repositorio: https://github.com/Clau1210/sistema-incidencias
- Ejecuciones: https://github.com/Clau1210/sistema-incidencias/actions
## 8. Participación del colaborador

**Mariano Figueroa - marianofigueroa161-byte**

Participé en la revisión de la documentación del proyecto Sistema de Incidencias, verificando la descripción de sus funcionalidades, las pruebas automatizadas y la configuración de integración continua mediante GitHub Actions. Asimismo, colaboré en la actualización del archivo README.md para mantener organizada la información del proyecto.
