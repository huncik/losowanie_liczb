#include <iostream>
#include <cstdlib>
#include <ctime>
#include <fstream>
using namespace std;

int main() {
    srand( time(NULL) );

    cerr << "wylosowana liczba to:\n";
    for (int i = 0; i < 1; ++i)
        cerr << (rand() % 100) + 1 << '\n';
}
