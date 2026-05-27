# Bandit Nivel 4 → 5

## Objetivo
Encontrar la contraseña en el único archivo legible por humanos en el directorio inhere del home.
## Qué aprendí
- Conocer el contenido de un archivo y su formato
- Comandos: file
## Comandos usados
ssh bandit4@bandit.labs.overthewire.org -p 2220
ls
cd inhere
ls -la
file ./-file0*
cat ./file07

## Contraseña obtenida
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
