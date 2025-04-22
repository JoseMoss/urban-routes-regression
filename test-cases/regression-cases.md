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


## 📋 Flujo de Trabajo
- Toda nueva prueba o corrección debe realizarse en una rama propia.
- Abrir pull request a `main` una vez terminada la ejecución y recolección de evidencias.
- Los issues de bugs deben etiquetarse con:
  - `bug`
  - `regression`
  - `severity: High|Medium|Low`

---

## ✅ Casos de Prueba Ejecutados
Los casos de prueba están documentados en `test-cases/` y reflejan el estado actual de cada uno:

- **CASO-1**: Desplazamiento del mapa – ✅ Aprobado
- **CASO-2**: Zoom del mapa – ✅ Aprobado
- **CASO-3**: No se puede hacer clic en los encabezados del área – ❌ No aprobado (URB-5)
- **CASO-4**: No se puede hacer clic en los encabezados de la ciudad – ✅ Aprobado
- **CASO-5**: Se puede seleccionar el campo "Desde" – ❌ No aprobado (URB-7)
- **CASO-6**: Búsqueda en campo "Hasta" – ❌ No aprobado (URB-1)
- **CASO-7**: Pin visible tras completar "Desde" – ❌ No aprobado (URB-2)
- **CASO-8**: Pin visible tras completar "Hasta" – ❌ No aprobado (URB-3)
- **CASO-9**: Eliminación del campo "Desde" – ✅ Aprobado
- **CASO-10**: Eliminación del campo "Hasta" – ✅ Aprobado
- **CASO-11**: Renderización de objetos 3D – ✅ Aprobado
- **CASO-12**: Activar modo pantalla completa – ❌ No aprobado (URB-6)
- **CASO-13**: Desactivar modo pantalla completa – ✅ Aprobado
- **CASO-14**: Activar modo Relieve – ✅ Aprobado
- **CASO-15**: Activar modo Satélite – ❌ No aprobado (URB-8)
- **CASO-16**: Edificios al hacer zoom – ✅ Aprobado
- **CASO-17**: Estaciones de metro al hacer zoom – ✅ Aprobado
- **CASO-18**: Lugares de interés al hacer zoom – ✅ Aprobado
- **CASO-19**: Parques al hacer zoom – ✅ Aprobado
- **CASO-20**: Mostrar información al hacer clic – ✅ Aprobado
- **CASO-21**: Ocultar información con la "X" – ✅ Aprobado
- **CASO-22**: Activar Street View – ✅ Aprobado
- **CASO-23**: Desactivar Street View – ✅ Aprobado
- **CASO-24**: Mostrar info al hacer clic en el logo – ❌ No aprobado (URB-4)

---

## 📝 Contribuciones y Reportes
Para reportar un bug, utiliza la plantilla [bug_report.md](.github/ISSUE_TEMPLATE/bug_report.md). Para solicitar nuevas funcionalidades o mejoras, utiliza [feature_request.md](.github/ISSUE_TEMPLATE/feature_request.md).

---

> _Desarrollado por JOSE LUIS MOSQUEDA MOLINARI as QA Engineer_
