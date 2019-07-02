# DH
#include "pch.h"
#include <iostream>
#include <math.h>
using namespace std;

int main()
{
	setlocale(LC_ALL, "RUS");
	int g, p, a, b;
	long long int A, B, K1, K2;
	cout << "Введите g" << endl;
	cin >> g;
	cout << "Введите p" << endl;
	cin >> p;
	cout << "Введите a" << endl;
	cin >> a;
	cout << "Введите b" << endl;
	cin >> b;
	A = pow(g, a);
	A = A % p;
	B = pow(g, b);
	B = B % p;
	K1 = pow(B, a);
	K1 = K1 % p;
		cout << "Ключ - " << K1;
	
}

