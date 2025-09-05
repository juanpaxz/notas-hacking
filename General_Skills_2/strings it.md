#### Description

Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/fae9ac5267cd6e44124e559b901df177/strings) without running it?
### Solucion

Extrae todos los strings del archivo.
strings archivo | grep pico

```
picoCTF{5tRIng5_1T_7f766a23}
```

### Notas Adicionales

La tarea es encontrar la flag sin ejecutar el archivo. La pista proporcionada es: **"strings it"**, sugiriendo el uso del comando `strings` para extraer cadenas legibles del archivo.
### Referencias

https://youtu.be/VJrXHpHglak
