# 🌿 Gentleman Biome

Un proyecto educativo que muestra el proceso de migración desde ESLint + Prettier hacia Biome,
implementando las mejores prácticas de linting y formateo de código en un entorno React moderno.

## 🎯 Propósito del Proyecto

Este repositorio sirve como guía práctica para:

- 🔄 Migrar progresivamente desde ESLint + Prettier hacia Biome
- ⚙️ Configurar Biome con reglas optimizadas para TypeScript y React
- 🧪 Comparar el rendimiento y las capacidades de ambas soluciones

## ⚡ Stack Tecnológico

- 🌿 [Biome](https://biomejs.dev/) v1.9.4 - Linter y formateador todo en uno
- ⚛️ [React](https://reactjs.org/) v18.2 - Biblioteca UI con componentes y hooks
- 🚀 [Rspack](https://www.rspack.dev/) v1.2.2 - Bundler ultra rápido escrito en Rust
- 📦 [TypeScript](https://www.typescriptlang.org/) v5.7 - JavaScript con tipado estático
- 🏎️ [Bun](https://bun.sh/) - Runtime y gestor de paquetes ultrarrápido

## 🚀 Empezando

### Prerrequisitos

- [Bun](https://bun.sh/) (versión 1.0 o superior)
- Alternativamente: Node.js (versión 18 o superior)

### Instalación

1. Clona el repositorio:

```bash
git clone https://github.com/gentelman-programming/gentleman-biome.git
cd gentleman-biome
```

## 🔄 Estado de la Migración

Actualmente el proyecto se encuentra en proceso de migración:

- ✅ Configuración inicial de Biome
- ✅ Reglas personalizadas para TypeScript y React
- 🚧 Migración de scripts (aún usando ESLint y Prettier)
- 📝 Documentación del proceso

## ⚙️ Configuración de Biome

El proyecto ya incluye una configuración completa de Biome en `biome.json` con:

```json
{
  "formatter": {
    "enabled": true,
    "indentStyle": "space",
    "indentWidth": 2,
    "lineWidth": 80
  },
  "organizeImports": {
    "enabled": true
  },
  "javascript": {
    "formatter": {
      "quoteStyle": "double",
      "trailingCommas": "all"
    }
  }
}
```

### 🔍 Reglas de Linting Personalizadas

La configuración de Biome incluye reglas personalizadas para diferentes categorías:

- **Accesibilidad (a11y)**: Garantiza que el código sea accesible
- **Complejidad**: Evita prácticas que aumentan la complejidad del código
- **Corrección**: Detecta y previene errores comunes
- **Seguridad**: Identifica posibles problemas de seguridad
- **Estilo**: Mantiene un estilo de código consistente
- **Sospechoso**: Detecta código que podría causar problemas

Además, incluye configuraciones específicas para archivos TypeScript:

- Reglas como `noArguments`, `noVar` y `useConst`
- Desactivación de reglas redundantes con TypeScript

## 📝 Scripts Actuales

```bash
# Desarrollo
bun dev      # Inicia el servidor de desarrollo con Rspack

# Producción
bun build    # Construye la aplicación para producción

# Calidad de código (aún usando ESLint/Prettier)
bun format   # Formatea el código con Prettier
bun lint     # Verifica el código con ESLint
```

## 📦 Configuración de TypeScript

El proyecto usa TypeScript con una configuración moderna:

- Target: ES2020
- JSX: react-jsx
- Strict mode activado
- Resolución de módulos: bundler
- Integración con Rspack

## 📜 Licencia

Este proyecto está bajo la Licencia MIT - mira el archivo [LICENSE](LICENSE) para
más detalles.

## ✨ Agradecimientos

- [Biome](https://biomejs.dev/) - El futuro del linting y formateo
- [ESLint](https://eslint.org/) y [Prettier](https://prettier.io/) - Por pavimentar el camino
- [Comunidad Gentleman Programming](https://discord.gg/gentleman-programming) - Por el feedback constante

---

Desarrollado con ❤️ por [Gentleman Programming](https://github.com/gentelman-programming)
