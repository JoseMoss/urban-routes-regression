# Urban Routes – Pruebas de Regresión

Este repositorio contiene los artefactos y documentación para las **pruebas de regresión** de la aplicación de rutas `Urban Routes`.

## 📌 Descripción del Proyecto
Urban Routes es una aplicación que permite calcular rutas, duración y precio de viajes entre dos puntos (`Desde` y `Hasta`) usando distintos medios de transporte:

- Modos de ruta: Óptimo, Flash, Personal
- Tipos de transporte: Auto usuario, A pie, Taxi, Bicicleta, Scooter, Compartir auto

El objetivo de este proyecto es:
1. Ejecutar los casos de prueba de regresión preparados por el equipo de QA.
2. Identificar discrepancias entre el resultado esperado y el actual.
3. Reportar todos los errores al equipo de desarrollo para su corrección.

---

## 🗂 Estructura de Carpetas
```text
urban-routes-regression/
├─ .github/ISSUE_TEMPLATE/      # Plantillas de Issue para bugs y mejoras
├─ docs/                        # Documentación: test plan, traceability matrix
├─ test-cases/                  # Casos de prueba en formato Markdown
├─ reports/                     # Evidencias, capturas y logs de ejecución
└─ README.md                    # Este archivo
```

## 🚀 Primeros Pasos
1. Clonar este repositorio:
   ```bash
   git clone https://github.com/TU_USUARIO/urban-routes-regression.git
   cd urban-routes-regression
   ```
2. Crear la rama para tu sprint de regresión:
   ```bash
   git checkout -b regression-sprint-1
   ```
3. Ejecutar los casos de prueba listados en `test-cases/`.
4. Guardar evidencias en `reports/` y, si encuentras bugs, crear un issue usando `.github/ISSUE_TEMPLATE/bug_report.md`.

## 📋 Flujo de Trabajo
- Toda nueva prueba o corrección debe realizarse en una rama propia.
- Abrir pull request a `main` una vez terminada la ejecución y recolección de evidencias.
- Los issues de bugs deben etiquetarse con:
  - `bug`
  - `regression`
  - `severity: High|Medium|Low`

---

## 📝 Contribuciones y Reportes
Para reportar un bug, utiliza la plantilla [bug_report.md](.github/ISSUE_TEMPLATE/bug_report.md). Para solicitar nuevas funcionalidades o mejoras, utiliza [feature_request.md](.github/ISSUE_TEMPLATE/feature_request.md).

---

> _Desarrollado por JOSE LUIS MOSQUEDA MOLINARI as QA Engineer_
