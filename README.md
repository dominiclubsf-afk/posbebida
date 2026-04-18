# EventPOS

Sistema de punto de venta para eventos y noches. Desarrollado para MISOUND / boliche.

## 🚀 App en vivo

👉 **https://TU_USUARIO.github.io/eventpos/**

## ✨ Funcionalidades

- **Roles**: Admin y Cajeros con acceso separado
- **Eventos**: Gestión de noches/eventos
- **Barras**: Múltiples barras con cajeros asignados por barra
- **Stock**: Depósito central → transferencia a barras → control por barra
- **Listas de invitados**: Con QR por persona y consumiciones
- **POS móvil**: Optimizado para celular, funciona offline
- **Reportes**: Por evento, barra, cajero, productos y cierres de caja
- **Cortesías**: Control de consumiciones con validación estricta

## 🗄️ Base de datos

Supabase (PostgreSQL). El schema está en `schema.sql`.

### Setup inicial
1. Crear proyecto en [supabase.com](https://supabase.com)
2. Ir a **SQL Editor** → pegar contenido de `schema.sql` → Run
3. Listo

## 👤 Credenciales por defecto

| Usuario | Contraseña | Rol |
|---------|-----------|-----|
| admin | admin123 | Administrador |

> ⚠️ Cambiar la contraseña del admin después del primer ingreso.

## 📱 Instalar en celular (Android)

1. Abrir la URL en Chrome
2. Menú (⋮) → **Agregar a pantalla de inicio**
3. Se instala como app

## 🛠️ Tecnologías

- HTML + CSS + JS vanilla (single file)
- [Supabase](https://supabase.com) como backend
- GitHub Pages como hosting

## 📂 Archivos

```
eventpos.html   → App completa
schema.sql      → Schema de base de datos
index.html      → Redirect a eventpos.html (GitHub Pages)
README.md       → Este archivo
```
