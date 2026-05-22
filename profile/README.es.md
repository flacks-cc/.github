<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/3dc78378-72c8-44b6-b1ea-9e0ccd7150c5">
    <img alt="Flack's Cut & Connect" src="https://github.com/user-attachments/assets/3dc78378-72c8-44b6-b1ea-9e0ccd7150c5" width="100%">
  </picture>
</p>

<h1 align="center">💈 Flack's Cut & Connect — Ecosistema de Reservas y Comercio Multicanal</h1>

<p align="center">
  <em>Plataforma unificada de reservas, catálogo y ventas para barberías y negocios de cuidado personal</em>
</p>

<p align="center">
  <a href="https://github.com/flacks-cc/mobile-app"><img src="https://img.shields.io/badge/App_M%C3%B3vil-Angular_Ionic-4584FF?logo=ionic&logoColor=white" alt="App Móvil"></a>
  <a href="https://github.com/flacks-cc/web-app"><img src="https://img.shields.io/badge/App_Web-Angular-DD0031?logo=angular&logoColor=white" alt="App Web"></a>
  <a href="https://github.com/flacks-cc/api"><img src="https://img.shields.io/badge/API_Central-Spring_Boot-6DB33F?logo=springboot&logoColor=white" alt="API Central"></a>
  <a href="https://github.com/flacks-cc/mobile-app-android"><img src="https://img.shields.io/badge/App_Android-Java-3DDC84?logo=android&logoColor=white" alt="App Android"></a>
  <a href="https://github.com/flacks-cc/landing"><img src="https://img.shields.io/badge/Sitio_Web-Visitar-4285F4?logo=googlechrome&logoColor=white" alt="Sitio Web"></a>
</p>

<p align="center">
  <a href="https://chrisssp.vercel.app/en/projects/flacks-cc">🌐 Visitar flacks.cc</a>
</p>

<p align="center">
  <a href="README.md">🇬🇧 English</a> · <a href="README.es.md">🇪🇸 Español</a>
</p>

---

## 🎯 El Desafío

La programación manual, los datos de clientes dispersos y los canales de venta desconectados causaban reservas duplicadas, pérdida de ingresos y poca visibilidad del comportamiento del cliente. Flack's Cut & Connect resuelve esto con un ecosistema unificado que centraliza reservas, catálogo, ventas y gestión del personal, con flujos basados en roles para administradores, empleados y clientes en web y móvil.

## 🏗 Arquitectura

```
                    ┌──────────────┐
                    │  App Móvil   │
                    │ (Ionic/Ang.) │
                    ├──────────────┤
                    │ App Android  │
                    │   (Nativa)   │
                    ├──────────────┤
                    │  App Web     │
                    │   (Angular)  │
                    └──────┬───────┘
                           │
                    ┌──────▼───────┐
                    │  API Central │
                    │ Spring Boot  │
                    └──────┬───────┘
                           │
                    ┌──────▼───────┐
                    │  PostgreSQL  │
                    └──────────────┘
```

## 📦 Repositorios

| Repositorio | Propósito | Tecnologías | Estado |
|------------|-----------|-------------|--------|
| [mobile-app](https://github.com/flacks-cc/mobile-app) | PWA híbrida para clientes | Angular, Ionic, Capacitor | ✅ Activo |
| [mobile-app-android](https://github.com/flacks-cc/mobile-app-android) | App Android nativa | Java, Android | ✅ Activo |
| [web-app](https://github.com/flacks-cc/web-app) | Panel admin y landing page | Angular, Bootstrap | ✅ Activo |
| [web-app-remaster](https://github.com/flacks-cc/web-app-remaster) | App web remasterizada | Angular, Bootstrap | ✅ Activo |
| [api](https://github.com/flacks-cc/api) | API REST principal | Spring Boot, PostgreSQL | ✅ Activo |
| [api-laravel](https://github.com/flacks-cc/api-laravel) | API complementaria Laravel | PHP, Laravel | ✅ Activo |
| [api-iot](https://github.com/flacks-cc/api-iot) | API de gestión de tarjetas IoT | Java, Spring Boot | ✅ Activo |
| [iot-dashboard](https://github.com/flacks-cc/iot-dashboard) | Dashboard de monitoreo IoT | Angular, TypeScript | ✅ Activo |
| [desktop-app](https://github.com/flacks-cc/desktop-app) | App de escritorio administrativa | Java, Swing | ✅ Activo |

## 🧠 Cómo funciona

1. **Clientes** exploran servicios y productos mediante la app móvil o web, reservan citas y gestionan sus reservas
2. **Empleados** administran sus horarios, procesan visitas sin cita y manejan tickets de servicio desde el panel admin
3. **Administradores** supervisan operaciones, gestionan inventario y acceden a reportes via el dashboard web
4. **Dispositivos IoT** alimentan datos en tiempo real al dashboard para gestión de colas y seguimiento de servicios

## 🛡 Privacidad y Seguridad

- Autenticación JWT en todas las plataformas
- Control de acceso basado en roles (RBAC) para empleados, admins y clientes
- Datos de clientes cifrados
- Procesamiento seguro de pagos y reservas

## 🤝 Contribuciones

Seguimos un flujo de trabajo estricto basado en PRs. Revisa el `CONTRIBUTING.md` de cada repositorio para las guías.

---

<p align="center">
  <sub>Hecho con ❤️ por el equipo flacks-cc · 2026</sub>
</p>
