# Design System: Eidon 🌌

## 1. Concepto Visual
**"Adaptive Clarity"**: Una interfaz editorial y limpia que se adapta al entorno del usuario. En ambos modos, la prioridad es el contenido media, utilizando bordes redondeados (`2xl`) y una jerarquía tipográfica clara.

## 2. Paleta de Colores (Theming)

| Elemento | ☀️ Light Mode (Principal) | 🌙 Dark Mode (Soporte) |
| :--- | :--- | :--- |
| **Background** | `#F8FAFC` (Slate-50) | `#0F172A` (Slate-900) |
| **Surface (Cards)** | `#FFFFFF` (Puro) | `#1E293B` (Slate-800) |
| **Text Primary** | `#1E293B` (Slate-800) | `#F8FAFC` (Slate-50) |
| **Text Secondary** | `#64748B` (Slate-500) | `#94A3B8` (Slate-400) |
| **Primary Action** | `#6366F1` (Indigo-500) | `#818CF8` (Indigo-400) |
| **Accent (Teal)** | `#14B8A6` (Teal-500) | `#2DD4BF` (Teal-400) |
| **Borders** | `#E2E8F0` (Slate-200) | `#334155` (Slate-700) |

## 3. Tipografía
- **Main Font:** `Inter` (Sans-serif) - Para legibilidad en cuerpos de texto.
- **Display Font:** `Lexend` - Para identidad de marca, títulos y logotipos.

## 4. Elevación y Sombras
- **Light Mode:** Sombras difusas y suaves (`shadow-xl shadow-slate-200/50`).
- **Dark Mode:** Sin sombras pesadas; la profundidad se genera mediante el color de la superficie (`Surface`) más claro que el fondo.

## 5. Reglas de Interfaz (UI)
- **Border Radius:** `1rem` (16px) para tarjetas; `9999px` para botones tipo píldora.
- **Transiciones:** `cubic-bezier(0.4, 0, 0.2, 1)` con duración de `300ms` para el cambio entre temas.