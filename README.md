# sobreviviendo_a_la_progrmacion_7


# 1. De los retos anteriores selecione 3 funciones y escribalas en forma de lambdas.

 - RETO 6 PUNTO 1 - LAMBDA

```pseudocode
import math
p = math.pi 
                            
if __name__ == "__main__":
 CalcularVolumen= lambda r1, r2, h: ((4/3*p*(r1**3))+(1/3*p*h*(r2**2))) 
 
 r1: float = float(input("ingrese el valor de r1:"))
 r2: float = float(input("ingrese el valor de r2:"))
 h: float = float(input("ingrese el valor de h:"))
 volumen=CalcularVolumen(r1,r2,h)
 print("el volumen es "+str(volumen)+" unidades cubicas")

```


 - RETO 6 PUNTO 2 - LAMBDA

```pseudocode
import math
p = math.pi #defini la variable pi, importante para todos los calculos
                            
if __name__ == "__main__":
 CalcularArea= lambda r,a,b: ((a*b)+(2*(p*(r**2))))  
                                    
 r: float = float(input("ingrese el valor de r:"))        
 a: float = float(input("ingrese el valor de a:"))
 b: float = float(input("ingrese el valor de b:"))
 area=CalcularArea(r,a,b)
 print("el area es "+str(area)+" unidades cuadras")

```


 - RETO 6 PUNTO 3 - LAMBDA


```pseudocode
if __name__ == "__main__":
 CalcularCantidadDeCarne= lambda N,M,K: ((N*6)+(M*7)+(K))
 N: float = float(input("ingrese el numero de gallinas:"))
 M: float = float(input("ingrese el numero gallos:"))
 K: float = float(input("ingrese el numero de pollitos:"))
 CantidadDeCarne=CalcularCantidadDeCarne(N,M,K)
 print("La cantidad de carne es "+str(CantidadDeCarne)+" kilogrmos")
```

   
