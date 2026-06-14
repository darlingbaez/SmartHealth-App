# SmartHealth

## Sistema de Gestión de Citas Médicas

## 📌 Descripción
SmartHealth es una aplicación móvil desarrollada para la gestión de citas médicas entre pacientes, médicos y centros de salud. El sistema permite a los usuarios registrarse, iniciar sesión, programar, modificar y cancelar citas médicas de forma digital, mejorando la organización y eficiencia del proceso de atención.

---

## 🛠️ Tecnologías utilizadas
- Flutter
- Dart
- Firebase Authentication
- Cloud Firestore
- Firebase Storage
- GitHub

---

## 🏗️ Arquitectura
Clean Architecture

El proyecto está organizado siguiendo el patrón Clean Architecture, separando la aplicación en capas independientes para mejorar la mantenibilidad, escalabilidad y testabilidad del sistema.

Esto permite dividir claramente:
- Lógica de presentación
- Lógica de negocio
- Acceso a datos

---

## ⚙️ Funcionalidades principales
- Registro e inicio de sesión de usuarios
- Gestión de pacientes
- Programación de citas médicas
- Modificación y cancelación de citas
- Consulta de historial de citas
- Administración de usuarios y horarios médicos

---

## 🎯 Alcance del sistema
El sistema se enfoca únicamente en la gestión de citas médicas.

### ❌ No incluye:
- Videollamadas médicas
- Pagos en línea
- Integración con seguros médicos
- Diagnósticos médicos con inteligencia artificial

---

## 👤 Integrante
Darling Báez


## 📁 Estructura del proyecto
lib/
│
├── core/
│ ├── constants/
│ ├── utils/
│ └── services/
│
├── data/
│ ├── datasources/
│ ├── models/
│ └── repositories/
│
├── domain/
│ ├── entities/
│ ├── repositories/
│ └── usecases/
│
├── presentation/
│ ├── screens/
│ ├── widgets/
│ └── providers/
│
├── shared/
│ ├── themes/
│ └── components/
│
└── main.dart
