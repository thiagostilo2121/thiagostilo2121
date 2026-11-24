<div align="center">

# Thiago Valentín Stilo Limarino

### Backend Developer · Python · Próximo ingresante a Ingeniería en Sistemas de Información (UTN)

<p align="center">
  <a href="mailto:stilothiagovalentin@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-blue?style=flat-square&logo=gmail" alt="Email"></a>
  <a href="https://github.com/thiagostilo2121"><img src="https://img.shields.io/badge/GitHub-thiagostilo2121-black?style=flat-square&logo=github" alt="GitHub"></a>
  <a href="https://instagram.com/stilo.tvl"><img src="https://img.shields.io/badge/Instagram-stilo.tvl-E4405F?style=flat-square&logo=instagram" alt="Instagram"></a>
  <img src="https://img.shields.io/badge/Location-Buenos%20Aires%2C%20Argentina-green?style=flat-square" alt="Location">
</p>

<p align="center">
  <a href="https://hub.xerj.org/contributors/thiagostilo2121"><img src="https://hub.xerj.org/contributors/thiagostilo2121/badge.svg" alt="XERJ Corpus Hub contributor"></a>
</p>

<a href="README.en.md">English version</a>

</div>

> **Buscando:** mi primera posición como desarrollador backend, en modalidad remota, part-time desde febrero de 2027.

## 📌 Sobre mí

Desarrollador backend autodidacta de Buenos Aires, Argentina. Trabajo principalmente con Python y me interesan el diseño de sistemas, las APIs y las bases de datos.

Empecé a programar a los ocho años con juegos en PowerPoint, Roblox Studio y Scratch. A los once pasé a Python y desde entonces aprendo de forma independiente, con proyectos propios como principal método de estudio.

Me interesa el contexto donde vive el software: qué problema resuelve una organización, qué restricciones tiene y qué decisiones técnicas y económicas hacen viable la solución.

## 🛠️ Tecnologías y herramientas

| Categoría | Herramientas |
| :--- | :--- |
| **Lenguajes** | `Python` · `Rust` (en aprendizaje) |
| **Backend** | `FastAPI` · `Pydantic` · `SQLAlchemy` · `SQLModel` |
| **Bases de datos** | `PostgreSQL` · `SQLite` · `MySQL` |
| **Migraciones** | `Alembic` |
| **Testing** | `pytest` |
| **CI/CD** | `GitHub Actions` |
| **Documentación** | `Markdown` · `Mermaid` |
| **Entorno** | `Linux` · `Git` · `GitHub` |

> La lista reúne herramientas que usé en proyectos o que estudio activamente. No implica el mismo nivel de dominio en todas.

## 🔬 Proyectos

### 🐏 [RAMTable](https://github.com/thiagostilo2121/ramtable_py): tablas tipadas en memoria para Python

Librería sin dependencias en runtime. Declarás un esquema de columnas y cada fila se valida al insertarse. Los datos viven en memoria, sin SQL ni escritura en disco.

```bash
python -m pip install ramtable
```

```python
from ramtable import Table

people = Table(name="people", columns={"id": int, "name": str, "age": int})
people.rows.insert({"id": 1, "name": "Ada", "age": 36})

older = people.rows.filter({"age": {">": 30}})
print([row["name"] for row in older])
# ['Ada']
```

Publicada en PyPI y TestPyPI, con documentación propia y licencia MIT. La integración continua corre los tests en Python 3.11 a 3.15, construye el wheel y ejecuta el ejemplo de inicio sobre el paquete instalado.

