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
                                  
                                  
                                  
