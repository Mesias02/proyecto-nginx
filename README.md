# Práctica Servidor Web con Docker y Nginx

## 1. Título
**Configuración de Servidores Web con Nginx en Docker**

---

## 2. Tiempo de duración
**120 minutos**

---

## 3. Fundamentos
En esta práctica aprenderemos a configurar servidores web utilizando Nginx dentro de contenedores Docker. Nginx es un servidor web eficiente y ligero utilizado para servir aplicaciones y manejar cargas de trabajo. Docker, por su parte, facilita la creación de entornos aislados y portables para ejecutar aplicaciones.

### Conceptos clave:
- **Nginx:** Servidor web y proxy inverso.
- **Docker:** Plataforma para contenedores.
- **Contenedores:** Instancias ligeras que aíslan aplicaciones y dependencias.

---

## 4. Conocimientos previos
Para realizar esta práctica, el estudiante necesita:
- Conocer comandos básicos de Linux (como `cd`, `ls`, `nano`).
- Manejo de navegador web.
- Uso básico de Docker (CLI o Desktop).

---

## 5. Objetivos a alcanzar
- Implementar dos contenedores Nginx con configuraciones personalizadas:
  - Un contenedor con datos del Instituto Tecnológico Superior Sudamericano (`nginx1`).
  - Un contenedor con datos personales del estudiante (`nginx2`).
- Manipular y editar archivos HTML directamente dentro de contenedores.

---

## 6. Equipo necesario
- Computador con sistema operativo Windows, Linux o Mac.
- Docker Desktop instalado y funcionando correctamente.
- Conexión a internet para descargar imágenes de Docker.
- Editor de texto (`nano` o similar) instalado dentro del contenedor.

---

## 7. Material de apoyo
- [Documentación oficial de Docker](https://docs.docker.com/)
- [Documentación oficial de Nginx](https://nginx.org/en/docs/)
- Guía de la asignatura proporcionada por el docente.

---

## 8. Procedimiento

### Paso 1: Descargar Docker y verificar instalación
1. Instalar Docker Desktop desde [Docker.com](https://www.docker.com/).
2. Verificar instalación con:
   ```bash
   docker --version

## 9. Resultados esperados
- Nginx1: Página institucional del Instituto Tecnológico Superior Sudamericano, visualizable en http://localhost:8089.
- Nginx2: Página personalizada con datos del estudiante, accesible en http://localhost:8090.

Capturas de pantalla esperadas:
- Figura 1-1: Página del Instituto configurada correctamente.
- ![Captura de pantalla 2025-04-12 095518](https://github.com/user-attachments/assets/f2dbe529-dffe-4e5c-a8d5-8b610dfefe1f)

- Figura 1-2: Página del estudiante con la información personal actualizada.


## 10. Bibliografía
- Docker, Inc. (2025). Docker Documentation. Recuperado de https://docs.docker.com/
- Nginx, Inc. (2025). Nginx Documentation. Recuperado de https://nginx.org/en/docs/



