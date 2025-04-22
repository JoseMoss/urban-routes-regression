# Informe de Errores - Urban Routes

Este documento contiene los errores encontrados durante la ejecución de las pruebas de regresión en la aplicación Urban Routes. Los errores se detallan con su descripción, pasos a seguir, resultado esperado y resultado actual.

---

## Errores Identificados

### **URB-1**: No se pueden buscar objetos en el campo "HASTA"
- **Pasos a seguir**:
  1. Abre la aplicación Urban Routes: [Urban Routes](https://cnt-60bb0ab7-1f70-405e-80dc-2b30e2f52106.containerhub.tripleten-services.com/)
  2. Haz clic en el campo "HASTA".
  3. Busca un lugar, metro, etc.
- **Resultado esperado**: Muestra el resultado de la búsqueda.
- **Resultado actual**: No pasa nada.
- **Severidad**: Grave

---

### **URB-2**: El campo "DESDE" no está vacío
- **Pasos a seguir**:
  1. Abre la aplicación Urban Routes: [Urban Routes](https://cnt-60bb0ab7-1f70-405e-80dc-2b30e2f52106.containerhub.tripleten-services.com/)
  2. Haz clic en el campo "DESDE".
  3. Ingresa una dirección.
  4. El mapa se enfoca en el pin de la dirección seleccionada.
- **Resultado esperado**: El campo "DESDE" debería estar vacío, y el mapa debe enfocarse en el pin de la dirección seleccionada.
- **Resultado actual**: El campo "DESDE" no está vacío, y el mapa no se enfoca en la dirección seleccionada.
- **Severidad**: Grave

---

### **URB-3**: El pin de la dirección no aparece en el campo "HASTA"
- **Pasos a seguir**:
  1. Abre la aplicación Urban Routes: [Urban Routes](https://cnt-60bb0ab7-1f70-405e-80dc-2b30e2f52106.containerhub.tripleten-services.com/)
  2. Haz clic en el campo "HASTA".
  3. Ingresa una dirección.
- **Resultado esperado**: El mapa debe enfocarse en el pin de la dirección seleccionada y la vista debe coincidir con la descripción del diseño.
- **Resultado actual**: El campo "HASTA" no está vacío, el mapa no se enfoca en el pin de la dirección seleccionada, y la vista no coincide con la descripción del diseño.
- **Severidad**: Grave

---

### **URB-4**: Información de la aplicación no se muestra al hacer clic en el logotipo
- **Pasos a seguir**:
  1. Abre la aplicación Urban Routes: [Urban Routes](https://cnt-60bb0ab7-1f70-405e-80dc-2b30e2f52106.containerhub.tripleten-services.com/)
  2. Haz clic en el logotipo de la app ubicado en la parte superior izquierda.
- **Resultado esperado**: Al presionar el logotipo, debe mostrarse información sobre la aplicación.
- **Resultado actual**: No pasa nada.
- **Severidad**: Menor

---

### **URB-5**: Se puede interactuar haciendo clic en los encabezados del mapa
- **Pasos a seguir**:
  1. Abre la aplicación Urban Routes: [Urban Routes](https://cnt-60bb0ab7-1f70-405e-80dc-2b30e2f52106.containerhub.tripleten-services.com/)
  2. Haz clic en el campo "DESDE".
  3. Busca un lugar, por ejemplo, Hollywood.
  4. Da clic sobre el encabezado.
- **Resultado esperado**: No se debe poder interactuar con los encabezados del mapa.
- **Resultado actual**: Se muestra información de la dirección y se puede interactuar con el encabezado.
- **Severidad**: Moderado

---

### **URB-6**: El modo de vista pantalla completa no permite solicitar transporte
- **Pasos a seguir**:
  1. Abre la aplicación Urban Routes: [Urban Routes](https://cnt-60bb0ab7-1f70-405e-80dc-2b30e2f52106.containerhub.tripleten-services.com/)
  2. Haz clic en el icono del modo de vista pantalla completa en la parte superior derecha.
  3. Intenta solicitar un transporte.
- **Resultado esperado**: El modo de vista pantalla completa está activado, y las pestañas del navegador están ocultas.
- **Resultado actual**: No se puede solicitar transporte desde el modo de vista pantalla completa.
- **Severidad**: Grave

---

### **URB-7**: El campo de búsqueda "Desde" no está vacío
- **Pasos a seguir**:
  1. Abre la aplicación Urban Routes: [Urban Routes](https://cnt-60bb0ab7-1f70-405e-80dc-2b30e2f52106.containerhub.tripleten-services.com/)
  2. Haz clic en el campo "DESDE".
- **Resultado esperado**: Se selecciona el campo "Desde". El cursor parpadea y el campo de búsqueda está vacío.
- **Resultado actual**: El campo de búsqueda "DESDE" no está vacío.
- **Severidad**: Moderado

---

### **URB-8**: La vista satélite no se activa correctamente
- **Pasos a seguir**:
  1. Abre la aplicación Urban Routes: [Urban Routes](https://cnt-60bb0ab7-1f70-405e-80dc-2b30e2f52106.containerhub.tripleten-services.com/)
  2. Pasa el cursor sobre el icono de vista satélite.
  3. Haz clic sobre el icono de vista satélite.
- **Resultado esperado**: El mapa debe mostrar el modo satélite correctamente.
- **Resultado actual**: El modo satélite se activa junto con el modo de etiquetas.
- **Severidad**: Menor

---

## 📌 Conclusión
Se han identificado varios errores graves que afectan la interacción del usuario con la aplicación. Estos problemas deben ser corregidos antes de la próxima versión para asegurar una experiencia de usuario óptima.

