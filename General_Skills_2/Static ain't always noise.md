#### Description

Can you look at the data in this binary: [static](https://mercury.picoctf.net/static/66932732825076cad4ba43e463dae82f/static)? This [BASH script](https://mercury.picoctf.net/static/66932732825076cad4ba43e463dae82f/ltdis.sh) might help!

### Solucion
examinar con strings 
strings static | grep pico

buscar 
strings static | grep -i "pico"

```
picoCTF{d15a5m_t34s3r_f5aeda17}
```
### Notas Adicionales
están pidiendo es **mirar los datos dentro de un binario**, sin ejecutarlo.
se refieren a que uses herramientas de consola como `strings`, `grep`, `less`, etc., para leer el binario.
### Referencias

https://www.google.com/search?client=opera&q=Static+ain%E2%80%99t+always+noise+picoctf&sourceid=opera&ie=UTF-8&oe=UTF-8