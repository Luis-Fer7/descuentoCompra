#include <iostream>
#include <stdio.h>
using namespace std;
//funcion
float descuento(float cp)
{
    float x;
//evaluacion del descuento cuando sea mayor a 10000
    if (cp > 10000)
    {
        x = cp * 0.25;

        return x;
    }
    //cuando la funcion es menor o igual a 10000
    else
    {
        x = cp * 0.10;

        return x;
    }
}
// todo el proceso de la funcion
int main ()
{
    float total;

    cout<<"Ingrese la cantidad total a pagar: "<<endl;
    cin>>total;
    cout<<"El descuento que se le aplico segun su total es de : "<<descuento(total)<<" Q"<<endl;

    system("pause");
    return 0;
}
