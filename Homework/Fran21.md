```python
celcius=25.4
kelvin=celcius+273.15
print(str(celcius)+"+°C+ 273.15 = "+ str(kelvin)+"k")
```

    25.4+°C+ 273.15 = 298.54999999999995k
    


```python
import math
h1=1.5
h2=2.2
h3=1.56
h4=1.78
h5=1.82
h6=1.90
h7=1.66
h8=1.91
h9=1.76
h10=1.88
cantidad=10
suma=(h1+h2+h3+h4+h5+h6+h7+h8+h9+h10)/cantidad
print("La media de 10 datos es : "+ str(suma)+"m")
sumacuadro= ((h1-suma)**2+ (h2-suma)**2 + (h3-suma)**2 + (h4-suma)**2 + (h5-suma)**2 + (h6-suma)**2 + (h7-suma)**2+ (h8-suma)**2+ (h9-suma)**2+ (h10-suma)**2)
deviacion= math.sqrt(sumacuadro/cantidad)
print("La suma de los valores menos la media al cuadrado es :"+ str(sumacuadro))
print("La desviacion estandard es :"+ str(deviacion))
```

    La media de 10 datos es : 1.797m
    La suma de los valores menos la media al cuadrado es :0.35800999999999994
    La desviacion estandard es :0.18921152184790438
    


```python

```
