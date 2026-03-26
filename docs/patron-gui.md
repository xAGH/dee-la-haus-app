# Design System & Patrón GUI – App Postventa La Haus

---

## 1. Principios de Diseño

- Claridad sobre complejidad
- Enfoque en trazabilidad y estados
- Consistencia visual en todos los módulos
- Acceso rápido a acciones críticas

---

## 2. Paleta de Colores

### 2.1 Colores Base

| Uso | Color | Hex |
|-----|------|-----|
| Fondo principal | Verde oscuro | #004132 |
| Cards / superficies | Verde oscuro secundario | #173330 |
| Texto principal | Amarillo neón | #e6fa41 |
| Botones principales | Azul | #2596be |

---

### 2.2 Colores de Estado

| Estado | Color sugerido |
|--------|--------------|
| Pendiente | Amarillo (#e6fa41) |
| En proceso | Azul (#2596be) |
| Escalado | Naranja (#ff8c42) |
| Resuelto | Verde claro (#4caf50) |
| Error / Rechazado | Rojo (#e53935) |

---

### 2.3 Uso de Colores

- Fondo general siempre oscuro (#004132)
- Cards ligeramente diferenciadas (#173330)
- Texto principal en alto contraste (#e6fa41)
- Botones con color de acción (#2596be)
- Estados deben destacarse visualmente

---

## 3. Tipografía

### 3.1 Estilo

- Sans-serif moderna (ej: Inter, Roboto)
- Alta legibilidad en móvil

### 3.2 Jerarquía

- Títulos: Bold
- Subtítulos: Medium
- Texto: Regular
- Labels: Light / Medium

---

## 4. Espaciado y Layout

### 4.1 Sistema de Espaciado

- Base: 8px
- Espacios comunes:
  - 8px (mínimo)
  - 16px (estándar)
  - 24px (secciones)
  - 32px (bloques grandes)

---

### 4.2 Layout Base

- Header superior
- Área de contenido scrollable
- Bottom navigation fija

---

## 5. Componentes Base

### 5.1 Cards

Uso:
- Trámites
- Solicitudes
- Resúmenes

Características:
- Fondo: #173330
- Bordes redondeados
- Padding interno consistente
- Jerarquía visual clara

---

### 5.2 Botones

Tipos:
- Primario → #2596be
- Secundario → transparente con borde
- Destructivo → rojo

Estados:
- Normal
- Hover (ligeramente más claro)
- Disabled (opacidad reducida)

---

### 5.3 Inputs

- Bordes suaves
- Fondo ligeramente contrastado
- Estados:
  - Focus
  - Error
  - Completo

---

### 5.4 Badges / Estados

- Forma: píldora o etiqueta
- Color según estado
- Texto corto

---

### 5.5 Listas

- Separación clara entre ítems
- Uso de iconos opcional
- Información jerárquica

---

## 6. Patrón GUI Definido

### 6.1 Estructura General

La aplicación sigue un patrón:

**Dashboard + Bottom Navigation + Sistema basado en estados**

---

### 6.2 Navegación Principal

```plaintext
[ Documentos ] [ Inicio ] [ Solicitudes ]
```