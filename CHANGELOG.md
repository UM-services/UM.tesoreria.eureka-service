# Changelog

Todos los cambios notables en este proyecto serán documentados en este archivo.

El formato está basado en [Keep a Changelog](https://keepachangelog.com/es-ES/1.0.0/),
y este proyecto adhiere a [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.0.2] - 2025-07-20

### Cambiado
- Actualización de Spring Boot de 3.5.0 a 3.5.3
- Actualización del sistema de documentación a GitHub Pages automatizado
- Optimización del Dockerfile para usar multi-stage builds
- Mejora de los workflows de GitHub Actions con nuevas características
- Actualización del sistema de build con JaCoCo para cobertura de código
- Eliminación de scripts Python obsoletos de documentación

### Agregado
- Nuevo sistema de documentación automática con GitHub Pages
- Integración de SonarCloud para análisis de código
- Configuración de JaCoCo para reportes de cobertura

### Mejorado
- Optimización del proceso de build de Docker
- Mejora en la seguridad del contenedor usando usuario no privilegiado
- Documentación técnica y guías de usuario

### Eliminado
- Scripts antiguos de generación de documentación en Python
- Configuraciones obsoletas de Jekyll
- Maven wrapper innecesario

## [0.0.2-SNAPSHOT] - 2025-03-29

### Cambiado
- Actualización de Java de 21 a 24
- Actualización de la imagen base de Docker de eclipse-temurin:21-jre-alpine a eclipse-temurin:24-jre-alpine
- Actualización de la imagen de build de Docker de maven:3-eclipse-temurin-21-alpine a maven:3-eclipse-temurin-24-alpine
- Actualización de GitHub Actions para usar Java 24 