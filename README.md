# Consigna de Proyecto: "Biblioteca Personal con Autenticación"

## Descripción General

Desarrolla una aplicación web para la gestión de una biblioteca personal. El sistema debe permitir a los usuarios registrarse, iniciar sesión y gestionar su lista de libros leídos y por leer de manera privada y segura.

---

## Entrega

En el campo que aparece a continuación podrás entregar el enlace al repositorio del proyecto a desarrollar.  
**Tenés tiempo para hacerlo hasta el 21/07/2025 inclusive.**

---

## 📌 Importante

- **Si realizaste solo el curso de React:**  
  Podés utilizar datos mockeados o Firebase como base de datos.

- **Si participaste de ambos cursos (Frontend y Backend):**  
  Se espera que trabajes en el desarrollo completo: tanto del frontend como del backend.

- **Ante cualquier duda o consulta, podés escribirme a:**  
  gabialberini733@gmail.com

---

## 🔗 Link de la consigna

[https://github.com/GabrielAlberini/consigna-react-node-darwoft.git](https://github.com/GabrielAlberini/consigna-react-node-darwoft.git)

---

## Requisitos del Proyecto

### 1. **Frontend (React)**
- Utiliza React para construir la interfaz de usuario.
- Implementa un sistema de rutas protegidas: solo los usuarios autenticados pueden acceder a la gestión de su biblioteca.
- Permite a los usuarios:
  - Registrarse y autenticarse.
  - Ver su lista de libros leídos y por leer.
  - Agregar nuevos libros a la biblioteca.
  - Marcar libros como leídos o eliminarlos.
  - Acceder a una página de ajustes de usuario.
- Utiliza un contexto global para manejar el estado de autenticación.
- Consume una API REST para todas las operaciones relacionadas con usuarios y libros.

### 2. **Backend (Node.js + Express + MongoDB)**
- Implementa una API RESTful con Node.js y Express.
- Utiliza MongoDB como base de datos.
- Implementa autenticación basada en JWT (JSON Web Tokens).
- Crea modelos para usuarios y libros.
- Protege las rutas de libros para que solo el usuario autenticado pueda acceder a su propia biblioteca.
- Valida los datos de entrada tanto en el registro/login como en la creación/edición de libros.

### 3. **Extras**
- Maneja errores y muestra mensajes claros al usuario.
- Aplica buenas prácticas de organización de código y estructura de carpetas.
- Incluye un archivo README.md con instrucciones para instalar y ejecutar el proyecto.

---

## Entregables

- **Código fuente** del frontend y backend (si corresponde).
- **README.md** elaborado, que incluya:
  - Instrucciones claras y detalladas para instalar y ejecutar ambos servidores (frontend y backend).
  - Descripción general del proyecto.
  - Tecnologías utilizadas.
  - Cualquier otro dato relevante para la correcta ejecución y comprensión del proyecto.

---

## Criterios de Evaluación

- Cumplimiento de los requisitos funcionales.
- Seguridad en la autenticación y protección de rutas.
- Calidad y claridad del código.
- Experiencia de usuario (UX/UI).
- Documentación y facilidad de despliegue.