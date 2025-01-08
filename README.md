<h1>Querys</h1><hr>
<h2>Consultas realizadas con el motor de base de datos relacional</h2>
<h3>Que son las bases de datos relacionales</h3>
<p>Las bases de datos relacionales son un tipo de base de datos que organiza los datos en tablas, que están compuestas por filas y columnas. Cada fila en una tabla representa un registro único, y cada columna representa un atributo de los datos. Las tablas están relacionadas entre sí mediante claves (keys), que permiten establecer conexiones lógicas entre los datos de diferentes tablas.
para que siven las bases de datos relacionales
Las bases de datos relacionales sirven para organizar y gestionar datos de manera eficiente y estructurada. Aquí te dejo algunas de sus aplicaciones más comunes:

Gestión de Información: Se utilizan en sistemas de gestión de información, como los sistemas de gestión de relaciones con clientes (CRM), sistemas de gestión de inventarios, y sistemas de recursos humanos.

Transacciones Financieras: Son esenciales en el sector financiero para gestionar transacciones bancarias, cuentas de clientes, operaciones de bolsa, entre otros.

Sistemas de Reservas: Se utilizan en sistemas de reservas de vuelos, hoteles, alquiler de coches, donde es crucial gestionar y relacionar grandes volúmenes de datos de clientes y reservas.

Aplicaciones Web y Móviles: La mayoría de las aplicaciones web y móviles utilizan bases de datos relacionales para almacenar y recuperar datos de usuarios, contenidos, transacciones, etc.

Investigación y Análisis: Ayudan en la recopilación y análisis de grandes volúmenes de datos para investigaciones científicas, análisis de mercado, y estudios de comportamiento.

Comercio Electrónico: En tiendas en línea para gestionar productos, inventarios, pedidos de clientes, y datos de envío.
</p>
<h3>Para que sirve el lenguaje de programación de consultas PL-SQL</h3>
<p>T-SQL (Transact-SQL), PL/SQL (Procedural Language/Structured Query Language) y PL/pgSQL (Procedural Language/PostgreSQL Structured Query Language) son lenguajes de programación que permiten la creación de bloques de código y procedimientos almacenados en bases de datos Oracle y PostgreSQL, respectivamente. Ambos lenguajes ofrecen extensiones a SQL estándar, permitiendo realizar operaciones más complejas y automatizadas.</p>
<p> para que sirve T-SQL
T-SQL (Transact-SQL) es una extensión de SQL desarrollada por Microsoft y Sybase, que se utiliza principalmente en sistemas de gestión de bases de datos como Microsoft SQL Server. Aquí te explico algunas de sus funcionalidades clave:

Consultas Avanzadas: Permite realizar consultas SQL complejas para extraer y manipular datos de bases de datos relacionales.

Procedimientos Almacenados: Se pueden crear procedimientos almacenados, que son bloques de código que se pueden ejecutar repetidamente sin tener que reescribir la consulta cada vez. Esto mejora la eficiencia y la seguridad.

Triggers: Los triggers son procedimientos que se ejecutan automáticamente en respuesta a ciertos eventos en la base de datos, como inserciones, actualizaciones o eliminaciones de datos.

Control de Flujo: T-SQL permite utilizar estructuras de control de flujo como bucles, condicionales (IF...ELSE) y bloques TRY...CATCH para manejar errores, lo cual proporciona mayor flexibilidad y control sobre las operaciones de bases de datos.

Manejo de Transacciones: Facilita la gestión de transacciones, lo cual es crucial para asegurar la integridad de los datos y la consistencia en operaciones de bases de datos, especialmente en entornos de alta concurrencia.

Funciones Escalares y de Tabla: Se pueden definir funciones que devuelvan valores individuales (escalars) o conjuntos de resultados (de tabla), lo que permite reutilizar lógica compleja en varias consultas.

Integración con Aplicaciones: T-SQL se utiliza ampliamente para integrar bases de datos con aplicaciones web y de escritorio, permitiendo operaciones eficientes y seguras. </p>
<p>
  PL/SQL:

Procedimientos y Funciones: Permite definir procedimientos y funciones que pueden ser llamados desde aplicaciones o directamente desde SQL.

Variables y Control de Flujo: Se pueden declarar variables, utilizar estructuras de control como bucles y condicionales.

Triggers: Se pueden crear disparadores que ejecutan código automáticamente en respuesta a ciertos eventos en la base de datos.

Manejo de Errores: Ofrece mecanismos avanzados para la captura y manejo de errores.

Reutilización de Código: Facilita la modularización y reutilización del código.

PL/pgSQL:

Procedimientos y Funciones: Similar a PL/SQL, permite definir y ejecutar procedimientos y funciones dentro de PostgreSQL.

Variables y Control de Flujo: Ofrece una sintaxis rica para trabajar con variables, bucles, y condicionales.

Triggers: Permite crear triggers que se ejecutan en respuesta a cambios en la base de datos.

Manejo de Errores: Incluye capacidades robustas para la captura y manejo de excepciones.

Integración con SQL: Facilita la integración de operaciones SQL dentro de bloques procedurales.
</p>

<p>Si necesitas probar los scripts te muestro a continuación como se hace</p>
<h3>Instalar postgresql en Sistema Operativo Windows</h3>
<p>
  Paso 1: Descargar e instalar PostgreSQL
Visita el sitio web oficial de PostgreSQL y descarga el instalador para Windows. Asegúrate de elegir la versión correcta según tu arquitectura (32 o 64 bits)2.

Ejecuta el instalador y sigue las instrucciones del asistente. Selecciona el directorio de instalación y los componentes que deseas instalar3.

Configura la contraseña del superusuario (por defecto, el nombre es "postgres"). Recuerda esta contraseña para futuras conexiones4.

Configura el puerto TCP (puedes dejar el puerto predeterminado, que es 5432).

Finaliza la instalación y espera a que el proceso termine.

Paso 2: Instalar pgAdmin 4 v8
Visita el sitio web oficial de pgAdmin y descarga el instalador para Windows.

Ejecuta el instalador y sigue las instrucciones del asistente. Selecciona el directorio de instalación y los componentes que deseas instalar4.

Abre pgAdmin 4 desde el menú de inicio.

Introduce la contraseña del superusuario que configuraste durante la instalación de PostgreSQL.

Conéctate al servidor PostgreSQL y comienza a gestionar tus bases de datos.

Paso 3: Configurar y probar la instalación
Abre pgAdmin 4 y asegúrate de que puedas conectarte al servidor PostgreSQL.

Crea una nueva base de datos y prueba algunas operaciones básicas para verificar que todo esté funcionando correctamente.
</p>
<h3>Importar base de datos</h3>
<p>
  Importar Datos
Crea una nueva base de datos o selecciona una existente donde deseas importar los datos.

Haz clic derecho sobre la base de datos seleccionada.

Selecciona "Restore" (Restaurar).

Navega hasta el archivo de base de datos.

Haz clic en "Restore" para iniciar el proceso.
</p>
<p>Ejecuta los scripts!</p>
