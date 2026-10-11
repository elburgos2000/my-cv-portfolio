# 🌐 Brayan Burgos Palomino | Executive Portfolio & Interactive CV

[![Live Demo](https://img.shields.io/badge/Demo-Cloud%20Run%20Live-22c55e?style=for-the-badge&logo=googlecloud&logoColor=white)](https://my-cv-brayanburgos-izh55vvqnq-ew.a.run.app/)
[![Profile](https://img.shields.io/badge/GitHub-elburgos2000-6366f1?style=for-the-badge&logo=github&logoColor=white)](https://github.com/elburgos2000)
[![Tech Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%20%7C%20Tailwind%20%7C%20Vanilla%20JS-3b82f6?style=for-the-badge)](https://developer.mozilla.org/)

Curriculum Vitae interactivo y portafolio profesional de alto impacto diseñado para **Brayan Burgos Palomino**, Ingeniero de Software & Analista de Inteligencia de Negocios (BI Analyst).

---

## ✨ Características Principales

- **🎨 Diseño Ultra Moderno (Dark Glassmorphism):** Estética ejecutiva con bordes sutiles, desenfoques de fondo (`backdrop-filter: blur`), gradientes pulidos y tipografía Inter.
- **✨ Spotlight Dinámico con Cursor:** Efecto de iluminación interactiva que rastrea el puntero sobre las tarjetas del portafolio.
- **🌐 Selector Bilingüe Instantáneo (ES 🇪🇸 / EN 🇺🇸):** Cambio fluido de idioma en tiempo real sin recargar la página.
- **🗂️ Filtro Interactivo por Categorías:** Clasificación dinámica de proyectos por *Todos*, *Inteligencia de Negocios & Data*, *Ingeniería & IA* y *Desarrollo Web / Móvil*.
- **⚡ Enlaces Directos & One-Click Copy:** Acceso rápido a repositorios de GitHub, descarga de CV en PDF y copiado de correo electrónico al portapapeles con notificación Toast animada.
- **☁️ Despliegue Serverless de Alto Rendimiento:** Contenedor Nginx ultra-ligero (Alpine) desplegado sobre **Google Cloud Run** con escalado automático a cero y compresión Gzip.

---

## 🛠️ Stack Tecnológico

| Capa | Tecnologías |
| :--- | :--- |
| **Frontend** | HTML5 Semántico, Vanilla JavaScript (ES6+), Tailwind CSS, Lucide Icons |
| **Contenedor & Servidor** | Docker, Nginx Alpine, Gzip compression |
| **Infraestructura Cloud** | Google Cloud Run, Google Artifact Registry |
| **Control de Versiones** | Git, GitHub CLI |

---

## 🚀 Despliegue Local & con Docker

### Opción 1: Servir directamente
```bash
# Con Bun
bun x serve .

# O con Python
python -m http.server 8080
```

### Opción 2: Construir y correr con Docker
```bash
docker build -t cv-portfolio .
docker run -p 8080:8080 cv-portfolio
```

---

## ☁️ Despliegue en Google Cloud Run

```bash
gcloud run deploy my-cv-brayanburgos \
  --source . \
  --region europe-west1 \
  --allow-unauthenticated
```

---

## 👨‍💻 Autor

**Brayan Burgos Palomino**  
- **Rol:** Software Engineer & BI Analyst  
- **GitHub:** [@elburgos2000](https://github.com/elburgos2000)  
- **Email:** [motocrossloco@gmail.com](mailto:motocrossloco@gmail.com)  
- **Ubicación:** Bogotá, Colombia  
