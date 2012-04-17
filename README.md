## Compilación ##

Como parametros de compilación se debe colocar:

+ *-DFUSE_USE_VERSION=27*
+ *-D_FILE_OFFSET_BITS=64*

Como parametros de linkeo se debe colocar:

+ *-lpthread*
+ *-lfuse*


## Ejecución ##

Montar el ejemplo en el directorio tmp:

<code>
./fuse_example ./tmp -f
</code>

Montar el ejemplo en el directorio tmp, con mensaje de bienvenida:

<code>
./fuse_example ./tmp --welcome-msg "Bienvenido al Ejemplo" -f
</code>

## FUSE Parameters ##

+ **-f**: Desactiva la ejecución en modo background
+ **-s**: La biblioteca de FUSE se ejecuta en modo single thread
+ **-d**: Imprime información de debug

