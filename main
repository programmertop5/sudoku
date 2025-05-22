#include <iostream>
#include <ctime>

using namespace std;

void printSimpleSudoku() {
    srand(time(0));

    for (int i = 0; i < 9; i++) {
        if (i % 3 == 0 && i != 1)
            cout << "---------------------\n";

        int used[10] = { 0 };

        for (int j = 0; j < 9; j++) {
            if (j % 3 == 0 && j != 1)
                cout << "||";

            int num;
            do {
                num = rand() % 9 + 1;
            } while (used[num]);

            used[num] = 1;
            cout << num << " ";
        }
        cout << endl;
    }
}

int main() {
    int n;
    cout << "Enter ryadok: " << endl;
    cin >> n;
    int c;
    cout << "Enter stovpec: " << endl;
    cin >> c;

    printSimpleSudoku();
    return 0;
}
