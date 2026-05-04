# CICD-Devops

Un repositorio dedicado a prácticas y configuraciones de **CI/CD (Continuous Integration/Continuous Deployment)** e **infraestructura como código** para ambientes DevOps.

## 📋 Descripción

Este proyecto contiene herramientas, scripts y configuraciones para automatizar procesos de integración continua, despliegue continuo y gestión de infraestructura. Incluye ejemplos de pipelines, configuraciones de contenedores y mejores prácticas de DevOps.

## 🛠️ Composición del Proyecto

El repositorio está compuesto por:

| Lenguaje | Porcentaje |
|----------|-----------|
| **JavaScript** | 68.1% |
| **HTML** | 25.8% |
| **Dockerfile** | 6.1% |

## 🚀 Características

- ✅ Configuraciones de CI/CD
- 🐳 Dockerfiles para containerización
- 📦 Scripts de automatización
- 🔧 Infraestructura como código
- 📊 Pipelines de integración continua

## 📁 Estructura del Proyecto

```
CICD-Devops/
├── README.md           # Este archivo
├── Dockerfile          # Configuración de contenedores Docker
├── scripts/            # Scripts de automatización
├── config/             # Archivos de configuración
└── pipelines/          # Definiciones de pipelines CI/CD
```

## 🔧 Requisitos

- Node.js (para ejecución de scripts JavaScript)
- Docker & Docker Compose
- Git

## 📦 Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/JavierSalazar-2002/CICD-Devops.git
cd CICD-Devops
```

2. Instala las dependencias:
```bash
npm install
```

3. Configura las variables de entorno:
```bash
cp .env.example .env
```

## 🚀 Uso

### Ejecutar Scripts

```bash
npm run build    # Construir el proyecto
npm run test     # Ejecutar pruebas
npm run deploy   # Desplegar
```

### Ejecutar con Docker

```bash
docker build -t cicd-devops .
docker run -d cicd-devops
```

## 🔄 Pipelines CI/CD

Este proyecto está configurado para ejecutar pipelines automáticos en:
- Commits a `main`
- Pull Requests
- Despliegues programados

## 📚 Documentación

Para más información sobre las configuraciones específicas, consulta los archivos de configuración en el repositorio.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Haz un fork del proyecto
2. Crea una rama con tu feature (`git checkout -b feature/AmazingFeature`)
3. Commits con mensajes descriptivos (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto está disponible bajo una licencia abierta. Consulta el archivo LICENSE para más detalles.

## 👤 Autor

**Javier Salazar**
- GitHub: [@JavierSalazar-2002](https://github.com/JavierSalazar-2002)

## 📞 Soporte

Si tienes preguntas o encuentras problemas, abre un [Issue](https://github.com/JavierSalazar-2002/CICD-Devops/issues) en el repositorio.

---

**Última actualización:** Mayo 4, 2026

⭐ Si te resulta útil, considera darle una estrella al repositorio.
