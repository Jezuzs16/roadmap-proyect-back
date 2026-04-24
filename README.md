# ⚙️ Roadmap Tech - API Backend
## 🛠️ Tecnologías a utilizar

* **[Node.js](https://nodejs.org/):** Entorno de ejecución para JavaScript en el servidor.
* **[Express.js](https://expressjs.com/):** Framework para construir nuestra API de forma rápida y organizada.
* **[Prisma ORM](https://www.prisma.io/):** Herramienta moderna para interactuar con la base de datos de forma sencilla (¡adiós al SQL complejo!).
* **[PostgreSQL](https://www.postgresql.org/):** Nuestra base de datos relacional robusta.
* **[dotenv](https://www.npmjs.com/package/dotenv):** Para gestionar variables de entorno de forma segura.

---

## 📋 Requisitos Previos

1.  **Node.js** (Versión 18 o superior).
2.  **PostgreSQL:** Asegúrate de tenerlo instalado y un servidor corriendo localmente (pueden usar pgAdmin o Docker).
3.  **Extensión de Prisma:** Instala la extensión "Prisma" en VS Code para tener resaltado de sintaxis.

---

## 🚀 Configuración del Proyecto

Sigue estos pasos para levantar el servidor en tu máquina:

### 1. Clonar e instalar
```bash
git clone [URL_DEL_REPOSITORIO_BACK_AQUÍ]
cd roadmap-project-back
npm install
```

### 2. Configurar la Base de Datos Local
Crea un archivo llamado `.env` en la raíz del proyecto. Deberás configurar tu URL de conexión local siguiendo este formato:

```env
# Reemplaza 'usuario' y 'password' con tus credenciales de PostgreSQL local
# Por defecto en Windows suele ser usuario: postgres y el password que elegiste al instalar
DATABASE_URL="postgresql://usuario:password@localhost:5432/roadmap_db?schema=public"
PORT=3000
```
Asegurate de llamar a la base de datos `roadmap_db` usando phpmyadmin o psql antes de hacer las migraciones.

