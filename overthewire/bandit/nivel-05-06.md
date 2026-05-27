# Bandit Nivel 5 → 6

## Objetivo
Encontrar la contraseña que se almacena en un archivo ubicado en algún lugar del directorio inhere y posee las siguientes propiedades:
Legible para humanos
Tamaño: 1033 bytes
No ejecutable
## Qué aprendí
- Buscar un archivo por tipo y tamaño
- Comandos: find
## Comandos usados
ssh bandit5@bandit.labs.overthewire.org -p 2220
ls
cd inhere
ls -l
find ./ -type f -size 1033c
cat ./maybehere07/.file2
## Contraseña obtenida
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
