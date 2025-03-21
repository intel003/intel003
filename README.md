# AiFinChain - Aplicación de Finanzas Personales con IA

AiFinChain es una aplicación web de finanzas personales que ayuda a los usuarios a gestionar sus gastos, ahorros e inversiones. La aplicación incluye un asistente de IA que proporciona consejos personalizados basados en los patrones de gasto y objetivos financieros del usuario.

## Características

- Seguimiento de ingresos y gastos
- Categorización automática de transacciones
- Visualización de datos financieros con gráficos
- Establecimiento de metas de ahorro
- Asistente de IA para consejos financieros personalizados
- Diseño responsive para múltiples dispositivos (móvil, tablet, PC)

## Tecnologías utilizadas

- React
- Vite
- Material UI
- Chart.js
- React Router

## Instalación

```bash
# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
npm run dev
```

## Despliegue en GitHub Pages

Para desplegar la aplicación en GitHub Pages, sigue estos pasos:

1. Instala Git si no lo tienes instalado: [Descargar Git](https://git-scm.com/downloads)

2. Inicializa un repositorio Git en la carpeta del proyecto:
   ```bash
   git init
   git add .
   git commit -m "Primer commit"
   ```

3. Crea un nuevo repositorio en GitHub y conecta tu repositorio local:
   ```bash
   git remote add origin https://github.com/tu-usuario/AiFinChain.git
   git branch -M main
   git push -u origin main
   ```

4. Despliega la aplicación en GitHub Pages:
   ```bash
   npm run deploy
   ```

5. Configura GitHub Pages en tu repositorio:
   - Ve a la configuración de tu repositorio en GitHub
   - En la sección "GitHub Pages", selecciona la rama "gh-pages" como fuente
   - Guarda los cambios y espera unos minutos

La aplicación estará disponible en: https://tu-usuario.github.io/AiFinChain/

## Uso

Abre tu navegador y visita `http://localhost:3000` para ver la aplicación en funcionamiento.