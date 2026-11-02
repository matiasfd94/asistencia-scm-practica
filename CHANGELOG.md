# Changelog

Los cambios relevantes del proyecto se documentan en este archivo.


## [2.0.0] - 2026-11-02

### Changed
- La función registrar_asistencia ahora recibe un diccionario con los datos del alumno en lugar de un DNI como texto.
- El registro muestra el DNI y la materia del alumno.
- Cambio incompatible: las llamadas anteriores deben adaptarse al nuevo formato de entrada.


## [1.1.0] - 2026-11-02

### Added
- Contador de asistencias válidas durante la ejecución.
- Visualización del número de cada asistencia y del total de la sesión.

## [1.0.1] - 2026-11-02

### Fixed
- Eliminación de espacios al inicio y al final del DNI mediante strip().

## [1.0.0] - 2026-11-02

### Added
- Primera versión estable.
- Validación del DNI con al menos siete caracteres y únicamente dígitos.
- Retorno de un valor booleano para indicar el resultado del registro.