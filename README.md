#  Misión MongoDB: El Bestiario Digital

## Nombre: Jennifer Torres

Este proyecto es un **registro de criaturas fantásticas** usando **MongoDB**, ideal para aprender operaciones CRUD y análisis de bases de datos NoSQL. La base de datos permite almacenar información diversa de cada criatura, como habilidades, hábitat y nivel de peligro.

>  Este proyecto sirve como práctica profesional de MongoDB, combinando scripts, consultas y análisis.

---

##  Estructura del Proyecto

- `misiones_mongodb.js` → Script con todas las operaciones CRUD.
- `ANALISIS_NOSQL.md` → Reflexión sobre NoSQL vs SQL y casos de estudio.
- `README.md` → Instrucciones y documentación.
- `capturas/` → Carpeta con screenshots de Compass, mongosh y resultados.

![Vista de MongoDB Compass](./capturas/image.jpg)

---

## Scripts y Comandos

| Comando / Acción | Descripción |
|-----------------|------------|
| `mongosh`       | Abre la terminal de MongoDB para ejecutar comandos interactivos. |
| `load('misiones_mongodb.js')` | Ejecuta automáticamente todos los comandos del script. |
| `db.criaturas.find()` | Muestra todas las criaturas en la colección. |
| `db.criaturas.updateOne()` | Actualiza un documento específico (ej: agregar habilidades). |
| `db.criaturas.updateMany()` | Actualiza múltiples documentos según un criterio (ej: incrementar nivel de peligro). |

---

##  Tecnologías utilizadas

| Herramienta | Propósito |
|-------------|-----------|
| MongoDB     | Base de datos NoSQL orientada a documentos. |
| MongoDB Compass | Interfaz gráfica para visualizar y manipular datos. |
| mongosh     | Consola interactiva de MongoDB para ejecutar scripts y consultas. |
| VS Code (opcional) | Para editar scripts con la extensión MongoDB. |

---

##  Configuración rápida

### 1. Clonar el repositorio
```bash
git clone https://github.com/Jntorres2001/mision-mongodb-jennifer.git
cd mision-mongodb-jennifer
```
## Capturas de pantalla
![Vista de MongoDB Compass](./capturas/Screenshot_2.jpg)

---
![Vista de MongoDB Compass](./capturas/image1.png)

---
## Análisis NoSQL
- NoSQL vs SQL: MongoDB permite flexibilidad de esquema, ideal para criaturas con atributos variados, a diferencia de un modelo relacional rígido.

- Tipos de NoSQL: Clave-Valor, Columnar, Grafo; útiles en escenarios específicos como mensajería rápida o redes sociales.

- Casos de estudio: Netflix y Amazon usan MongoDB para catálogos con datos heterogéneos y consultas rápidas.

