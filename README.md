
# Barajas-post1-u4
## Descripción
Laboratorio 1 de la Unidad 4: Primer programa NASM con segmentos y salida DOS. 
## Prerrequisitos
- DOSBox 0.74+
- NASM 2.14+
- ALINK
## Compilación y ejecución
<div align="justify">
Se debe ejecutar en la consola de Windows los siguientes comandos, ubicandose previamente en la carpeta donde se ha clonado el repositorio: <br><br>


nasm -f obj programa.asm -o programa.obj <br>
alink programa.obj -oEXE -o programa.exe -entry main

Una vez realizado esto, se procede a abrir DOSBox y montar como unidad C a la carpeta en donde fue clonado el repositorio. Posterior a esto, se ejecuta el código usando "programa.exe" dentro del emulador.
</div>

