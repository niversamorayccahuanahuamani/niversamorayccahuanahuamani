
struct player{
	int anillos;   //Es el numero de anillos del gusano.
	int vidas;
	int puntos;
	int x[320], y[320];   /* 120 es la maxima longitud del gusano.
	En estas dos variables se guardan todas las coordenadas
	x e y del gusano */
	int direccion;  // 1 arriba, 2 abajo, 3 izquierda, 4 derecha.
	int repetir;  // Contador que suma puntos y al llegar a un limite:vida extra.
	int gameover;













