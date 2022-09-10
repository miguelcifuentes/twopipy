# twopipy
secundo intento 
import numpy as np 
# funcion de comparacion
def comparar(z1):
  z=z1
  if 0 in z:
    return None 
  if 0 not in [ sum(z) for z in itertools.permutations(z, 2) ]:
      
      c=[x for x in z if (x>-33 and x<33)]

      if len(c)==6:
        return c
    
      else:
        return None
