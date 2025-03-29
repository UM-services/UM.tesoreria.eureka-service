# Changelog

Todos los cambios notables en este proyecto serán documentados en este archivo.

El formato está basado en [Keep a Changelog](https://keepachangelog.com/es-ES/1.0.0/),
y este proyecto adhiere a [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.0.1-SNAPSHOT] - 2024-02-15

### Cambiado
- Actualización de Java de 21 a 24
- Actualización de Spring Boot de 3.4.3 a 3.4.4
- Actualización de Spring Cloud de 2024.0.0 a 2024.0.1
- Actualización de la imagen base de Docker de eclipse-temurin:21-jre-alpine a eclipse-temurin:24-jre-alpine
- Actualización de la imagen de build de Docker de maven:3-eclipse-temurin-21-alpine a maven:3-eclipse-temurin-24-alpine

### Agregado
- Configuración inicial del proyecto
- Servidor Eureka con configuración básica
- Integración con Spring Cloud
- Configuración de Actuator para monitoreo
- Implementación de Caffeine Cache
- Documentación inicial del proyecto
- Scripts de generación de documentación
- Configuración de GitHub Pages
- Configuración de GitHub Actions

### Corregido
- Problemas de logging con commons-logging
- Configuración de caché para producción

### Seguridad
- Implementación de endpoints seguros para Actuator
- Configuración de autenticación básica 