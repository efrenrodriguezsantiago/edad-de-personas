/*Se necesita realizar un programa que calcule la edad en años de una persona,
 para saber si es mayor de edad o no,
  dado como parámetro de entrada el año de nacimiento.
   El programa imprimirá un mensaje que indique si es mayor de edad o no
*/

#include <iostream>

using namespace std;
 
 int main(){
 	int anio_actual =0, anio_de_nacimiento = 0,edad = 0;  //son las variables que se debe de introducir
 	
 	cout<<"escribe el anio actual :";cin>>anio_actual;  //el usuario digita el anio actual e imprime el anio
 	cout<<"escribe el anio de nacimiento :";cin>>anio_de_nacimiento;  //el usuario digita su fecha de nacimiento e imprime en pantalla su nacimiento
 	
 	edad = anio_actual - anio_de_nacimiento;  //la funcion de edad esque hace la operacio para sacar la edad del usuario
 	cout<<"\nla edad es:"<<edad<<endl;  //imprime enpantalla la edad del usuario
 	
 	if(edad < 18)  //se utiliza la sentencia dado caso que si es menos de 18 anios
 	{
 		cout<<"es menor de edad"<<endl;  //la persona es menor de edad
	 }
 	else  //si no es menor de edad
 	{
 		cout<<"es mayor de edad"<<endl;  //el programa imprimira en pantalla que la persona es mayor de edad
	 }

    cin.get();

    return 0;  //termina el programa resuelto
 }
