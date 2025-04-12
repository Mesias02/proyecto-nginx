# Práctica Servidor Web con Docker y Nginx

## 1. Título
**Configuración de Servidores Web con Nginx en Docker**
---
![image](https://github.com/user-attachments/assets/9d765b1a-781b-4b92-9db0-56f3475b3c77)


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
Primer comando versión
![image](https://github.com/user-attachments/assets/0b2720a2-5511-4139-8852-aa172847f261) 
Segundo comando docker pull hello-world
![image](https://github.com/user-attachments/assets/8e6a3300-3212-42ff-bf15-4b8a587ec456)
Tercer comando docker images
![image](https://github.com/user-attachments/assets/73320420-49fc-40be-8a5f-cb04e1f3eb4b)
Cuarto comando docker image ls
![image](https://github.com/user-attachments/assets/0ee7b02c-4b5f-46aa-bce6-9776402d9a0c)
Quinto comando docker container run hello-world
![image](https://github.com/user-attachments/assets/f5d86da4-4688-4680-9de8-0e7784cc531c)
Sexto comando docker container ls 
![image](https://github.com/user-attachments/assets/f51ddb3e-ffc8-439f-ab67-f7ceb890728f)
Septimo comando docker container ls -a
![image](https://github.com/user-attachments/assets/cf52e8e9-02de-4a63-8d32-13dac1cea40a)
Octavo comando docker pull nginx
![image](https://github.com/user-attachments/assets/36fe2444-40fd-44c8-9193-9fe239036c86)
![image](https://github.com/user-attachments/assets/0ef5664b-27fb-4ac0-8d6e-0db619c0d883)
Noveno comando docker container run –name web-server nginx
![image](https://github.com/user-attachments/assets/bd1b71a0-df0d-494b-b9eb-d588dd006e85)
Decimo comando docker container run –name web-server detach -d nginx
![image](https://github.com/user-attachments/assets/8c21252f-1379-4fea-a545-e2ee1e0a8af5)
- Manejo de navegador web.
- Uso básico de Docker (CLI o Desktop).
![image](https://github.com/user-attachments/assets/4e3d2779-67d7-4a3e-9df0-b0631b3ed9b5)
![image](https://github.com/user-attachments/assets/4ddcd138-c2c1-49b8-b58b-6b5c4124b731)

---

## 5. Objetivos a alcanzar
- Implementar dos contenedores Nginx con configuraciones personalizadas:
  - Un contenedor con datos del Instituto Tecnológico Superior Sudamericano (`nginx1`).
  - Un contenedor con datos personales del estudiante (`nginx2`).
    ![Captura de pantalla 2025-04-12 080730](https://github.com/user-attachments/assets/60f5f304-570d-49d1-95da-4ee9ee015049)

- Manipular y editar archivos HTML directamente dentro de contenedores.
  ![Captura de pantalla 2025-04-12 094344](https://github.com/user-attachments/assets/e2d7fe73-c507-4e88-a516-6f31860e573a)
  ![Captura de pantalla 2025-04-12 100039](https://github.com/user-attachments/assets/63866971-504d-4d0e-8283-fc437a719b12)


---

## 6. Equipo necesario
- Computador con sistema operativo Windows, Linux o Mac.
- Docker Desktop instalado y funcionando correctamente.
- Conexión a internet para descargar imágenes de Docker.
- Editor de texto (`nano` o similar) instalado dentro del contenedor.
  ![Captura de pantalla 2025-04-12 095954](https://github.com/user-attachments/assets/fd1489fa-a4e2-4cb5-ad29-86096687fd77)
- Guardar cambios en nano
- Presiona CTRL + X para salir.
- Escribe Y para confirmar guardar.
- Presiona Enter para confirmar el nombre.
- Usa exit para salir del contenedor.


---

## 7. Material de apoyo
- [Documentación oficial de Docker](https://docs.docker.com/)
  ![image](https://github.com/user-attachments/assets/e34bfa04-dcba-4219-8c77-56c78adb4e96)
  
  

---

## 8. Procedimiento

### Paso 1: Descargar Docker y verificar instalación
Instalar Docker Desktop desde [Docker.com](https://www.docker.com/).



## 9. Resultados esperados
- Nginx1: Página institucional del Instituto Tecnológico Superior Sudamericano, visualizable en http://localhost:8089.
- Nginx2: Página personalizada con datos del estudiante, accesible en http://localhost:8090.

Capturas de pantalla esperadas:
- Figura 1-1: Página del Instituto configurada correctamente.
- ![Captura de pantalla 2025-04-12 095518](https://github.com/user-attachments/assets/f2dbe529-dffe-4e5c-a8d5-8b610dfefe1f)

- Figura 1-2: Página del estudiante con la información personal actualizada.
![Captura de pantalla 2025-04-12 100304](https://github.com/user-attachments/assets/951d545f-fb62-4202-851c-26213832617c)


## 10. Bibliografía
- Docker, Inc. (2025). Docker Documentation. Recuperado de https://docs.docker.com/
- 
- Nginx, Inc. (2025). Nginx Documentation. Recuperado de https://nginx.org/en/docs/



