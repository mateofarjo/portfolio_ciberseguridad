# Bandit Nivel 8 → 9

## Objetivo
Encontrar la contraseña que se almacena en el archivo data.txt y es la única línea de texto que aparece solo una vez.
## Qué aprendí
- Ordenar el contenido de un archivo de texto de forma alfabética (`sort`).
- Filtrar líneas repetidas en un archivo ordenado para encontrar elementos únicos (`uniq -u`).
- Uso de *pipes* (`|`) para encadenar comandos en una sola línea.
- Comandos: `sort`, `uniq`
## Comandos usados
ssh bandit8@bandit.labs.overthewire.org -p 2220
ls
sort data.txt | uniq -u
## Contraseña obtenida
4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
