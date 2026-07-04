# FarmaCode

Sistema de escritorio para apoyar la operación de una farmacia: inventario, ventas, compras, proveedores, usuarios, devoluciones y generación de documentos. El proyecto está desarrollado en Java con una interfaz gráfica Swing y persistencia en una base de datos SQL.

## Funcionalidades

- Inicio de sesión, recuperación de acceso y administración de usuarios.
- Registro, consulta y modificación de productos y proveedores.
- Control de inventario y alertas operativas.
- Registro de ventas, compras, devoluciones y requisiciones.
- Generación de facturas y reportes en PDF.
- Métricas y gráficas de ventas.
- Envío de correo desde los flujos que lo requieren.

## Tecnologías

- Java y Java Swing.
- Formularios del GUI Builder de NetBeans.
- SQL y JDBC.
- iText para documentos PDF.
- JFreeChart para visualización de métricas.
- JavaMail para correo electrónico.

## Instalación

### Requisitos

- JDK compatible con el proyecto.
- Apache NetBeans recomendado para editar los archivos `.form`.
- Motor de base de datos SQL configurado para el entorno local.

### Ejecución

1. Clona el repositorio:

   ```bash
   git clone https://github.com/JesusACastillo/FarmaCode.git
   cd FarmaCode
   ```

2. Abre el proyecto en NetBeans.
3. Añade al classpath las dependencias necesarias desde `lib/`.
4. Configura localmente la conexión a la base de datos sin publicar credenciales.
5. Ejecuta la clase principal `farmacia/Farmacia.java`.

> El repositorio conserva la estructura original del proyecto. Para un entorno reproducible se recomienda migrar las dependencias a Maven o Gradle.

## Capturas

Las capturas de la aplicación todavía no están publicadas. Como siguiente paso se recomienda añadir imágenes de los módulos de inicio de sesión, inventario, ventas y reportes en `docs/screenshots/`.

## Estructura

```text
FarmaCode/
├── Entidades/     # Modelos y acceso a datos
├── Interfaces/    # Ventanas y formularios Swing
├── farmacia/      # Punto de entrada de la aplicación
├── icons/         # Recursos gráficos
├── lib/           # Dependencias del proyecto original
└── metodos/       # Utilidades, reportes y componentes
```

## Mejoras futuras

- Incorporar Maven o Gradle y documentar versiones de dependencias.
- Separar credenciales y configuración mediante variables de entorno.
- Añadir migraciones y datos de demostración para la base de datos.
- Crear pruebas automatizadas para reglas de negocio y acceso a datos.
- Publicar capturas y un video corto del flujo principal.

## Autor

**Jesús Castillo** — [GitHub](https://github.com/JesusACastillo)
