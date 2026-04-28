# Country Code Selector — React 18 + TypeScript

Aplicación de selección de países con código telefónico, desarrollada
como exploración de arquitectura frontend en React 18 con TypeScript.

## Estructura del proyecto

    src/
    ├── components/       # Librería de componentes UI
    │   ├── button/
    │   ├── card/
    │   ├── input/
    │   ├── layout/
    │   ├── selector/
    │   └── spacer/
    ├── pages/            # Páginas con separación controller/view/styles
    │   ├── countryDetail/
    │   ├── dashboard/
    │   └── notFound/
    ├── theme/            # Sistema de tema centralizado
    │   └── theme.config.ts
    ├── config/           # Configuración global
    ├── modules/          # Módulos de negocio
    └── routes.tsx        # Definición de rutas

## Características técnicas

- Componentización atómica de UI — button, card, input, layout,
  selector y spacer como unidades independientes y reutilizables
- Separación por página en tres capas — controller (lógica),
  page (estructura) y styled (estilos)
- Sistema de tema centralizado — `theme.config.ts` como fuente
  única de tokens de diseño (colores, espaciados)
- TypeScript estricto en componentes y páginas
- Rutas definidas centralizadamente en `routes.tsx`
- Prettier y configuración de linting incluidos

## Stack

- **Framework:** React 18, Vite
- **Lenguaje:** TypeScript
- **Estilos:** Styled Components
- **Herramientas:** Prettier, ESLint

## Contexto

Proyecto de exploración desarrollado en 2022 previo a Aeromexico.
Enfoque en arquitectura de componentes, separación de responsabilidades
y sistema de diseño a nivel programación.
