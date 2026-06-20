# Especificaciones del Banner Profesional

## Dimensiones
- **Tamaño recomendado:** 1500 × 400 px (ratio 3.75:1)
- **Formato:** PNG o JPG
- **Peso máximo:** 1 MB

---

## Concepto visual

### Distribución (de izquierda a derecha)

```
┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│   [BLOQUE IZQUIERDO — 55%]          [BLOQUE DERECHO — 45%]         │
│                                                                     │
│   Gustavo García Carrillo           [Íconos de tecnología en grid] │
│   ─────────────────────             SQL  Python  R                  │
│   Data Analyst · BI · Data Science  PowerBI  Looker  Pandas        │
│                                     VBA  Git  Jupyter               │
│   "Datos → Decisiones"                                              │
│   Estado de México · México         [Línea de código decorativa]   │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

---

## Textos

| Elemento        | Texto                                                   |
|-----------------|---------------------------------------------------------|
| Nombre          | Gustavo García Carrillo                                 |
| Subtítulo       | Data Analyst · Business Intelligence · Data Science     |
| Tagline         | "Datos → Decisiones"                                    |
| Localización    | 📍 Estado de México, México                             |

---

## Paleta de colores

| Rol            | Color       | HEX       |
|----------------|-------------|-----------|
| Fondo          | Azul oscuro | `#0d1117` |
| Texto principal| Blanco      | `#FFFFFF` |
| Acento 1       | Azul        | `#0e75b6` |
| Acento 2       | Cyan claro  | `#58a6ff` |
| Texto secundario| Gris claro | `#8b949e` |
| Separador      | Azul medio  | `#1f6feb` |

---

## Tipografía

- **Nombre:** Inter Bold o Poppins SemiBold, 48–56px, blanco
- **Subtítulo:** Inter Medium, 22px, cyan `#58a6ff`
- **Tagline:** Inter Regular o Italic, 18px, gris claro
- **Código decorativo:** Fira Code o JetBrains Mono, 13px, opacity 40%

---

## Elemento decorativo (bloque derecho)

Badges o íconos de tecnología en un grid 3×3:

```
[ SQL ]    [ Python ]  [ R      ]
[ Power BI][ Looker ] [ pandas ]
[ VBA    ] [ Git    ] [Jupyter ]
```

Estilo: íconos outline o logos oficiales con fondo semitransparente `rgba(14, 117, 182, 0.15)` y borde `#0e75b6` a 1px. Tamaño de ícono: 40×40 px.

---

## Herramientas gratuitas para crearlo

1. **Canva** – canva.com (busca "GitHub Profile Banner" en templates)
2. **Figma** – figma.com (diseño vectorial profesional, gratuito)
3. **Adobe Express** – express.adobe.com (templates editables)

### Proceso en Canva:
1. Nuevo diseño → Tamaño personalizado → 1500 × 400 px
2. Fondo: color sólido `#0d1117`
3. Agrega texto con los datos de arriba
4. Descarga como PNG
5. Sube a tu repo como `/assets/banner.png`

---

## Código HTML para insertar en el README

```markdown
<div align="center">
  <img src="./assets/banner.png" alt="Gustavo García Carrillo – Data Analyst" width="100%" />
</div>
```

O usando URL directa de GitHub:

```markdown
![Banner](https://raw.githubusercontent.com/TU_USUARIO/TU_USUARIO/main/assets/banner.png)
```
