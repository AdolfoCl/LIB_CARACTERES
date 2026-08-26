# LIB_CARACTERES

An ALGOL library for Unisys MCP that gives COBOL programs character translation
they cannot do on their own.

COBOL on the MCP has no comfortable way to reach a character by its code, or to
map one code to another across the whole of a record. This library does it, and
COBOL calls it like any other library.

## Getting the sources off the MCP machine

`control_batfiles.bat` drives FTP through `control_getfiles`, which is not tracked:
it carries the host, usercode and password of the machine the sources live on.
Copy `control_getfiles.example` (and `symbol_getfiles.example` where present) to the
name without the suffix and fill in your own values.
