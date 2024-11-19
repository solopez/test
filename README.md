# test

HOLA MUNDO!

### FORMACIÓN FULL STACK <3

hola!!!
#copio y pego algo para probar...
def NewtonRaphson(a,b,c,d,e):
    contador=0
    g=0
    while contador<10:
        contador+=1
        if ObtenerDerivada(a,b,c,e)!=0:
             e= e-(ObtenerFuncion(a,b,c,d,e)/ObtenerDerivada(a,b,c,e))
             g=e       
    return g

