## Ejercicio 4

### Errores encontrados

![](/img/ex4.jpeg)

### Solución

Agregar llaves a la función dameCita

```cs
public String dameCita()  {

 String [] citas = {
 "No hay mal que por bien no venga",
 "FRASE DE PRUEBA 2",
 "No por mucho madrugar amanece mas temprano"};
 Random random = new Random();
 int numCita = random.Next(0,3);
 return (citas[numCita]);
 }
```
