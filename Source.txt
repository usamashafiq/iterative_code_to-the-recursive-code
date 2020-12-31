#include<iostream>
#include<conio.h>
void ser(int);
using namespace std;
int main() {
	int a;
	cout << "Enter a number to show series : ";
	cin >> a;

	ser(a);
	_getch();
}
void ser(int a) {
	if (a >= 0) {
		if (a == 1) {
			cout << a;
		}
		else
		{
			cout << a;
			ser(a - 1);
		}



	}
	if (a <= 0) {
		if (a == -1) {
			cout << a;
		}
		else {
			cout << a;
			ser(a + 1);
		}



	}





}
