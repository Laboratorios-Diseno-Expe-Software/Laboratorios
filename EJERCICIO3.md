## Ejercicio 3
### Errores encontrados

![](/img/ex3.jpeg)

### Solución
Durante la revisión minuciosa del código, hemos identificado un aspecto crucial en la función 'FahrenheitToCelsius(ByVal Fahrenheit As Double)',
que también está ubicada en la línea 17 del archivo. Es evidente que dicha función no cuenta con la instrucción 'return', la cual es esencial para
que la función pueda ejecutarse de manera efectiva y devolver los resultados esperados.

```cs
Public Function FahrenheitToCelsius(ByVal Fahrenheit As Double) _
        As Double
        Return ((Fahrenheit - 32) * 5) / 9
    End Function
```
