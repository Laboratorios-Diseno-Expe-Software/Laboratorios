## Ejercicio 2
### Errores encontrados

![](/img/ex2.jpeg)

### Solución
Agregar Case en la línea 20

```cs
Select Case UCase(Trim(strmoneda))
         Case "DO"
             'dolar
            Return "30"
         Case "RE"
                'real
                Return "9.9"
         Case "EU"
            'Euro
            Return "33"
        End Select
```