# VC_P1

# Tarea 1
Crea una imagen, p.e. de 800x800 píxeles, con la textura del tablero de ajedrez

Se divide el tablero en una matriz de 8X8 si la suma de los indices es par la casilla se pinta de negro, esto se hace ajustando las dimensiones que hay que pintar conocidos los indices. (El codigo es un poco ineficiente ahora que lo estoy viendo otra vez no hace falta pintar todas las casillas solo las blancas)

![image](https://github.com/user-attachments/assets/154c69da-d4ef-4deb-b301-d4fac5e26da8)

# Tarea 2
Crear una imagen estilo Mondrian (un ejemplo https://www3.gobiernodecanarias.org/medusa/ecoescuela/sa/2017/04/17/descubriendo-a-mondrian/ )

Similar a la tarea 1 pero los rangos en los que se pinta son arbitrarios y desiguales, se deben definir en el código.

![image](https://github.com/user-attachments/assets/9d705382-23c6-41f4-a035-23659f03f754)


# Tarea 3
Resuelve una de las tareas previas (a elegir) con las funciones de dibujo de OpenCV  :)

Exactamente igual que la tarea 1 pero utilizando las funciones de openCV para pintar el tablero 

![image](https://github.com/user-attachments/assets/8f05feb6-1531-4764-82dd-1db5590ce359)


# Tarea 4
Modifica de forma libre los valores de un plano de la imagen

Modificamos los valores de un plano y lo insertamos en el frame

![image](https://github.com/user-attachments/assets/aea8f440-14b0-4a0c-98ff-b295d44d7343)


# Tarea 5
Pintar círculos en las posiciones del píxel más claro y oscuro de la imagen 
¿Si quisieras hacerlo sobre la zona 8x8 más clara/oscura?

Con un par de bucles que recorran el frame detectamos cuales son las zonas con los pixeles mas claros y mas oscuros, ahí pintamos los puntos.

![image](https://github.com/user-attachments/assets/b66a8ff7-71f3-41ed-b016-ab6f805a346f)


# Tarea 6
Llevar a cabo una propuesta propia de pop art.

Nuevo pop-art añadiendo mas planos, jugando con el orden de los canales y en algunos casos modificando su valor.

![image](https://github.com/user-attachments/assets/bd7b47bf-8d41-4f08-86ea-906d13e0d63b)

