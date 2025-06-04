# ZenithZone - Electron + TypeScript

Aplicación de escritorio desarrollada con Electron y TypeScript.

## 📁 Estructura del Proyecto

```
ZenithZone/
├── ZenithZone_v1/           # Directorio del proyecto principal
│   ├── src/                 # Código fuente TypeScript
│   ├── dist/                # Archivos compilados
│   ├── node_modules/        # Dependencias
│   ├── package.json         # Configuración del proyecto
│   ├── tsconfig.json        # Configuración TypeScript
│   └── package-lock.json    # Lock de dependencias
├── .gitignore              # Archivos ignorados por Git
├── README.md               # Este archivo
└── LICENSE                 # Licencia del proyecto
```

## 🚀 Comandos de Desarrollo

### Navegar al directorio del proyecto:
```bash
cd ZenithZone_v1
```

### Instalar dependencias:
```bash
npm install
```

### Scripts disponibles:
```bash
# Compilar TypeScript
npm run build

# Ejecutar la aplicación
npm start

# Modo desarrollo (con inspector)
npm run dev

# Limpiar archivos compilados
npm run clean

# Reconstruir desde cero
npm run rebuild
```

## 🛠️ Entorno Configurado

- **Electron**: Framework para aplicaciones de escritorio
- **TypeScript**: Verificación de tipos y autocompletado
- **Seguridad**: Context isolation y node integration deshabilitada
- **DevTools**: Habilitadas para desarrollo

## 🎯 Próximos Pasos

1. Navegar a `ZenithZone_v1/`
2. Instalar dependencias con `npm install`
3. Crear archivos básicos en `src/`:
   - `main.ts`: Proceso principal de Electron
   - `index.html`: Interfaz de usuario
4. Compilar y ejecutar con `npm start`

## 📦 Para Colaboradores

```bash
git clone https://github.com/MarioCanudas/ZenithZone.git
cd ZenithZone/ZenithZone_v1
npm install
npm start
```

¡El entorno está listo para desarrollar! 🎉
