# 🚀 GitHub Actions Deployment Challenge: De Cero a Pipeline de 3 Jobs

<br/>

<img width="178" height="178" alt="WhatsApp Image 2026-04-25 at 10 51 43 AM" src="https://github.com/user-attachments/assets/13339401-2365-4213-9f5b-43feb63d042b" /><br><sub> Rider Alberto Diaz Quintero</sub>

- rideralbertodiaz1210@gmail.com

<hr>


## 🔗 Despliegues en Vivo (Demos)

| Desafío | Tipo | Estado del Pipeline | Enlace de Despliegue |
| :--- | :--- | :--- | :--- |
| **H-1** | Estático básico | ![Success](https://img.shields.io/badge/Pipeline-Success-brightgreen) | https://github.com/RiderDiaz2/hack_github1_actions_3|
| **H-2** | Dual Job (CI/CD) | ![Success](https://img.shields.io/badge/Pipeline-Success-brightgreen) | https://github.com/RiderDiaz2/hack_github2_actions_3|
| **H-3** | React + Multi-Job | ![Success](https://img.shields.io/badge/Pipeline-Success-brightgreen) |https://github.com/RiderDiaz2/hack_github3_actions_3 |

¡Bienvenido! Este repositorio recopila la resolución de los tres desafíos prácticos de **Integración y Despliegue Continuo (CI/CD)** implementando **GitHub Actions** y desplegando proyectos estáticos y en **React** hacia **GitHub Pages**.

---

## 🛠️ Tecnologías y Conceptos Clave
* **Entornos de ejecución:** Linux (Ubuntu Runners) & Windows Subsystem for Linux (WSL).
* **Control de Versiones:** Git & GitHub.
* **Gestor de versiones de Node:** FNM (Fast Node Manager) para un entorno aislado sin permisos de superusuario.
* **CI/CD:** Pipelines estructurados en YAML, variables de entorno, artefactos de build y concurrencias de despliegue.

---

## 📂 Estructura del Repositorio
Cada desafío cuenta con su propio workflow de automatización que gestiona el ciclo de vida del código:

```text
📁 hack_github_actions_3/
├── .github/workflows/
│   └── deploy.yml          # Workflow de integración, construcción y despliegue secuencial
├── package.json            # Configuración de dependencias de la App de React
├── vite.config.js          # Configuración base para ajustar rutas relativas en GitHub Pages
├── index.html              # Punto de entrada de la aplicación
└── src/                    # Código fuente en React
