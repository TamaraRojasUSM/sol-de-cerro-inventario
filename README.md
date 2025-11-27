# Sistema de Gestión y Análisis de Inventario - Sol de Cerro 🎶

Proyecto desarrollado para la **Agrupación Social y Cultural Sol de Cerro**  
Taller de Sistemas de Información II - 2025

---

## 🚀 Tecnologías utilizadas
- **Laravel 12** (Framework backend PHP)
- **Laravel Breeze** (Autenticación y CRUD de usuarios)
- **Blade + Alpine.js + Tailwind CSS** (Frontend)
- **MySQL/MariaDB** (Base de datos relacional)
- **Eloquent ORM** (Mapeo objeto-relacional)
- **Git + GitHub** (Control de versiones)

---

## ⚙️ Requisitos previos
- PHP >= 8.2
- Composer
- Node.js + npm
- MySQL/MariaDB
- Git

---

## 📂 Instalación y configuración

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/<TU_USUARIO>/sol-de-cerro-inventario.git
   cd sol-de-cerro-inventario
2. Instalar dependencias de PHP:
    composer install
3. Instalar dependencias de Node:
    npm install
4. Configurar archivo .env:
    APP_NAME="Sol de Cerro Inventario"
    APP_URL=http://localhost:8000

    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=sol_de_cerro
    DB_USERNAME=root
    DB_PASSWORD=

5. Ejecutar migraciones:
    php artisan migrate
6. Levantar servidores:
    php artisan serve   
    npm run dev
