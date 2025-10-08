## Description
We found this [packet capture](https://jupiter.challenges.picoctf.org/static/b506393b6f9d53b94011df000c534759/capture.pcap). Recover the flag that was pilfered from the network.

### Solucion

```
picoCTF{p1LLf3r3d_data_v1a_st3g0}
```
### Notas Adicionales
para encontrar la bandera primero tuve que analizar el inicio de la cadena que contenia los digitos de la bandera, encontrando que empezaba en ip.addr == 10.0.0.66, despues converti toda la cadena de codigo ASCII a Texto para poder tener la respuesta

### Referencias
https://codebeautify.org/ascii-to-text