# Integrantes:
Gonzalez Ana.
Gonzalez Iara.
Kevarkian Candela.
# Proyecto: Contador de números.
![ae2551b8-6c82-4473-a847-13d130324a13](https://github.com/iaragonzalezzz/Parcial-SPD./assets/123982656/6714bd4b-de2e-4e86-8019-8ddfe944ac6f)
# Descripción:
Se utiliza un contador de 0 a 99 usando dos displays de 7 segmentos y tres botones para
controlar la cuenta. El contador va a comenzar en 0, aumentando o disminuyendo
su valor en una unidad con los botones.
# Función principal:
Esta función se encarga de (dependiendo el display presionado) mostrar el valor correspondiente. 

void display_numeros(int numero)
{
  
	digitalWrite(A, HIGH);
    digitalWrite(B, HIGH);
    digitalWrite(C, HIGH);
    digitalWrite(D, HIGH);
    digitalWrite(E, HIGH);
    digitalWrite(F, HIGH);
    digitalWrite(G, HIGH);
  
    switch(numero){
      case 0:
        digitalWrite(A, LOW);
        digitalWrite(B, LOW);
        digitalWrite(C, LOW);
        digitalWrite(D, LOW);
        digitalWrite(E, LOW);
        digitalWrite(F, LOW);
        break;
      case 1:
        digitalWrite(B, LOW);
        digitalWrite(C, LOW);
        break;
      case 2:
        digitalWrite(A, LOW);
        digitalWrite(B, LOW);
        digitalWrite(E, LOW);
        digitalWrite(D, LOW);
        digitalWrite(G, LOW);
        break;
      case 3:
        digitalWrite(A, LOW);
        digitalWrite(B, LOW);
        digitalWrite(C, LOW);
        digitalWrite(D, LOW);
        digitalWrite(G, LOW);
        break;
      case 4:
        digitalWrite(B, LOW);
        digitalWrite(C, LOW);
        digitalWrite(F, LOW);
        digitalWrite(G, LOW);
        break;
      case 5:
        digitalWrite(A, LOW);
        digitalWrite(C, LOW);
        digitalWrite(D, LOW);
        digitalWrite(F, LOW);
        digitalWrite(G, LOW);
        break;
      case 6:
        digitalWrite(A, LOW);
        digitalWrite(C, LOW);
        digitalWrite(D, LOW);
        digitalWrite(E, LOW);
        digitalWrite(F, LOW);
        digitalWrite(G, LOW);
        break;
      case 7:
        digitalWrite(A, LOW);
        digitalWrite(B, LOW);
        digitalWrite(C, LOW);
        break;
      case 8:
        digitalWrite(A, LOW);
        digitalWrite(B, LOW);
        digitalWrite(C, LOW);
        digitalWrite(D, LOW);
        digitalWrite(E, LOW);
        digitalWrite(F, LOW);
      	digitalWrite(G, LOW);
        break;
      case 9:
        digitalWrite(A, LOW);
        digitalWrite(B, LOW);
        digitalWrite(C, LOW);
        digitalWrite(F, LOW);
        digitalWrite(G, LOW);
        break;
    }
}



# 🫡 Link del proyecto:
https://www.tinkercad.com/things/kkYjhEb2GxB
