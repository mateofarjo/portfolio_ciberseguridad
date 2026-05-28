# Bandit Nivel 9 → 10

## Objetivo
Encontrar la contraseña que se encuentra almacenada en el archivo `data.txt`, oculta dentro de las pocas cadenas de texto legibles por humanos y precedida por varios caracteres `=`.
## Qué aprendí
- Extraer cadenas de texto legibles por humanos desde un archivo binario (`strings`).
- Filtrar resultados usando caracteres especiales como patrón de búsqueda.
- Comandos: `strings`,`grep`.
## Comandos usados
ssh bandit9@bandit.labs.overthewire.org -p 2220
ls
strings data.txt | grep "==="
## Contraseña obtenida
FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
