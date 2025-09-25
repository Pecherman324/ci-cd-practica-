# Práctica 2: Implementación de CI/CD para una Aplicación Web

## Objetivo
Automatizar el proceso de construcción, prueba, análisis de seguridad y despliegue de una aplicación web utilizando pipelines de CI/CD.

## Estructura del Proyecto
```
ci-cd-practica/
├── app/
│   ├── index.js
│   ├── package.json
│   └── Dockerfile
├── .github/
│   └── workflows/
│       └── ci.yml
├── docker-compose.yml
└── README.md
```

## Instalación y Uso

### Requisitos
- Node.js 18+
- Docker
- Git

### Ejecutar localmente
```bash
cd app
npm install
npm start
```

### Ejecutar con Docker
```bash
docker-compose up --build
```

La aplicación estará disponible en http://localhost:3000

## CI/CD Pipeline
El pipeline automatiza:
- Instalación de dependencias
- Ejecución de pruebas
- Construcción de imagen Docker
- Despliegue del contenedor

## Evidencias
Las capturas de pantalla del pipeline ejecutándose se encuentran en la carpeta `evidencias/`.
