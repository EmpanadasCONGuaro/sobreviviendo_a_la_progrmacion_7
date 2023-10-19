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

# 2. De los retos anteriores selecione 3 funciones y escribalas con argumentos no definidos (*args).


 - RETO 6 PUNTO 4 - SIN ARGUMENTOS DEFINIDOS


```pseudocode
def Vueltas(*args) -> float:
  ValorDeVueltas=((B)-((P*300)+(M*3300)+(H*350))) 
  return ValorDeVueltas

if __name__ == "__main__":
 B: float = float(input("ingrese el valor del billete:"))
 P: float = float(input("ingrese el numero de panes:"))
 M: float = float(input("ingrese el numero de bolsas de leche:"))
 H= float = float(input("ingrese el numero de huevos:"))
 ValorDeVueltas=Vueltas(P,M,H,B)

ValorDeVueltas2= (ValorDeVueltas*(-1))

if ValorDeVueltas == 0:
 print("sus vueltas son 0, por lo tanto estamos a paz y salvo")
elif ValorDeVueltas < 0:
 print("quedas debiendo "+str(ValorDeVueltas2))
elif ValorDeVueltas > 0:
 print("sus vueltas son " +str(ValorDeVueltas))

```


 - RETO 6 PUNTO 5 - SIN ARGUMENTOS DEFINIDOS


```pseudocode
def CalcularPrestamos(*args) -> float:
  valortotaldelprestamo= (c*((1+i/100)**n))
  return valortotaldelprestamo

if __name__ == "__main__":
 c: float = float(input("Ingrese el valor del prestamo:"))
 i: float = float(input("Ingrese la tasa de intereses:"))
 n: float = float(input("Ingrese el tiempo es meses:"))
 valortotaldelprestamos= CalcularPrestamos(c,i,n)
 print("el valor final del prestamos es "+str(valortotaldelprestamos))
```


 - RETO 6 PUNTO 6 - SIN ARGUMENTOS DEFINIDOS


```pseudocode
def CalcularContagios(*args) -> float:
  NumeroDeContagios=(C*(2**D))
  return NumeroDeContagios

if __name__ == "__main__":
 C: float = float(input("Ingrese el número de contagios actuales:"))
 D: float = float(input("Ingrese el número de dias:"))
 NumeroDeContagios = CalcularContagios(C,D)
 print("el número de contadios después de "  + str(D) +  " dia(s) es de " + str(NumeroDeContagios))
```


# 3. Escriba una función recursiva para calcular la operación de la potencia.


```pseudocode
def potencia(x,a)->float:
    if a == 0:
       return 1
    else:
       return x * potencia(x,a-1)

if __name__ == "__main__":
   x:float=float(input("ingrese un numero como base:"))
   a:float=float(input("ingrese un numero como exponente:"))
   
   lapotenciacion =potencia(x,a)
   print(f"{x} elevado al exponente {a} es {lapotenciacion}") 
```



# 4. Utilice la siguiente plantilla de code para contar el tiempo:

 - PLANTILLA:


```pseudocode
import time

start_time = time.time()
# instrucciones sobre las cuales se quiere medir tiempo de ejecución
end_time = time.time()

timer = end_time - start_time
print(timer)
```



```pseudocode
import time

def fibonaccitomasRECURSIVOQUENUNCA(x):
    if x <= 0:
        return 0
    elif x ==1:
        return 1
    else:
        return fibonaccitomasRECURSIVOQUENUNCA(x-1) + fibonaccitomasRECURSIVOQUENUNCA(x-2)
    
if __name__ == "__main__":
    x:int=int(input("ingrese el numero x:"))

    start_time = time.time()
    resultado = fibonaccitomasRECURSIVOQUENUNCA(x)
    end_time = time.time()
    timer = end_time - start_time

    print(f"la sucesion de fibonacci {x} por recursion es {resultado}")
    print(f"el timepo es {timer}") 
```


# 5. Crear cuenta en stackoverflow y adjuntar imagen en el repo



   ![image](https://github.com/EmpanadasCONGuaro/sobreviviendo_a_la_progrmacion_7/assets/142174506/fadc3d8f-013f-48da-8139-fdc773fc5a56)



# 6. Cosas de adultos....ir a linkedin y crear perfil....NO IMPORTA que estén iniciando, si tienen tiempo para redes poco útiles como fb, insta, o tiktok tienen tiempo para crear un perfil mamalón. Dejar enlace en el repo.



LINK: https://www.linkedin.com/in/david-felipe-valencia-yague-615409297/
