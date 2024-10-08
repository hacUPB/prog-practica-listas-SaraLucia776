### Cifrado Cesar

- Recibe el mensaje principal
- Se establece la cantidad de veces que se va a correr los elementos del mensaje 
- Coloco un rango de 97 a 122
- Usar función lower para solo manejar letras minúsculas
- Crear una cadena vacía donde se van a guardar las letras
- Con un for, vuelvo cada letra en número con ord (tabla ASCII) y le sumo la cantidad establecida
- Si se pasa del rago: resto el resultado de la suma con el numero 122 y lo que me de lo sumo con el 97

#Función ord: le doy la letra y me duelve el codigo en números
#Función chr: le doy el número y me devuelve la letra en mayúcula

## Pseudocódigo

Inicio 

msj = imprimir("Mensaje a cifrar") lower()
num_veces = imprimir("Cantidad de veces que se quiere mover")

cifrar = ""
nueva = ""




