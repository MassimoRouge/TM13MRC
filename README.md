//Nombre:Rodriguez Cordero Maximiliano
// Grupo:itm13
// Fecha:15 03 2024
//

#include <iostream>
#include"Eigen/Dense"

using namespace std;
using namespace Eigen;

int x = 123;
float y = 12.58;
double pi = 3.14159;
char caracter = 'H';
string texto = "va entre comillas!!!";
bool deci =0;

int main(){
    cout << "int x=" << x << endl;
    cout << "float y=" << y << endl;
    cout << "double pi=" << pi << endl;
    cout << "char caracter=" << caracter << endl;
    cout << "texto=" << texto << endl;
    cout << "bool deci=" << deci << endl;
    MatrixXd A(3, 3);
    A << 1, 2, 3, 
         4, 5, 6, 
         7, 8, 9;   
    cout << A;
    cout << endl;
    cout << endl;

    MatrixXd B(3, 3);
    B << 1, 2, 3,
        4, 5, 6,
        7, 8, 9;    
    cout << B;
    cout << endl;
    cout << endl;

    MatrixXd C(3, 3);
    C << 1, 2, 3,
        4, 5, 6,
        7, 8, 9;
    cout << C;
    cout << endl;
    cout << endl;

    /*lodearribaquenojale*/
    cout <<  "hola tu \"juan\" como te va"<< endl;
    cout <<  "hola tu\njuan\n como te va" << endl;
    cout <<  "hola tu\tjuan\t como te va "<< endl;

}
