# coding=utf-8

print ('Hola negros')
print()
print('ya se \'programar\' en python')
print(3.141592)
print('IZQ' + ' DER')

frase = 'changua '
otra_frase = ' y el mondongo'
print(frase + otra_frase)
print(frase + '\n' + otra_frase)
print()
print(frase)
print(type(frase))

frase= 2.15
print(frase) 
print(type(frase))
print(type(str(frase)))

#operaciones aritmeticos
# + - * /
# + - sumas y restas
# * / multiplicacion y division
# ** potencia
# // division entera

print(3+12)
print(5-23)
print(8*3)
print(5**3)
print(14/3)
print(14//3) 
print(25**(1/2)) # raiz cuadrada

#programa que me salude
nombre = input('Cual es tu nombres? ')
print('Hola ' + nombre)

#programa que pregunte la hora y diga cuantos minutos representan
horas = input('dame una cantidad de horas ')
minutos = 60 * float(horas)
print('la cantidad de minutos es ', minutos)
