# Biblioteca Personal con Autenticación

## Descripción

Aplicación web para la gestión de una biblioteca personal. Permite a los usuarios registrarse, iniciar sesión y gestionar su lista de libros leídos y por leer de manera privada y segura.

---

## Tecnologías utilizadas

- **Frontend:** React, React Router, Context API, CSS
- **Backend:** Node.js, Express, MongoDB, JWT
- **Otros:** Axios (para consumo de API), Mongoose (ODM para MongoDB)

---

## Repositorios base

Podés utilizar los siguientes repositorios como base para tu desarrollo, según el curso realizado:

- **Node (Backend):**  
  [https://github.com/GabrielAlberini/node-curso-darwoft.git](https://github.com/GabrielAlberini/node-curso-darwoft.git)

- **React (Frontend):**  
  [https://github.com/GabrielAlberini/frontend-darwoft](https://github.com/GabrielAlberini/frontend-darwoft)

> Si solo realizaste el curso de React, podés trabajar únicamente con el frontend y utilizar datos mockeados o Firebase como base de datos.  
> Si realizaste ambos cursos (Frontend y Backend), se espera que desarrolles la solución completa utilizando ambos repositorios como punto de partida.

---

## Instalación y ejecución

### 1. Clonar los repositorios

```bash
# Clonar el frontend
git clone https://github.com/GabrielAlberini/frontend-darwoft.git

# Clonar el backend
git clone https://github.com/GabrielAlberini/node-curso-darwoft.git
```

### 2. Instalación de dependencias

#### Frontend

```bash
cd frontend-darwoft
npm install
```

#### Backend

```bash
cd node-curso-darwoft
npm install
```

### 3. Configuración de variables de entorno

#### Backend

Crea un archivo `.env` en la carpeta del backend con la siguiente información (ajusta según tu entorno):

```
MONGO_URI=mongodb://localhost:27017/tu_basededatos
JWT_SECRET=tu_clave_secreta
PORT=4000
```

#### Frontend

Si necesitas configurar la URL de la API, crea un archivo `.env` en la carpeta del frontend:

```
VITE_API_URL=http://localhost:4000
```

### 4. Ejecución de los servidores

#### Backend

```bash
npm run dev
```

#### Frontend

En otra terminal:

```bash
npm run dev
```

---

## Uso

1. Regístrate o inicia sesión.
2. Agrega libros a tu biblioteca personal.
3. Marca libros como leídos o elimínalos.
4. Accede a la página de ajustes para modificar tus datos si lo deseas.

---

## Entrega

Debes entregar el enlace a tu repositorio en el siguiente formulario:  
[@https://forms.gle/KmVd1TK1QdfKtk417](https://forms.gle/KmVd1TK1QdfKtk417)

**Tenés tiempo para hacerlo hasta el 21/07/2025 inclusive.**

---

## Contacto

Ante cualquier duda o consulta, podés escribir a:  
gabialberini733@gmail.com

---

## Licencia

Este proyecto es solo para fines educativos. 