# Convercion_de_C++_a_ARM
En este caso es una practica que nos toco elaborar para poder pasar de un codigo de C++ a ensamblador

### Comandos para pasar de "C++ a ARM"

1. Para poder pasar de **C++ a ARM** usaremos el siquiente comando: **g++ -S "Nombre del archivo".cpp "Nombre del archivo".s**. 

Ejemplo: 
```
g++ -S run.cpp run.s
```
2. Para poder enlazar el codigo se usara el suiente comando: **g++ -g -o "Nombre del archivo" "Nombre del archivo".s**. 

Ejemplo:
```
g++ -g -o run run.s
```

Los comando establecidos anteriormente, ya que el primero nos ayuda a convertir en nuesto codigo principal que en este caso es C++ a un lenguaje 
ensamblador que es ARM y por el siguiente nos realiza un enlazamiento del archivo que tiene como extencion ".s" y nos arroga el resultado que esta 
ensamblado que en este caso tomare como ejemplo el de **hola mundo**, que nos arrogara el mensaje de hola mundo en la pantalla.
