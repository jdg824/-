#include <iostream>

using namespace std;

int main() {
	int cash;
	int count = 0;

	cin >> cash;
	
	count += cash / 500;
	cash -= 500 * (cash / 500);

	count += cash / 100;
	cash -= 100 * (cash / 100);

	count += cash / 50;
	cash -= 50 * (cash / 50);

	count += cash / 10;
	cash -= 10 * (cash / 10);

	cout << count;
}
