## Ejercicio 4
### Errores encontrados

![](/img/ex3.jpeg)

### Solución
Agregar Return en la línea 17

```cs
Public Function FahrenheitToCelsius(ByVal Fahrenheit As Double) _
        As Double
        Return ((Fahrenheit - 32) * 5) / 9
    End Function
```