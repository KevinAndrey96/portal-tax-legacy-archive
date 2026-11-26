# Exclusive Tax Services: app Xamarin del portal de personal (archivo histórico)

![Estado: archivo histórico](https://img.shields.io/badge/Estado-archivo%20hist%C3%B3rico-lightgrey) ![Xamarin.Forms 4.8](https://img.shields.io/badge/Xamarin.Forms%204.8-3498DB) ![C#](https://img.shields.io/badge/C%23-239120) ![Android | iOS](https://img.shields.io/badge/Android%20%7C%20iOS-lightgrey)

> [!NOTE]
> Código original de la app móvil que publicaba el portal web del personal de Exclusive Tax Services en Android e iOS (2020). El producto continúa en **[xamarin-exclusive-tax-services](https://github.com/KevinAndrey96/xamarin-exclusive-tax-services)**, que reúne todos sus componentes con documentación actualizada.

## Qué contiene

- Proyecto compartido `PortalTax` con una `ContentPage` que carga el portal en un `WebView`.
- Proyectos de plataforma `PortalTax.Android` y `PortalTax.iOS` con iconos y configuración de publicación.
- Solución `PortalTax.sln` lista para Visual Studio.

## Stack original

| Componente | Tecnología |
| :--- | :--- |
| Lenguaje | C# (.NET Standard 2.0) |
| UI | Xamarin.Forms 4.8 |
| Plataformas | Xamarin.Android y Xamarin.iOS |

## Ejecutarlo localmente

Abre `PortalTax.sln` en Visual Studio 2019 o 2022 con la carga de trabajo de Xamarin y restaura los paquetes NuGet. Xamarin dejó de tener soporte en mayo de 2024; la versión vigente del producto vive en el monorepo.

## Estado del repositorio

- Se conserva sin cambios funcionales como referencia del código original (2020).
- No recibe actualizaciones de dependencias; el mantenimiento ocurre en [xamarin-exclusive-tax-services](https://github.com/KevinAndrey96/xamarin-exclusive-tax-services).
- En noviembre de 2026 se depuró el historial completo: se retiraron el keystore de firma, 2.900 archivos de `bin/` y `obj/` y el paquete `.aab` publicado. Todos los commits conservan su fecha original.

## Autoría

Kevin Andrey Herrera Silva ([@KevinAndrey96](https://github.com/KevinAndrey96)).

## Licencia

Código desarrollado para un cliente y publicado como muestra de portafolio. No incluye licencia de código abierto: todos los derechos reservados.
