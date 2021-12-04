# arrayto6


//arrayto6
#include <iostream>
#include <algorithm>
using namespace std;


int main() {

	int arr[1000];

	for (int i = 0; i < 1000; i++) {
		arr[i] = rand() % 100;
		cout << arr[i] << endl;
		if (arr[i] == 6) {
			cout << arr[i] << endl;
			i++;
		}
		else {
			continue;
		}
		cout << "Amount of 6's: " << i;
	}

	return 0;
}
    
//Largest number					      
 #include <iostream>
#include <algorithm>
#include <array>
using namespace std;


int main() {
	int numb = 0;
	array<int, 10> user = {};


	cout << "Type any numbers" << endl;

	for (int i = 0; i < 10; i++) {
		cin >> user[i];
		if (numb < user[i]) {
			numb = user[i];
		}
	}
	cout << "The largest number is " << numb << endl;

	return 0;
                                  
                                  
