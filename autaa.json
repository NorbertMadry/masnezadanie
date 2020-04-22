#include <iostream>
#include <fstream>
#include <string>

using namespace std;

int main()
{
    string marka;
    string model;
    string id;
    string linia;

    ofstream wyjscie("out.json");
    ifstream wejscie;
    wejscie.open("a.txt");
    wyjscie.open("b.json");
    if(wejscie.good())
            while(!wejscie.eof()&&getline(wejscie, lina))
    {
        getline (wejscie, linia);
        wyjscie << " [  \n { \n \"marka\" : \" " <<marka ;
        getline (wejscie, linia);
        wyjscie << " [  \n { \n \"model\" : \" " <<model;
        getline (wejscie, linia);
        wyjscie << " [  \n { \n \"id\" : \" " <<id;

    }

    wejscie.close();
    wyjscie.close();

    system("PAUSE");
    return 0;
}
