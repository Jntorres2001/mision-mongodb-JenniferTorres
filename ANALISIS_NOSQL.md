# Análisis NoSQL: El Manuscrito del Cronista

## 1. NoSQL vs. SQL

MongoDB, como base de datos orientada a documentos, es más adecuada para el “Bestiario Digital” porque permite almacenar información con estructuras variables.  
En un modelo relacional (SQL), tendríamos que definir columnas fijas para todos los tipos de criaturas, lo cual generaría muchos campos vacíos o tablas relacionadas complicadas.  
En cambio, MongoDB permite que cada documento tenga diferentes atributos (por ejemplo, una criatura puede tener “cabezas”, otra “estadísticas”, otra “hechizos”).  
Esta flexibilidad facilita el modelado de datos semi-estructurados y la evolución del esquema sin necesidad de migraciones.

## 2. Otro tipo de NoSQL

Un ejemplo de otro tipo de base de datos NoSQL son las **bases de datos de tipo Clave-Valor**, como Redis.  
Estas almacenan datos como pares únicos de clave y valor, similares a un diccionario.  
Son ideales para escenarios donde se necesita acceder rápidamente a información mediante una clave, como cachés en tiempo real, sesiones de usuario o contadores de visitas.

**Ejemplo de uso:**  
Redis se usa en sistemas de comercio electrónico para guardar temporalmente el carrito de compras de los usuarios debido a su alta velocidad.

## 3. Caso de estudio: MongoDB en el mundo real

**Aplicación:** Plataformas como Spotify y eBay han utilizado MongoDB.  
En plataformas como Spotify, MongoDB se utiliza para almacenar datos de usuarios, listas de reproducción y metadatos musicales.  
El modelo flexible de documentos permite representar información diversa —desde artistas hasta álbumes y canciones— sin una estructura rígida, lo que mejora la velocidad de desarrollo y la escalabilidad.
