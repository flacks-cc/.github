<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/2e4a7b8c-9d1f-4e3a-b6c7-8d9e0f1a2b3c">
    <img alt="Flack's Cut & Connect" src="https://github.com/user-attachments/assets/1a2b3c4d-5e6f-7a8b-9c0d-1e2f3a4b5c6d" width="100%">
  </picture>
</p>

<h1 align="center">💈 Flack's Cut & Connect — Multiplatform Booking & Commerce Ecosystem</h1>

<p align="center">
  <em>Unified reservations, catalog, and sales platform for barbershops and personal care businesses</em>
</p>

<p align="center">
  <a href="https://github.com/flacks-cc/mobile-app"><img src="https://img.shields.io/badge/Mobile_App-Angular_Ionic-4584FF?logo=ionic&logoColor=white" alt="Mobile App"></a>
  <a href="https://github.com/flacks-cc/web-app"><img src="https://img.shields.io/badge/Web_App-Angular-DD0031?logo=angular&logoColor=white" alt="Web App"></a>
  <a href="https://github.com/flacks-cc/api"><img src="https://img.shields.io/badge/Core_API-Spring_Boot-6DB33F?logo=springboot&logoColor=white" alt="Core API"></a>
  <a href="https://github.com/flacks-cc/mobile-app-android"><img src="https://img.shields.io/badge/Android_App-Java-3DDC84?logo=android&logoColor=white" alt="Android App"></a>
  <a href="https://github.com/flacks-cc/landing"><img src="https://img.shields.io/badge/Website-Visit-4285F4?logo=googlechrome&logoColor=white" alt="Website"></a>
</p>

<p align="center">
  <a href="https://chrisssp.vercel.app/en/projects/flacks-cc">🌐 Visit flacks.cc</a>
</p>

<p align="center">
  <a href="profile/README.md">🇬🇧 English</a> · <a href="profile/README.es.md">🇪🇸 Español</a>
</p>

---

## 🎯 The Challenge

Manual scheduling, scattered customer data, and disconnected sales channels caused double bookings, lost revenue, and low visibility into customer behavior. Flack's Cut & Connect solves this with a unified ecosystem that centralizes reservations, catalog, sales, and staff management, with role-based flows for admins, employees, and customers across web and mobile.

## 🏗 Architecture

```
                    ┌──────────────┐
                    │  Mobile App  │
                    │ (Ionic/Ang.) │
                    ├──────────────┤
                    │ Android App  │
                    │   (Native)   │
                    ├──────────────┤
                    │   Web App    │
                    │   (Angular)  │
                    └──────┬───────┘
                           │
                    ┌──────▼───────┐
                    │  Core API    │
                    │ Spring Boot  │
                    └──────┬───────┘
                           │
                    ┌──────▼───────┐
                    │  PostgreSQL  │
                    └──────────────┘
```

## 📦 Repositories

| Repository | Purpose | Stack | Status |
|------------|---------|-------|--------|
| [mobile-app](https://github.com/flacks-cc/mobile-app) | Customer-facing hybrid PWA | Angular, Ionic, Capacitor | ✅ Active |
| [mobile-app-android](https://github.com/flacks-cc/mobile-app-android) | Native Android experience | Java, Android | ✅ Active |
| [web-app](https://github.com/flacks-cc/web-app) | Admin panel and landing page | Angular, Bootstrap | ✅ Active |
| [web-app-remaster](https://github.com/flacks-cc/web-app-remaster) | Remastered web application | Angular, Bootstrap | ✅ Active |
| [api](https://github.com/flacks-cc/api) | Core REST API | Spring Boot, PostgreSQL | ✅ Active |
| [api-laravel](https://github.com/flacks-cc/api-laravel) | Supplementary Laravel API | PHP, Laravel | ✅ Active |
| [api-iot](https://github.com/flacks-cc/api-iot) | IoT card management API | Java, Spring Boot | ✅ Active |
| [iot-dashboard](https://github.com/flacks-cc/iot-dashboard) | IoT device monitoring dashboard | Angular, TypeScript | ✅ Active |
| [desktop-app](https://github.com/flacks-cc/desktop-app) | Desktop administration app | Java, Swing | ✅ Active |

## 🧠 How It Works

1. **Customers** browse services and products via the mobile app or web-app, book appointments, and manage their reservations
2. **Staff** manage their schedules, process walk-ins, and handle service tickets through the admin panel
3. **Admins** oversee operations, manage inventory, and access reports via the web dashboard
4. **IoT devices** feed real-time data into the dashboard for queue management and service tracking

## 🛡 Privacy & Security

- JWT-based authentication across all platforms
- Role-Based Access Control (RBAC) for staff, admins, and customers
- Encrypted customer data storage
- Secure payment and reservation processing

## 🤝 Contributing

We follow a strict PR-based workflow. Check each repository's `CONTRIBUTING.md` for guidelines.

---

<p align="center">
  <sub>Built with ❤️ by the flacks-cc team · 2026</sub>
</p>