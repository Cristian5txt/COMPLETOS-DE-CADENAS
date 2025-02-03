#include <iostream>
#include <string>
#include <algorithm>
using namespace std;

int main()
{
  string frase1,nueva;
  cout << "INGRESE FRASE UNO"<<endl;
  getline (cin,frase1);
  cout<< "su frase es : "<<frase1<<endl;
  //ASIGNACION
   nueva=frase1;
   cout<< "Su Nueva frase es : "<<nueva<<endl;

   //LONGITUD DE FRASES
   int longitud;
   longitud= frase1.length();
   cout<< "LA LONGITUD DE SU FRASE ES: "<<longitud<<endl;
    //CONCATENACION
    int longitud1;
    string NOMBRE= "REYES",FRASE2,FRASE3;
    string DOCS;
    cout << "INGRESE FRASE DOS"<<endl;
    getline (cin,FRASE2);
        cout << "INGRESE FRASE DOS"<<endl;
    getline (cin,FRASE3);
    DOCS= frase1+" "+FRASE2+" "+FRASE3+" "+NOMBRE;
    longitud1= DOCS.length();
    cout <<DOCS<<endl;
    cout<< "LA LONGITUD DE SU FRASE ES: "<<longitud1<<endl;
    //CONVERTIR
    transform(DOCS.begin(), DOCS.end(), DOCS.begin(), ::tolower);
    cout <<DOCS<<endl;
    r
