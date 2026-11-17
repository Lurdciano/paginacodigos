# 📚 Repositorio de Recursos y Proyectos - Análisis Funcional

> **Bitácora y base de conocimientos desarrollada durante la carrera Tecnicatura Superior en Análisis Funcional de Sistemas Informáticos.**

![Estado del proyecto](https://img.shields.io/badge/Estado-En%20Desarrollo%20Activo-orange?style=for-the-badge&logo=git)
![Carrera](https://img.shields.io/badge/Carrera-Tecnicatura%20Superior%20en%20An%C3%A1lisis%20Funcional-blue?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

---

## 📌 Sobre este proyecto

Este repositorio nace con el propósito de centralizar, documentar y tener siempre a mano todo el material práctico recopilado a lo largo del cursado de la carrera:

- **Snippets y código recurrente:** Plantillas de arquitectura multicapa (Entidades, Repositorios, Servicios, Controladores).
- **Resolución de problemas:** Errores habituales surgidos durante el desarrollo y cómo solucionarlos.
- **Consultas SQL:** Prácticas, scripts y sentencias trabajadas en las clases de bases de datos.
- **Proyectos de clase:** Aplicaciones y módulos desarrollados y testeados a lo largo del año.

El repositorio cuenta con una interfaz web estática simple, clara y ligera para facilitar la lectura y consulta rápida desde cualquier navegador.

> ⚠️ **Nota:** Este proyecto se encuentra **en constante evolución y actualización**. A medida que avance el cursado y se desarrollen nuevos contenidos, se continuará completando cada una de las secciones.

---

## 📂 Estructura del Proyecto

```text
PaginaProyectosGitHub/
│
├── index.html          # Panel principal con accesos directos a cada sección
├── styles.css          # Estilos generales (diseño responsive, tarjetas y bloques de código)
│
├── seccion-1.html      # 🧩 Códigos útiles y patrones repetitivos
├── seccion-2.html      # ⚠️ Errores comunes y soluciones aplicadas
├── seccion-3.html      # 🗄️ Consultas MySQL trabajadas en clase
├── seccion-4.html      # 🚀 Proyectos funcionales del cursado
│
├── favicon.svg         # Favicon vectorial (escalable y nítido en alta resolución)
├── favicon.ico         # Favicon multi-resolución (16x16, 32x32, 48x48)
├── favicon-32x32.png   # Favicon estándar para navegadores modernos
├── favicon-16x16.png   # Favicon compacto para pestañas
├── apple-touch-icon.png# Ícono para dispositivos Apple / accesos directos móviles
├── site.webmanifest    # Manifiesto web para Android y navegadores móviles
│
└── README.md           # Documentación general del repositorio
```

---

## 🧭 Contenido de las Secciones

### 🧩 1. Códigos Repetitivos ([`seccion-1.html`](./seccion-1.html))
Recopilación de estructuras base listas para reutilizar, basadas en Java y Spring Boot:
- **Entities:** Modelado de entidades JPA con `@Entity`, `@Table`, claves primarias y relaciones `@ManyToOne`.
- **Controllers:** Manejo de peticiones HTTP, mapeos (`@RequestMapping`, `@GetMapping`, `@PostMapping`), redirecciones y paginación con `PageWrapper`.
- **DAO / Repositories:** Interfaces con `JpaRepository` y consultas personalizadas con JPQL (`@Query`).
- **Services & ServicesImpl:** Separación de lógica de negocio mediante interfaces y sus correspondientes implementaciones transaccionales (`@Service`, `@Transactional`).
- **Clase Main:** Configuración de inicio con `@SpringBootApplication` y `@EnableWebMvc`.

### ⚠️ 2. Errores y Soluciones ([`seccion-2.html`](./seccion-2.html))
Bitácora de fallas técnicas, advertencias y bugs comunes encontrados durante el armado de los proyectos, documentando su causa y la forma en que fueron resueltos.

### 🗄️ 3. MySQL y Consultas SQL ([`seccion-3.html`](./seccion-3.html))
Espacio dedicado a consultas DDL y DML trabajadas en clase: creación de esquemas, relaciones, consultas complejas, `JOINs`, agrupaciones y buenas prácticas de persistencia relacional.

### 🚀 4. Proyectos ([`seccion-4.html`](./seccion-4.html))
Catálogo de proyectos y prácticas que alcanzaron un estado funcional en clase, sirviendo como referencia de implementación completa.

---

## 🛠️ Tecnologías y Herramientas

- **Frontend:** HTML5, CSS3 (CSS Grid, Flexbox, estilos para bloques de código).
- **Backend & Persistencia:** Java, Spring Boot, Spring Data JPA, Hibernate, Jakarta Persistence.
- **Base de Datos:** MySQL / SQL.
- **Control de Versiones:** Git y GitHub.

---

## 🚀 ¿Cómo visualizarlo localmente?

No requiere la instalación de servidores ni dependencias adicionales:

1. Clona este repositorio en tu máquina:
   ```bash
   git clone https://github.com/Lurdciano/paginacodigos.git
   ```
2. Accede a la carpeta del proyecto:
   ```bash
   cd paginacodigos
   ```
3. Abre el archivo `index.html` en tu navegador favorito:
   - En Windows, haz doble clic sobre `index.html` o ejecuta en consola:
     ```bash
     start index.html
     ```

---

## 🗺️ Hoja de Ruta (Roadmap)

- [x] Estructura base de navegación HTML/CSS.
- [x] Carga inicial de plantillas y código recurrente (Entidades, DAO, Servicios, Controladores).
- [ ] Carga y documentación de consultas MySQL realizadas en clase.
- [ ] Documentación detallada de errores comunes y soluciones paso a paso.
- [ ] Enlace y resumen de los proyectos finales de clase.
- [ ] Incorporación de resaltado de sintaxis (Syntax Highlighting) para bloques de código.
- [ ] Publicación en GitHub Pages para consulta online directa.

---

## 🎓 Contexto Académico

- **Carrera:** Tecnicatura Superior en Análisis Funcional de Sistemas Informáticos.
- **Nivel:** 3° Año / Proyectos Integradores de Cursado.

---

*Repositorio mantenido para fines de estudio, consulta rápida y aprendizaje continuo.*
