# 🎮 Tutorial: Minecraft 1.20.1 con Forge y Pack de Mods Dinamize

## 📋 Requisitos Previos

- **Minecraft Java Edition** comprado y funcionando
- **Java 17 o superior** instalado en tu sistema
- Conexión a internet estable
- Al menos 4GB de RAM libre

---

## 🔧 Paso 1: Instalación de Minecraft Forge 1.20.1

### 1.1 Descargar Forge
1. Ve a la página oficial: [https://files.minecraftforge.net/](https://files.minecraftforge.net/)
2. Selecciona la versión **1.20.1**
3. Descarga la versión **Recommended** (47.4.0 o superior)
4. Guarda el archivo `forge-1.20.1-47.4.0-installer.jar` en tu escritorio

### 1.2 Instalar Forge
1. **Cierra Minecraft Launcher** si está abierto
2. Haz **doble clic** en el archivo `forge-1.20.1-47.4.0-installer.jar`
3. En la ventana que se abre:
   - Selecciona **"Install client"**
   - Deja la ruta por defecto
   - Haz clic en **"OK"**
4. Espera a que termine la instalación
5. Verás un mensaje de **"Successfully installed client profile"**

### 1.3 Verificar Instalación
1. Abre **Minecraft Launcher**
2. En el menú desplegable de versiones, deberías ver **"forge-1.20.1-47.4.0"**
3. Selecciona esta versión y dale **"Play"**
4. Una vez que cargue el juego, verás **"Forge"** en la esquina inferior izquierda

---

## 📁 Paso 2: Localizar la Carpeta de Mods

### 2.1 Encontrar la Carpeta .minecraft
#### En Windows:
1. Presiona `Windows + R`
2. Escribe: `%appdata%\.minecraft`
3. Presiona Enter

#### Método alternativo:
1. Abre Minecraft Launcher
2. Ve a **"Installations"**
3. Haz clic en los **tres puntos** junto a la instalación de Forge
4. Selecciona **"Open folder"**

### 2.2 Crear Carpeta de Mods
1. Dentro de la carpeta `.minecraft`, busca la carpeta **"mods"**
2. Si no existe, créala haciendo clic derecho → **"Nueva carpeta"** → nombrarla **"mods"**

---

## 📦 Paso 3: Instalación del Pack de Mods Dinamize

### 3.1 Lista de Mods Incluidos

| Mod | Versión | Descripción |
|-----|---------|-------------|
| **AppleSkin** | 2.5.1 | Muestra información nutricional detallada |
| **Carry On** | 2.1.2.7 | Permite cargar bloques y entidades |
| **Cobweb** | 1.0.1 | Mejoras para las telarañas |
| **Farmer's Delight** | 1.2.8 | Expande el sistema de comida y agricultura |
| **FerriteCore** | 6.0.1 | Optimización de memoria |
| **Framework** | 0.7.15 | Librería base para otros mods |
| **Harvest with Ease** | 9.4.0 | Facilita la cosecha de cultivos |
| **Jade** | 11.13.1 | Muestra información de bloques y entidades |
| **JEI** | 15.20.0.110 | Visor de recetas y objetos |
| **Mantle** | 1.11.63 | Librería requerida para Tinkers' Construct |
| **Mouse Support** | 1.2.7 | Soporte mejorado para ratón |
| **Nature's Compass** | 1.11.2 | Brújula para encontrar biomas |
| **OptiFine** | HD_U_I6 | Optimización gráfica y shaders |
| **Refurbished Furniture** | 1.0.14 | Añade muebles decorativos |
| **Starlight** | 1.1.2 | Optimización del sistema de luz |
| **Tinkers' Construct** | 3.10.1.76 | Sistema avanzado de herramientas |
| **WI Zoom** | 1.5 | Función de zoom |
| **Xaero's Minimap** | 25.2.6 | Minimapa avanzado |

### 3.2 Instalación de Mods
1. **Descarga todos los archivos .jar** de los mods listados arriba
2. **Copia todos los archivos .jar** a la carpeta `mods` que creaste
3. **NO descomprimas** los archivos .jar, deben permanecer comprimidos

### 3.3 Estructura Final
Tu carpeta `mods` debe contener estos archivos:
```
mods/
├── appleskin-forge-mc1.20.1-2.5.1.jar
├── carryon-forge-1.20.1-2.1.2.7.jar
├── cobweb-forge-1.20.1-1.0.1.jar
├── FarmersDelight-1.20.1-1.2.8.jar
├── ferritecore-6.0.1-forge.jar
├── framework-forge-1.20.1-0.7.15.jar
├── harvest-with-ease-forge-1.20.1-9.4.0.jar
├── Jade-1.20.1-Forge-11.13.1.jar
├── jei-1.20.1-forge-15.20.0.110.jar
├── Mantle-1.20.1-1.11.63.jar
├── mss-1.2.7-1.20.jar
├── NaturesCompass-1.20.1-1.11.2-forge.jar
├── OptiFine_1.20.1_HD_U_I6.jar
├── refurbished_furniture-forge-1.20.1-1.0.14.jar
├── starlight-1.1.2+forge.1cda73c.jar
├── TConstruct-1.20.1-3.10.1.76.jar
├── WI-Zoom-1.5-MC1.20.1-Forge.jar
└── Xaeros_Minimap_25.2.6_Forge_1.20.jar
```

---

## 🚀 Paso 4: Configuración de Memoria (Recomendado)

### 4.1 Asignar más RAM
1. En Minecraft Launcher, ve a **"Installations"**
2. Haz clic en los **tres puntos** junto a la instalación de Forge
3. Selecciona **"Edit"**
4. Haz clic en **"More Options"**
5. En **"JVM Arguments"**, cambia `-Xmx2G` por `-Xmx4G` (o más si tienes RAM disponible)
6. Guarda los cambios

---

## ✅ Paso 5: Primera Ejecución

### 5.1 Iniciar el Juego
1. Selecciona el perfil **"forge-1.20.1-47.4.0"**
2. Haz clic en **"Play"**
3. **La primera carga será lenta** (puede tomar varios minutos)
4. Verás una pantalla de carga con el logo de Forge

### 5.2 Verificar Mods
1. Una vez en el menú principal, haz clic en **"Mods"**
2. Deberías ver **18 mods** cargados
3. Si algún mod aparece en rojo, hay un problema de compatibilidad

---

## 🎯 Características Principales del Pack

### 🍽️ **Farmer's Delight**
- Nuevos cultivos y comidas
- Sistema de cocina avanzado
- Herramientas de granja mejoradas

### 🔧 **Tinkers' Construct**
- Crea herramientas personalizadas
- Sistema de fundición
- Mejoras y modificaciones de herramientas

### 🗺️ **Xaero's Minimap**
- Minimapa en tiempo real
- Waypoints y marcadores
- Mapa del mundo completo

### 👀 **Jade + JEI**
- Información detallada de bloques
- Recetas y usos de todos los objetos
- Interfaz intuitiva y útil

---

## 🔧 Solución de Problemas

### ❌ El juego no inicia
- **Verifica Java**: Asegúrate de tener Java 17+
- **Revisa la RAM**: Asigna al menos 4GB
- **Logs**: Revisa el archivo `latest.log` en `.minecraft/logs/`

### ❌ Mods no cargan
- **Versión correcta**: Todos los mods deben ser para 1.20.1 Forge
- **Dependencias**: Algunos mods requieren otros (ej: TConstruct necesita Mantle)
- **Archivos .jar**: No descomprimas los mods

### ❌ Baja performance
- **OptiFine**: Configura las opciones gráficas
- **FerriteCore**: Ya incluido para optimización
- **RAM**: Asigna más memoria si es necesible

### ❌ Crash al iniciar
1. Elimina todos los mods de la carpeta `mods`
2. Añádelos de uno en uno para identificar el problemático
3. Verifica que todas las dependencias estén instaladas

---

## 📞 Soporte

Si tienes problemas:
1. **Revisa los logs** en `.minecraft/logs/latest.log`
2. **Verifica compatibilidad** de versiones
3. **Busca en foros** como r/feedthebeast o MinecraftForge

---

## ⚡ Consejos Adicionales

### 🎮 Controles Útiles
- **F1**: Ocultar/mostrar interfaz
- **F3**: Información de debug
- **Zoom**: Botón configurable (WI Zoom)
- **Minimapa**: M para abrir mapa completo

### 🔄 Actualizaciones
- **Siempre respalda** tu mundo antes de actualizar mods
- **Verifica compatibilidad** entre versiones
- **Lee los changelogs** antes de actualizar

### 🌍 Mundos Recomendados
- **Survival normal**: Para disfrutar todas las características
- **Creative**: Para probar mods nuevos
- **Superflat**: Para construcciones con Refurbished Furniture

---

## 🎉 ¡Disfruta del Juego!

Ya tienes instalado el pack completo de mods Dinamize para Minecraft 1.20.1. Este pack está diseñado para mejorar la experiencia de supervivencia con nuevas mecánicas, optimizaciones y herramientas útiles.

**¡Que tengas una excelente aventura en Minecraft!** 🚀

---

*Tutorial creado para el Pack de Mods Dinamize - Minecraft 1.20.1 Forge*
