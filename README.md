# 🐶 DogApp - Agenda de Citas para Mascotas

Proyecto del curso **Desarrollo de Aplicaciones para Dispositivos Móviles** de la Universidad del Valle, sede Cali.

## 📱 Descripción

**DogApp** es una aplicación móvil desarrollada en **Kotlin** con **Android Studio**, diseñada para facilitar la gestión de citas veterinarias. A través de un diseño intuitivo y el uso de autenticación biométrica, permite a los administradores registrar, visualizar, editar y eliminar citas de manera eficiente.

## 🎯 Funcionalidades

- 🔐 **Login con huella dactilar**
- 🏠 **Home con lista de citas** (visualización desde base de datos Room)
- 🐾 **Registro de nuevas citas** con datos del dueño, mascota, raza (desde API) y síntoma
- 📋 **Vista detallada de cada cita**
- ✏️ **Edición de citas** ya existentes
- ❌ **Eliminación de citas**
- 🔄 **Consumo de API REST** para razas e imágenes de mascotas
- 🎨 Interfaz inspirada en diseños específicos sin prototipos detallados

## 🧱 Tecnologías Usadas

- Kotlin
- Android Studio
- MVVM
- Room (SQLite)
- Retrofit
- Lottie
- Navigation Component
- Autenticación biométrica

## 📊 Evaluación del proyecto

- 60% Implementación funcional (Room, Retrofit, navegación, etc.)
- 20% Interfaz visual según HU
- 20% Gestión de tareas en JIRA y control de versiones en GitHub

## 🗂 Estructura del Repositorio

```bash
DogApp/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   ├── res/
│   │   │   └── AndroidManifest.xml
├── .gitignore
├── build.gradle
└── README.md
