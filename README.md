# HackatonAppDeUna 🚀

Este proyecto fue desarrollado durante el evento tech Hackathon DEUNA 2025 con un enfoque práctico y demostrativo: integrar agentes de inteligencia artificial para ofrecer a los usuarios una mejor experiencia y un mayor control sobre su gestión financiera personal.

La aplicación busca convertir la interacción financiera en una experiencia más intuitiva, aprovechando asistentes conversacionales y automatización para ayudar al usuario a:
- monitorear sus gastos e ingresos;
- consultar información financiera de manera natural;
- recibir recomendaciones sobre presupuesto y control económico;
- mejorar la toma de decisiones con apoyo de IA.

## Equipo

- Luis Enrique Pérez — desarrollo principal de la aplicación móvil y lógica del proyecto.
- Juan Pachacama — colaboración en desarrollo e integración tecnológica.
- El resto del equipo — diseño de mockup en Figma, vistas, flujo de la experiencia de usuario y apoyo visual.

## Propósito del proyecto

Este fue un proyecto de hackathon, por lo que su objetivo principal fue demostrar cómo los agentes de IA pueden integrarse en una app móvil para ofrecer un mejor control financiero y una experiencia más cercana al usuario. La idea no era solo crear una app funcional, sino explorar la combinación entre React Native, asistentes conversacionales y APIs de modelos de lenguaje para resolver una necesidad real de gestión económica.

## Aplicación y demo

Se construyó una versión de prueba de la aplicación y se publicó un APK para evaluación:

[Descargar APK](https://expo.dev/artifacts/eas/uBcfWAtRDJR5zYdFyxufru.apk)

La aplicación fue pensada para probar su uso sin requerir registro, autenticación ni permisos complejos.

## Requisitos para ejecutar el proyecto

La app fue desarrollada con React Native y Expo. Para ejecutarla localmente, es necesario contar con:
- Node.js actualizado
- npm / npx
- Expo CLI

## Instalación de dependencias

Ejecuta lo siguiente en la carpeta del proyecto:

```bash
npm install -g expo-cli
npm install
```

## Ejecución local

```bash
npx expo start
```

## Instalación en dispositivo

### Emulador Android
- Abrir Android Studio.
- Iniciar un emulador Android.
- En la terminal de Expo, presionar la tecla `a` para abrir la app en el emulador.

### Dispositivo físico
- Instalar la app Expo Go en el celular.
- Escanear el código QR generado por `npx expo start`.
- La aplicación se cargará automáticamente.

## Recomendaciones

- No enviar demasiadas consultas al chatbot para evitar saturar el límite de tokens de la API.
- Este proyecto tiene un enfoque de prototipo y demo, por lo que es importante realizar pruebas y ajustes antes de usarlo en entornos reales o de producción.

## Tecnologías utilizadas

- React Native
- JavaScript / TypeScript
- Expo
- API de Google Gemini

## Consideración final

Este repo representa una propuesta de solución desarrollada en un evento de innovación tecnológica, con la finalidad de mostrar cómo agentes de IA pueden apoyar a las personas en el control de sus finanzas personales de una manera más natural, útil y accesible.
