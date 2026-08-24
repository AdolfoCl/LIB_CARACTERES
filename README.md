# LIB_CARACTERES
Library Algol (Unisys MCP) para apoyar programas COBOL (Unisys MCP) con la traducción de caracteres

## Getting the sources off the MCP machine

`control_batfiles.bat` drives FTP through `control_getfiles`, which is not tracked:
it carries the host, usercode and password of the machine the sources live on.
Copy `control_getfiles.example` (and `symbol_getfiles.example` where present) to the
name without the suffix and fill in your own values.
