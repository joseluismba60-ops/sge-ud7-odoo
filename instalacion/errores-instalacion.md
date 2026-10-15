# Registro de Errores de Instalación

| Error o Mensaje | Causa Raíz | Solución Aplicada | Fuente Consultada |
| :--- | :--- | :--- | :--- |
| `WARN: the attribute version is obsolete` al levantar Docker Compose. | Las versiones modernas de Docker Compose ya no requieren que se especifique la versión de sintaxis en el archivo YAML. | Es una advertencia no bloqueante. Se puede ignorar de forma segura o eliminar la línea `version: '3.1'` del archivo. | Documentación oficial de Docker Compose Release Notes. |