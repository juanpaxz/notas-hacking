#### Description

Can you make sense of this file?Download the file [here](https://artifacts.picoctf.net/c/473/enc_flag).
### Solucion

por si hay varias carpetas una dentro de otra
cat enc_flag | base64 --decode | base64 --decode

```
picoCTF{base64_n3st3d_dic0d!n8_d0wnl04d3d_dfe803c6}
```
### Notas Adicionales

Es fundamental comprender cómo funciona la codificación y decodificación en base64.
### Referencias

https://www.youtube.com/watch?v=PI2-KwgAhXk&t=1s