[PyPI](https://pypi.org/project/ramtable/) · [Documentación](https://thiagostilo2121.github.io/ramtable_py/) · [Código](https://github.com/thiagostilo2121/ramtable_py) · [XERJ Corpus Hub](https://hub.xerj.org/corpus/thiagostilo2121--ramtable-py)

### 📚 Contribución al XERJ Corpus Hub

XERJ seleccionó el commit `f4d078b` de RAMTable, «add insert defaults for table columns», como ejemplo de referencia para agentes de IA: 6 archivos y 543 líneas en `tests` y `src/ramtable`. El hub indexa el repositorio completo en ese commit, con licencia MIT y atribución al autor.

[Corpus](https://hub.xerj.org/corpus/thiagostilo2121--ramtable-py) · [Perfil de contribuidor](https://hub.xerj.org/contributors/thiagostilo2121)

### 🪨 PetroLens: asistencia al análisis petrográfico · en desarrollo

Aplicación para asistir en el análisis de cortes delgados de rocas observados al microscopio. Combina procesamiento de imágenes con criterios petrológicos para identificar fases minerales y características texturales, y automatizar parte del trabajo de conteo y descripción.

El diseño separa la aplicación de los modelos de procesamiento, para que las técnicas de análisis puedan cambiar sin reescribir el resto del sistema. El objetivo es complementar el criterio del geólogo, no reemplazarlo.

Aprendo petrología con mi abuelo, [Carlos Oscar Limarino](https://www.researchgate.net/profile/Carlos-Limarino), doctor en Ciencias Geológicas, investigador superior de CONICET y profesor emérito de la UBA, con trayectoria en sedimentología y estratigrafía del Paleozoico. Gracias a eso conozco el problema de primera mano y no desde afuera.

El repositorio es privado mientras el proyecto se define. Puedo mostrar avances, capturas y decisiones de diseño en una conversación.

### 🛒 [Pedilo API](https://github.com/thiagostilo2121/pedilo-api): backend para gestión de pedidos · descontinuado

Backend de una plataforma de pedidos para pequeños negocios gastronómicos. Trabajé sobre autenticación, persistencia, lógica de pedidos y organización general de la aplicación.

Fue mi primera experiencia sosteniendo una aplicación backend completa con una finalidad comercial concreta. El proyecto no continuó, pero marcó el paso de los ejercicios sueltos a un producto con usuarios y necesidades reales.

### 🌐 [OpenArg Backend](https://github.com/colossus-lab/openarg_backend): contribución open source

Escribí la documentación técnica del backend: reorganicé el contenido existente y agregué diagramas Mermaid de arquitectura y de flujo. Dos commits incorporados al repositorio en marzo de 2026.

Fue mi primera contribución sobre una base de código ajena y en un flujo de trabajo colaborativo. Me obligó a leer el sistema antes de escribir sobre él.

[Ver contribuciones](https://github.com/colossus-lab/openarg_backend/commits?author=thiagostilo2121)

## 🤝 Experiencia complementaria

- **Delegado estudiantil (4 años):** representé a los estudiantes ante las autoridades del colegio y coordiné grupos de más de 30 personas.
- **Concejales del Futuro (2025, San Miguel, 2.º puesto):** equipo de cinco personas. Presentamos un proyecto de ordenanza para mejorar nuestro colegio, competimos contra 30 escuelas y ganamos 16 millones de pesos, que destinamos a la construcción de un playón deportivo.
- **Clases particulares (1 año):** Matemática y Contabilidad para estudiantes de secundaria, con 8 alumnos y alrededor de 50 horas de enseñanza.
- **Emprendimiento gastronómico:** con amigos armamos marca, logo, cuenta de Instagram y un plan de crecimiento para vender bizcochuelos. El proyecto no continuó porque el mercado ya tenía competidores establecidos. Ahí aprendí sobre precios, difusión y competencia.

## 🎓 Formación e idiomas

- **Educación secundaria:** orientación en Economía y Gestión de las Organizaciones. Desempeño académico destacado.
- **Distinciones escolares:** Mejor Promedio, Mejor Compañero y abanderado de la bandera provincial.
- **Técnico Informático:** itinerario formativo dentro de la educación secundaria.
- **Educación superior:** ingreso a Ingeniería en Sistemas de Información, Universidad Tecnológica Nacional (UTN), en curso.
- **Español:** nativo.
- **Inglés:** B2 según formación en instituto, sin certificación internacional.

## 🎯 Objetivos profesionales

Quiero mi primera experiencia en backend dentro de un equipo con prácticas establecidas: revisión de código, testing, despliegue y trabajo sobre una base de código compartida.

A mediano plazo busco sumar arquitectura y diseño de sistemas a esa base. A largo plazo, combinar tecnología, análisis y visión de negocio en productos propios.

---

<div align="center">

*Me interesa construir tecnología, pero sobre todo comprender los problemas que hacen necesaria su existencia.*

</div>
