# Bandit Nivel 10 → 11

## Objetivo
Encontrar la contraseña que se encuentra almacenada en el archivo `data.txt`, el cual contiene datos codificados en Base64.
## Qué aprendí
- Decodificar información que ha sido codificada en formato Base64 para recuperar el texto plano original.
- Comandos: `base64 -d `
## Comandos usados
ssh bandit10@bandit.labs.overthewire.org -p 2220
ls
 base64 -d data.txt
## Contraseña obtenida
dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
