# Faradays Components

**Versión:** 0.0.3

### Spinner

El componente `Spinner` es un elemento visual que muestra al usuario que una operación está en progreso y que debe esperar mientras se carga contenido o se completa una acción en segundo plano.

#### Props:

- **`color`** (string): Define el color del loader. Debe ser un valor válido en CSS, como un nombre de color (`"red"`), un valor hexadecimal (`"#3498db"`), o cualquier otro formato de color compatible.
  
- **`size`** (number): Define el tamaño del loader en píxeles. No incluyas la unidad de medida; el valor será automáticamente interpretado como píxeles.

#### Ejemplo de uso:

```jsx
<Spinner color="blue" size={50} />