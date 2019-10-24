# glava2
#include <iostream>
struct Pizza {
	char name[100];
	double weight;
	int kcal;
};
int main() {
	using namespace std;
	Pizza yourPizza;
	cout << "Enter Name: ";
	cin.getline(yourPizza.name, 100);
	cout << "Enter diametr: ";
	cin >> yourPizza.weight;
	cout << "Enter weight: ";
	cin >> yourPizza.kcal;
	cout << "Pizza: " << yourPizza.name << endl << "Diametr: " << yourPizza.weight << endl << "Weight: " << yourPizza.kcal << endl;
	return 0;
}
