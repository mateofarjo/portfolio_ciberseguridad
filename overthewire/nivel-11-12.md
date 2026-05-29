# Bandit Nivel 11 → 12

## Objetivo
Encontrar la contraseña que se encuentra almacenada en el archivo `data.txt`, donde todas las letras minúsculas (a-z) y mayúsculas (A-Z) han sido rotadas 13 posiciones (Cifrado ROT13).
## Qué aprendí
- Desplazar caracteres utilizando el comando de traducción de texto `tr`.
- Comprender el funcionamiento del cifrado simétrico clásico ROT13.
- Comandos: `tr`
## Comandos usados
ssh bandit10@bandit.labs.overthewire.org -p 2220
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
## Contraseña obtenida
7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
