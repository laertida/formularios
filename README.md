# Formularios básicos

Este repositorio muestra cómo funcionan los formularios de forma básica: estructura HTML, validación simple y manejo de envío con JavaScript. Es un proyecto pequeño pensado para aprender y experimentar.

## Requisitos

- Git
- Visual Studio Code
- (Opcional) Node.js y npm si prefieres servir con un servidor local desde la línea de comandos
- (Opcional) Extensión Live Server para VS Code

## Cómo clonar el repositorio

```bash
git clone https://github.com/laertida/formularios.git
cd formularios
```

## Cómo abrirlo en Visual Studio Code

1. Abre Visual Studio Code.
2. Desde la terminal o el explorador de archivos, ejecuta:

```bash
code .
```

Esto abrirá la carpeta del proyecto en VS Code.

## Servirlo con Live Server (recomendado)

Opción A — Extensión Live Server en VS Code:

1. Instala la extensión "Live Server" (por Ritwick Dey) desde el marketplace de VS Code.
2. Abre el archivo `index.html` (u otro HTML principal).
3. Haz clic en el botón "Go Live" en la barra de estado de VS Code, o haz clic derecho sobre el archivo y selecciona "Open with Live Server".

La extensión abrirá el proyecto en tu navegador y recargará automáticamente cuando guardes cambios.

Opción B — Usando el paquete npm `live-server`:

Si prefieres no usar la extensión, puedes usar el paquete npm:

```bash
npm install -g live-server
# o sin instalar globalmente
npx live-server
```

Esto servirá la carpeta actual en un servidor local y abrirá el navegador.

## Estructura del proyecto (ejemplo)

- index.html  — página principal con el/los formulario(s)
- css/        — estilos
- js/         — scripts de manejo del formulario
- README.md   — este archivo

(La estructura real puede variar según los archivos del repositorio.)

## Uso básico

1. Abre la página `index.html` con Live Server.
2. Rellena los campos del formulario y pulsa "Enviar".
3. Observa la validación del formulario y cómo JavaScript maneja los datos (puede mostrar resultados en la página o en la consola del navegador).

Para depurar, abre las herramientas de desarrollador (F12) y revisa la consola.

## Contribuciones

Si quieres mejorar el proyecto, abre un fork y envía un pull request. Los aportes para mejorar ejemplos, validaciones o documentación son bienvenidos.

