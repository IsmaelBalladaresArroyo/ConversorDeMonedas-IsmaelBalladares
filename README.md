# Challenge: Conversor de Monedas

## Descripción del proyecto

Este proyecto consiste en un conversor de monedas que permite realizar conversiones entre diferentes divisas de manera precisa. Ha sido desarrollado como un desafío técnico y está diseñado para ser fácil de usar e implementar.

## Requisitos

Antes de ejecutar este proyecto, asegúrate de contar con los siguientes requisitos:

- **Java Development Kit (JDK)** versión 8 o superior.
- Un entorno de desarrollo como **IntelliJ IDEA** o **Eclipse**.
- Herramienta de compilación **Maven** (opcional si deseas gestionar dependencias).

## Instrucciones de instalación y uso

Sigue estos pasos para instalar y ejecutar el proyecto:

1. **Clona el repositorio o descomprime el archivo**:
   ```bash
   git clone <URL-del-repositorio>
   ```
   Si tienes el archivo comprimido, descomprímelo en la carpeta de tu elección.

2. **Abre el proyecto en tu entorno de desarrollo**:
   - Importa el proyecto como un proyecto de Maven (si corresponde).
   - Verifica que las dependencias estén correctamente configuradas.

3. **Compila el proyecto**:
   - Si usas un IDE, localiza la opción "Build Project".
   - Desde la línea de comandos, navega al directorio del proyecto y ejecuta:
     ```bash
     mvn clean install
     ```

4. **Ejecuta el proyecto**:
   - Busca el archivo principal en el directorio `src/main/java`.
   - Ejecuta el archivo principal desde tu IDE o mediante el comando:
     ```bash
     java -cp target/<archivo-jar>.jar <clase-principal>
     ```

## Estructura del proyecto

La estructura básica del proyecto es la siguiente:

```
Challenge-ConversordeMonedas-main/
│
├── src/                # Código fuente del proyecto
│   ├── main/           # Archivos principales
│   │   ├── java/       # Código en Java
│   │   └── resources/  # Recursos adicionales
│   └── test/           # Pruebas unitarias
│
├── lib/                # Librerías externas (si corresponde)
├── target/             # Archivos compilados (generados después de compilar)
├── README.md           # Documentación del proyecto
├── pom.xml             # Archivo de configuración de Maven
└── ...                 # Otros archivos y configuraciones
```

¡Listo! Con esto deberías poder instalar y ejecutar el conversor de monedas sin problemas.
