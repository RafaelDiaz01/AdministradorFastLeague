# ⚽ **Liga Municipal de Fútbol Rápido - Ixtlán de Juárez**  

**Sistema de Administración Deportiva**  

Bienvenido al repositorio del **AdministradorFastLeague para la Liga Municipal de Fútbol Rápido de Ixtlán de Juárez**. Esta plataforma web optimiza la gestión de jugadores, partidos, estadísticas y torneos, desarrollada con tecnologías **Java EE**.  

---

## 🎯 **Funcionalidades Clave**  

### 👥 **Gestión de Jugadores y Equipos**  
- Registro y perfil de jugadores (datos personales, número, equipo).  
- Visualización de jugadores y equipos.  
- Historial deportivo (goles, tarjetas, asistencias).  

### ⚽ **Control de Partidos**  
- Programación de encuentros (fechas, horarios, arbitro).  
- Registro de resultados en tiempo real.  
- Automatización de tablas de posiciones.  

### 📊 **Estadísticas y Reportes**  
- Líderes de goleo y asistencias.  
- Historial de faltas (amarillas/rojas).  
- Diferencia de Goles.  

### 🏆 **Administración de Torneos**  
- Configuración de fases (torneo regular y liguilla).  
- Cálculo automático de puntuaciones.  
- Visualización de calendario completo.  

---

## 🛠 **Tecnologías Utilizadas**  

| **Categoría**       | **Tecnologías**  
|---------------------|-----------------  
| **Backend**         | Java EE, Servlets, JavaBeans  
| **Frontend**        | JSP, HTML5, CSS3, Bootstrap, JavaScript  
| **Base de Datos**   | MySQL  
| **Servidor**        | Apache Tomcat  
| **IDE**             | NetBeans  
| **Control de Versiones** | Git/GitHub  

---

## 🗂 **Estructura del Proyecto**  

```  
liga-futbol-rapido/  
├── src/  
│   ├── controllers/       # Servlets  
│   ├── models/            # JavaBeans y lógica  
│   └── db/                # Conexión a MySQL  
├── web/  
│   ├── WEB-INF/           # Configuraciones  
│   ├── views/             # JSPs  
│   │   ├── jugadores/  
│   │   ├── partidos/  
│   │   └── usuarios/  
│   └── assets/            # CSS/JS/imágenes  
├── sql/                   # Scripts de base de datos  
└── lib/                   # Dependencias (JDBC, etc.)  
```

---

## 🚀 **Cómo Ejecutar el Proyecto**  

1. **Requisitos Previos**:  
   - Java JDK 11+  
   - Apache Tomcat 9  
   - MySQL 8  
   - NetBeans (opcional)  

2. **Configuración**:  
   ```bash  
   # 1. Clonar repositorio  
   git clone https://github.com/RafaelDiaz01/AdministradorFastLeague.git  

   # 2. Importar base de datos (MySQL)  
   mysql -u usuario -p < sql/ligaMunicipalFutbol.sql  
   ```  

3. **Despliegue**:  
   - Configurar Tomcat en NetBeans.  
   - Ejecutar el proyecto desde el IDE o exportar como WAR.  

---

## 📸 **Capturas de Pantalla**  

| **Inicio de Sesión** | **Registro de Partido** | **Tabla de Posiciones** |  
|----------------------|-------------------------|-------------------------|  
| ![Login](screenshots/login.png) | ![Partido](screenshots/partido.png) | ![Posiciones](screenshots/posiciones.png) |  

---

## 📌 **Aprendizajes Obtenidos**  
✔️ Integración de **JSP + Servlets** con flujo MVC.  
✔️ Uso de **JDBC** para conexiones seguras a MySQL.  
✔️ Diseño de **interfaces intuitivas** para usuarios no técnicos.    

---

## 🤝 **Contribuciones**  
Este proyecto es de código abierto. ¡Aceptamos mejoras en:  
- Implementación de APIs REST.  
- Módulo de streaming en vivo.  
- App móvil complementaria.  

---

## 📜 **Licencia**  
Licencia Universidad de la Sierra Juárez.  

---  

**Desarrollado por [Kevin Rafael Díaz López](https://github.com/RafaelDiaz01) © 2025**  
🏆 *Para la Liga Municipal de Ixtlán de Juárez*  
