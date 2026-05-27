# Bandit Nivel 6 → 7

## Objetivo
Encontrar la contraseña que Se encuentra almacenado en algún lugar del servidor y posee las siguientes propiedades:
Pertenece al usuario bandit7
Pertenece al grupo bandit6
Tiene un tamaño de 33 bytes
## Qué aprendí
- Buscar un archivo por dueño y grupo
- Comandos: find
## Comandos usados
ssh bandit6@bandit.labs.overthewire.org -p 2220
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password
## Contraseña obtenida
morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
