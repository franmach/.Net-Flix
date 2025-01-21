# Aplicación Multiplataforma para Cines Privados

Esta aplicación multiplataforma está diseñada para una cadena de cines privados de streaming. Facilita la gestión de sucursales, la búsqueda y visualización de películas, y la administración de perfiles de usuarios, integrando características como autenticación personalizada y mapas interactivos.

---

## Tabla de Contenidos
1. [Descripción General](#descripción-general)
2. [Tecnologías Utilizadas](#tecnologías-utilizadas)
3. [Características](#características)
4. [Instalación](#instalación)
5. [Uso](#uso)
6. [Capturas de Pantalla](#capturas-de-pantalla)
7. [Contribuciones](#contribuciones)
8. [Contacto](#contacto)

---

## Descripción General
Esta aplicación tiene como objetivo principal proporcionar una plataforma integral que mejore la experiencia de los usuarios al interactuar con el catálogo de películas y sucursales. Los usuarios pueden buscar películas, marcarlas como favoritas, y gestionar sus perfiles con opciones avanzadas de autenticación. Además, incorpora un mapa interactivo para localizar y gestionar las sucursales de manera eficiente, mostrando la ruta más corta hacia ellas.

El proyecto utiliza tecnologías modernas y un enfoque multiplataforma, permitiendo su ejecución en Android, iOS y Windows desde una única base de código.

---

## Tecnologías Utilizadas
- **Lenguajes:** C#, XAML.
- **Framework:** .NET MAUI.
- **Bases de Datos:** SQLite.
- **APIs:** The Movie Database (TMDb), API de Geocodificación de Google.
- **Patrón de Diseño:** MVVM (Modelo-Vista-ViewModel).

---

## Características
- **Gestión de películas:** Búsqueda, filtrado y marcación de películas como favoritas.
- **Mapas interactivos:** Visualización y gestión de sucursales con cálculo de rutas en tiempo real.
- **Autenticación personalizada:**
  - Huella dactilar en dispositivos Android.
  - Email y contraseña en dispositivos Windows.
- **Gestión de usuarios:** Creación y edición de perfiles de usuario.
- **Persistencia de datos:** Almacenamiento local con SQLite.

---

## Instalación
1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/aplicacion-cine.git
   ```
2. Configura el entorno:
   - Instala las dependencias necesarias para .NET MAUI.
   - Asegúrate de tener SQLite configurado en tu dispositivo.

3. Ejecuta el proyecto:
   ```bash
   dotnet build
   dotnet run
   ```

4. Abre la aplicación en el dispositivo deseado (Android, iOS o Windows).

---

## Uso
- **Mapa interactivo:** Agrega sucursales con su dirección y calcula rutas hacia ellas.
- **Gestión de películas:** Accede a información actualizada mediante la API de TMDb.
- **Gestión de usuarios:** Regístrate o inicia sesión para personalizar tu experiencia.

---

## Capturas de Pantalla

---

## Contribuciones
Este proyecto fue desarrollado como parte de un curso académico y no está abierto a contribuciones externas.

---

## Contacto
Para más información, contacta a Francisco Machado en [franmach20@outlook.com](mailto:franmach20@outlook.com).
