<h1 align="center">Hola, soy Héctor Vallés 👋</h1>
<p align="center">
  Estudiante de <b>ASIR</b> · Homelab · Camino a la <b>ciberseguridad</b> 🔐
</p>

<p align="center">
  <a href="https://hvalles.com"><img src="https://img.shields.io/badge/Portfolio-hvalles.com-0A0A0A?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
</p>

---

## 🧑‍💻 Sobre mí

- 🎓 Estudio **Administración de Sistemas Informáticos en Red (ASIR)** , después de cursar 1º de **DAM**.
- 🔐 Mi objetivo es dedicarme profesionalmente a la **ciberseguridad**.
- 🏠 Aprendo practicando: tengo un **homelab** propio donde monto, rompo y aseguro servicios.
- 📍 España.

## 🏠 Homelab

Servidor casero con Ubuntu Server, gestionado solo por SSH y con todo dockerizado:

| Servicio | Para qué lo uso |
|---|---|
| **Pi-hole** | DNS propio y bloqueo de publicidad/rastreadores en toda la red |
| **WireGuard** (wg-easy) | VPN para acceder a la red de casa de forma segura, sin exponer más puertos |
| **Cloudflare Tunnel** | Publicar servicios sin abrir el 80/443 en el router |
| **Caddy** | Servidor web y reverse proxy |
| **Frigate NVR** | Videovigilancia con cámaras IP y detección de objetos |
| **GitHub Actions** (runner self-hosted) | Despliegue automático de mi portfolio |

Enfoque de seguridad: mínima superficie expuesta (un único puerto UDP para la VPN), servicios detrás de Cloudflare y cabeceras de seguridad (CSP) ajustadas.

## 🚀 Proyectos

- 🌐 **[hvalles.com](https://hvalles.com)** — Mi portfolio. React 19 + TypeScript + Vite + Tailwind + Framer Motion + Three.js, autoalojado en mi homelab con CI/CD.
- 🔎 **[GoogleBar](https://github.com/hectoormv/GoogleBar)** — Skin de Rainmeter con una barra de búsqueda de Google al estilo Android, en versión negra y blanca.

## 🛠️ Tecnologías

**Sistemas y redes**
<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
  <img src="https://img.shields.io/badge/Ubuntu_Server-E95420?style=flat-square&logo=ubuntu&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white">
  <img src="https://img.shields.io/badge/Pi--hole-96060C?style=flat-square&logo=pihole&logoColor=white">
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white">
  <img src="https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white">
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white">
</p>

**Desarrollo**
<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB">
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white">
</p>

**Herramientas**
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
  <img src="https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white">
</p>

## 🌱 Próximos pasos

- Profundizar en seguridad ofensiva y defensiva (hardening, redes, análisis de logs)
- Ampliar el homelab: Nextcloud y Cloudflare Zero Trust para los paneles internos
- Seguir documentando todo lo que monto en el portfolio


