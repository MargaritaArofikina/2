# 2

//Напишите программу, находящую обратный по модулю элемент. Иначе говоря по чисоам X и N нужно найти такое число Y, что остаток от деления //X*Y на N равняется единице


#include <iostream>
using namespace std;
int main() {

	int X, Y, N, a;
	cin >> X >> N;

	for (a = 1; a++) {

		if (X*a%N == 1){

			Y = a;
		}
		return 0;
	}
