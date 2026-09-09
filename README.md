<div align="center">

  <img src="public/Logo%20Mi%20Gusto%202025.png" alt="Mi Gusto Logo" width="180" />

  # 🚀 Lanzamiento CRUNCHY Validator

  **Plataforma de validación de códigos promocionales y verificación de beneficios en tiempo real para Mi Gusto.**

  [![Demo Live](https://img.shields.io/badge/🌐_Demo_Live-migusto.com.ar%2Fvalidacion-FF6B6B?style=for-the-badge&logo=googlechrome&logoColor=white)](https://migusto.com.ar/validacion)

  <br />

  ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
  ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
  ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
  ![Supabase](https://img.shields.io/badge/Supabase-%233ECF8E.svg?style=for-the-badge&logo=supabase&logoColor=white)
  ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

</div>

---

## 📌 Descripción General

**Lanzamiento CRUNCHY Validator** es una solución web desarrollada para el departamento de sistemas de **Mi Gusto**, diseñada para validar la autenticidad de los códigos promocionales vinculados al DNI de los clientes durante la campaña especial CRUNCHY. Permite verificar al instante la validez del beneficio, mostrando además información relevante como la sucursal asignada y la fecha de reserva o emisión.

---

## 🖼️ Galería de Imágenes

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <img src="public/CrunchyValidator.Demo.gif" alt="Demostración Interactiva" width="100%" />
      <br />
      <sub><b>🎥 Demostración del Validador</b></sub>
    </td>
    <td width="50%" align="center">
      <img src="public/CRUNCHY.png" alt="Campaña CRUNCHY" width="100%" />
      <br />
      <sub><b>✨ Campaña CRUNCHY</b></sub>
    </td>
  </tr>
</table>

---

## ✨ Características Principales

- 🔍 **Validación Instantánea:** Verificación inmediata combinando código promocional + DNI del cliente.
- ⚡ **Integración con Supabase:** Consultas eficientes y rápidas en tiempo real.
- 🏢 **Información Detallada:** Visualización de sucursal asignada y fecha de reserva/uso del beneficio.
- 🎨 **Interfaz Moderna:** Diseño dinámico, responsivo y adaptado a la identidad corporativa de la marca.
- 🌐 **Despliegue Optimizado:** Configurado para producción en subdirectorio (`/validacion/`) mediante `.htaccess`.

---

## 🔒 Seguridad

- Consultas de solo lectura ejecutadas cliente-servidor mediante clave pública `anon` de Supabase.
- Restricción estricta de permisos de escritura a nivel de cliente.
- Políticas de seguridad por fila (RLS - *Row Level Security*) aplicadas en la base de datos.

---

## 👥 Créditos y Desarrollo

Desarrollado por el **Departamento de Sistemas de Mi Gusto**:

- 👨‍💻 **Facundo Carrizo** — [![GitHub](https://img.shields.io/badge/GitHub-facu14carrizo-181717?style=flat-square&logo=github)](https://github.com/facu14carrizo) [![LinkedIn](https://img.shields.io/badge/LinkedIn-facu14carrizo-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/facu14carrizo)
- 👨‍💻 **Ramiro Lacci** — [![GitHub](https://img.shields.io/badge/GitHub-ramirolacci19-181717?style=flat-square&logo=github)](https://github.com/ramirolacci19) [![LinkedIn](https://img.shields.io/badge/LinkedIn-ramiro--lacci-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/ramiro-lacci)

---

### 📜 Licencia y Propiedad

© 2025 **Mi Gusto** (La Honoria Alimentos S.A. - CUIT: 30-71558654-8). Todos los derechos reservados.  
*Proyecto privado exclusivo para uso comercial de la marca.*
