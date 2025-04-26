# README - Refactorización Microservicios

## ¿Qué cambiamos y por qué?

### 1. Mejora de nombres de endpoints y funciones
- **Antes:** Algunos endpoints tenían nombres genéricos o ambiguos.
- **Cambio:** Se actualizaron para ser más descriptivos y seguir convenciones REST.
- **Motivo:** Facilitar la comprensión y mantenimiento del código.

### 2. Reorganización de carpetas por capas
- **Antes:** Los microservicios tenían estructuras planas sin separación clara.
- **Cambio:** Se implementó una división por capas: controladores, servicios, repositorios y dominio.
- **Motivo:** Mejorar la escalabilidad y modularidad del proyecto.

### 3. Limpieza del docker-compose
- **Antes:** Existían dependencias y servicios innecesarios que complicaban el despliegue.
- **Cambio:** Se eliminaron servicios no utilizados y se optimizaron las redes y volúmenes.
- **Motivo:** Acelerar la puesta en marcha y reducir errores de despliegue.

### 4. Documentación mejorada
- **Antes:** La documentación era limitada.
- **Cambio:** Se agregó una descripción breve de cada microservicio y sus endpoints en un archivo README adicional.
- **Motivo:** Facilitar la entrada de nuevos desarrolladores al proyecto.

### 5. Integración de pruebas unitarias
- **Antes:** No había cobertura de pruebas.
- **Cambio:** Se agregaron pruebas unitarias básicas para los servicios más críticos.
- **Motivo:** Mejorar la calidad del software y detectar errores de manera temprana.

---
