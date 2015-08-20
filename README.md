# Repositorio-Intro-a-la-Programacion
// SumaJavi.cpp : main project file.

#include "stdafx.h"
#include<iostream>
#include<conio.h>

using namespace std;

void main ()
{
	int A, B, C, D, E, F;
	cout << "Ingrese el primer valor";
	cin >> A;
	cout << "Ingrese el segundo valor";
	cin >>B;
	C= A+B;
	D= A-B;
	E= A*B;
	F= A/B;
	cout << "El resultado de la suma es: "<<C<<endl;
	cout << "El resultado de la resta es: "<<D<<endl;
	cout << "El resultado de la multiplicacion: "<<E<<endl;
	cout << "El resultado de la division: "<<F<<endl;


	cout << "Gracias por usar la mejor calculadora attentamente, Javiera.";
	
	getch();

}
