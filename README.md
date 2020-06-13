# Grafico-de-tallo-y-hojas
Comando para la creacion de un grafico de tallo y hojas 
#El ejemplo contempla los datos de un estudio del tipo de sedimentos existente en #perforacionesen mar abierto

# Declaramos scan para la lectura de datos, luego ingresamos los datos respectivamente
scan()->a

1: 10	21	12	12
5: 20	13	24	36
9: 31	18	17	16
13: 37	16	32	13
17: 14	49	25	19
21: 13	32	27	
24:
# La funcion de stem permite crear el diagrama de tallo y hojas
stem(a)

The decimal point is 1 digit(s) to the right of the |

  1 | 022333466789
  2 | 01457
  3 | 12267
  4 | 9

#Permite obtener el doble de tallo y hojas
stem(a,2)
The decimal point is 1 digit(s) to the right of the |

  1 | 0223334
  1 | 66789
  2 | 014
  2 | 57
  3 | 122
  3 | 67
  4 | 
  4 | 9

#Nos muestra la cantidad de datos sobrantes por la imposicion de una anchura de tres elementos 

stem(a,width=3)

The decimal point is 1 digit(s) to the right of the |

  1 | +9
  2 | +2
  3 | +2
  4 |
