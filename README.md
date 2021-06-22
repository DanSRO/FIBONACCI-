# FIBONACCI-
Código FIBONACCI em C++
#include <iostream>
using namespace std;
int main(){
	int num, ant=1, at=1, pr;
	cout << "\n Digite o numero de termos Fibonacci: ";
	cin >> num;
	for (int i=1; i<=num; i++){
		if (i == 1) cout << "0 ";
	else if (i==2 || i==3) cout << "1 ";
	else{
		pr = ant + at;
		ant = at;
		at = pr;
		cout << " " << pr;
		}
	}
	return 0;
	}
