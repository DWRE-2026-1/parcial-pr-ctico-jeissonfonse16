# Parcial Desarrollo Web con ReactJS
## Ingeniería de Prompts y Maquetación

---

# Iteración 1 – Estructura HTML

## Prompt 1 (Estructura semántica)

Genera la estructura base en HTML5 para un componente de interfaz.

Requisitos técnicos:
- Usar estructura semántica válida (HTML5).
- Incluir etiqueta <main> como contenedor principal.
- Dentro del main, crear una <section> que agrupe el componente.
- Agregar 5 elementos internos usando <div>.
- Asignar clases para facilitar la aplicación de estilos con selectores de clase.
- No aplicar estilos en línea.
- Enlazar correctamente un archivo externo llamado `style.css`.

---

# Iteración 2 – Estilos Base y Box Model

## Prompt 2 (Estilos fundamentales)

Agrega estilos en `style.css` considerando los siguientes criterios técnicos:

- Aplicar reset básico usando selector universal (*).
- Implementar `box-sizing: border-box` para controlar el modelo de caja.
- Eliminar márgenes y paddings por defecto.
- Definir dimensiones usando unidades relativas `rem`.
- Establecer color de fondo para el contenedor principal.
- Aplicar propiedades del Box Model (margin, padding).
- Crear forma tipo cápsula usando `border-radius`.
- Definir tamaño fijo para los elementos internos.

---

# Iteración 3 – Layout con CSS Grid

## Prompt 3 (Maquetación avanzada)

Refina el layout utilizando CSS Grid.

Requisitos técnicos:

- Usar `display: grid`.
- Definir `grid-template-columns` con 3 columnas.
- Usar `gap` para separación uniforme.
- Centrar elementos usando `justify-items`.
- Centrar el contenido verticalmente con `align-content`.
- Replicar exactamente la distribución visual:
  - 3 elementos en la primera fila.
  - 2 elementos centrados en la segunda fila.

---

# Reflexión Técnica

El desarrollo se abordó mediante un proceso iterativo, similar a un ciclo de diseño en ingeniería, donde cada prompt representó una mejora incremental del sistema.

1. En la primera iteración se definió la arquitectura estructural (HTML semántico).
2. En la segunda iteración se implementó la configuración base del sistema visual aplicando el Box Model y unidades relativas (`rem`).
3. En la tercera iteración se optimizó la distribución espacial mediante CSS Grid, logrando precisión en alineación y simetría.

La decisión de utilizar CSS Grid en lugar de Flexbox se tomó debido a la necesidad de controlar filas y columnas explícitamente, lo cual facilita la replicación exacta del patrón 3-2 del diseño.

El uso de `box-sizing: border-box` permitió un control más predecible de dimensiones, mientras que el uso de unidades relativas mejora la escalabilidad del diseño.
