<div align="center">
  <h1>🛒 Destinity - ERP 🛒</h1>
  <p>Sistema ERP modular para la gestión de tiendas de autoservicio, desarrollado con <strong>Jakarta EE</strong>, <strong>Maven</strong>, <strong>MongoDB Atlas</strong> y <strong>JSF</strong>.</p>

![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Jakarta EE](https://img.shields.io/badge/JakartaEE-ED8B00)
![NetBeans](https://img.shields.io/badge/NetBeans-1B6AC6?logo=apache-netbeans-ide&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?logo=apache-maven&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Payara](https://img.shields.io/badge/Payara-0093DD)

</div>

## 🌟 Bienvenido

Este es un sistema **ERP** diseñado para la administración eficiente de una **tienda de autoservicio**. Permite gestionar inventario, ventas, compras, finanzas, analíticas y recursos humanos.  

Está construido utilizando **Jakarta EE**, **MongoDB Atlas** y **JSF Pages** para su interfaz gráfica, siguiendo el modelo **MVC** y principios de **arquitectura limpia**.


## 📂 Módulos Principales

| Módulo              | Descripción                                        |
|---------------------|----------------------------------------------------|
| **Inventario**      | Control y gestión de productos en stock.           |
| **Ventas**          | Registro y seguimiento de transacciones de venta.  |
| **Compras**         | Gestión de pedidos y recepción de productos.       |
| **Finanzas**        | Manejo de ingresos, egresos y reportes financieros.|
| **Analíticas**      | Análisis de datos y generación de reportes.        |
| **Recursos Humanos**| Gestión de empleados y roles dentro del ERP.       |

## 🚀 ¿Cómo ejecutar el ERP?

### 🛠️ Requisitos Previos

- **Java 17+** - Instala el JDK desde [Oracle](https://www.oracle.com/java/technologies/javase-downloads.html).
- **NetBeans 25** - Descarga e instala [Apache NetBeans](https://netbeans.apache.org/).
- **Payara Server 6.2025.2 (Full)** - Configura el servidor [Payara](https://www.payara.fish/downloads/payara-platform-community-edition/).
- **MongoDB Atlas** - Configura tu base de datos en la nube en [MongoDB Atlas](https://www.mongodb.com/atlas).

### 📥 Instalación

1. **Clona el repositorio en tu máquina local:**
   ```bash
   git clone https://github.com/Eddys912/destinity.git
   ```
2. **Abrir el proyecto en NetBeans**:
    - `Archivo` → `Abrir proyecto` → `destinity`.
3. **Configurar credenciales:**
    - Renombrar el archivo `config.example.properties` a `config.example.properties` y configurar las variables para la conexión con Mongo Atlas.
4. **Iniciar Payara:**
    - Ejecuta el servidor desde `NetBeans` o manualmente.
5. **Compilar y Desplegar:**
    - Clic derecho en el proyecto → `Clean and Build`.
    - Clic derecho en el proyecto → `Run`.
6. **Abrir en el navegador:**
    - Accede a `http://localhost:8080/destinity/`.

## 🚀 ¿Cómo Contribuir?

1. **Realiza un Fork** del proyecto haciendo clic en el botón `Fork`.
2. **Realiza los pasos de Instalación.**
3. **Realiza tus cambios**:
   - Guarda los archivos.
   - Crea un commit con una descripción clara:
     ```bash
     git add .
     git commit -m "Descripción de los cambios realizados"
     ```
4. **Envía los cambios** a tu repositorio fork:
   ```bash
   git push origin mi-nueva-funcionalidad
   ```
5. **Abre un Pull Request** 🚀:
   - Dirígete al repositorio original y crea un **Pull Request**.
   - Describe los cambios realizados.
