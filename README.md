# ¡Hola! Soy MicaA209 👋

### 💻 Técnico en Informática | 🚀 Futuro Ingeniero en Sistemas | ⚙️ Backend Developer & Code Maintainer

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=250&section=header&text=MicaA209%20&fontSize=75&animation=fadeIn" alt="Header" />
</p>

---

## 🚀 Sobre Mí

¡Buenas! Soy **Técnico en Informática** y estudiante avanzado de **Ingeniería en Sistemas**. Mientras que el desarrollo frontend se encarga de que una aplicación entre por los ojos, mi obsesión está en el motor que la mantiene corriendo: el **desarrollo backend**, el **procesamiento eficiente de datos** y el **mantenimiento de código a largo plazo**.

Me apasiona sumergirme en arquitecturas complejas, desarmar cuellos de botella de rendimiento y aplicar ingeniería inversa o refactorización a sistemas heredados (*legacy code*). Creo firmemente que escribir código es fácil, pero escribir código limpio, documentado y mantenible en el tiempo es un arte que requiere verdadera disciplina de ingeniería.

* 🧠 **Mi filosofía:** *"El código se lee 10 veces más de lo que se escribe"*. Priorizo la legibilidad, la modularidad y el desacoplamiento.
* 🛡️ **Mi enfoque:** Minimizar la deuda técnica, optimizar algoritmos y garantizar que el backend sea un muro infranqueable de estabilidad.

---

## 🛠️ Mi Stack Tecnológico & Especializaciones

### 🎯 Lenguajes Core (Backend & Sistemas)

| Lenguaje | Nivel / Enfoque | Ecosistema & Frameworks | Aplicación en Producción |
| :--- | :--- | :--- | :--- |
| **Java** | Avanzado / Arquitectura | Spring Boot, Hibernate, Maven, JUnit | Microservicios, APIs robustas y patrones de diseño empresariales. |
| **C#** | Avanzado / Rendimiento | .NET Core, Entity Framework, LINQ | Servicios de alta disponibilidad, Web APIs y lógica de negocio distribuida. |
| **C++** | Intermedio-Avanzado | STL, Boost, CMake, Google Test | Estructuras de datos puras, optimización de algoritmos y consumo crítico de memoria. |
| **Python** | Avanzado / Scripting | FastAPI, PyTest, Pandas, Asyncio | Automatización de infraestructura, testing, scripts de mantenimiento y ETL. |

### 🧰 Herramientas, Infraestructura y Calidad de Código

* **Bases de Datos:** SQL Server, PostgreSQL, MySQL, Redis (Cacheo de datos).
* **Prácticas de Ingeniería:** SOLID, Clean Code, Test-Driven Development (TDD), Programación Concurrente y Asrincrónica.
* **DevOps & Entornos (Junior/Mantenimiento):** Docker (Contenerización), Git / GitHub Actions (Flujos CI/CD), Linux Server (Bash Scripting).
* **Análisis de Código:** Linters, SonarQube (básico), Profilers de memoria en C++ y .NET.

<p align="left">
  <!-- Lenguajes -->
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <br>
  <!-- Frameworks y BD -->
  <img src="https://img.shields.io/badge/.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="Net Core" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white" alt="Spring" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="Postgres" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
</p>

---

## 📐 Metodología de Trabajo y Buenas Prácticas

Cuando encaro un proyecto o tomo el control de un repositorio existente, sigo un checklist estricto de ingeniería:

1. **Refactorización Segura:** Cobertura de pruebas unitarias (*Unit Testing*) antes de modificar cualquier línea de código heredado para prevenir regresiones.
2. **Desacoplamiento Absoluto:** Separación estricta de responsabilidades utilizando arquitecturas limpias o en capas (Controller -> Service -> Repository).
3. **Optimización de Queries:** No todo es código de aplicación; analizo planes de ejecución en bases de datos relacionales, añado índices y evito el problema de consultas $N+1$.
4. **Documentación Técnica:** Comentarios claros en el *por qué* y no en el *qué*, acompañados de especificaciones OpenAPI/Swagger para las APIs.

---

## 📂 Casos de Estudio y Proyectos Destacados

### 🏢 1. Legacy Clean-Up & API REST Platform (`Java` / `Spring Boot`)
* **Problema:** Un sistema monolítico de gestión empresarial presentaba acoplamiento severo, clases de más de 3000 líneas y caídas por fugas de memoria.
* **Solución:** Lideré la refactorización modular del backend. Apliqué patrones **SOLID** (Inyección de Dependencias, Segregación de Interfaces) y migré la lógica a una arquitectura limpia basada en Spring Boot y PostgreSQL.
* **Resultado:** Reducción del 45% en la tasa de bugs reportados y una mejora notable en los tiempos de respuesta del servidor gracias al correcto manejo de transacciones de base de datos.

### ⚡ 2. Motor de Procesamiento Concurrente de Datos (`C++`)
* **Descripción:** Desarrollo de un motor multihilo de bajo nivel optimizado para el parseo, ordenamiento y filtrado de grandes volúmenes de registros estructurados (.csv/.bin).
* **Detalles Técnicos:** Implementación de *Thread Pools*, exclusión mutua (*mutexes*) para evitar condiciones de carrera, y uso intensivo de punteros inteligentes (`std::unique_ptr`, `std::shared_ptr`) para garantizar cero fugas de memoria (*Memory Leaks*).

### 🤖 3. Automatización de Backups y Pipeline de Monitoreo (`Python` / `.NET`)
* **Descripción:** Un sistema híbrido orientado al mantenimiento de servidores. 
* **Flujo:** Un servicio en segundo plano desarrollado en `C# (.NET)` monitorea la salud del hardware, la memoria y el espacio en disco. Ante cualquier anomalía, dispara scripts en `Python` de manera asincrónica que ejecutan tareas de depuración de logs, compresión y backups automáticos en servidores remotos, notificando mediante Webhooks.

---

## 📈 Mi Camino en la Ingeniería (Roadmap Actual)

Actualmente, además de cursar la carrera de ingeniería, estoy profundizando mis conocimientos de manera autónoma en:
- [🌲] Arquitectura de Microservicios y Patrones de Mensajería (RabbitMQ / Kafka).
- [⚙️] Técnicas avanzadas de Profiling y Tuning de Máquinas Virtuales (JVM y CLR de .NET).
- [☁️] Fundamentos de Cloud Computing (AWS/Azure) enfocados en servicios Backend

---

## 🤝 Hablemos de Código

¿Tenés un sistema con alta deuda técnica que necesite una mano de ingeniería? ¿Una API que requiera optimización o un backend que diseñar desde las bases? Estoy abierto a propuestas de proyectos y debates sobre arquitectura de software.

* ✉️ **Email Profesional:** [micaias.fernandez.09@gmail.com](mailto:micaias.fernandez.09@gmail.com)
---
<p align="center">
  🔧 <i>"Si depurar es el proceso de eliminar errores, entonces programar debe ser el proceso de introducirlos." — Edsger W. Dijkstra</i>
</p>
