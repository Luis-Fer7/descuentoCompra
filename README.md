#include <iostream>

using namespace std;

int main() {
    float precio, descuento, total;

    cout << "Ingrese su total de compra" << endl;
    cin >> precio;

    if (precio > 10000) {
        descuento = precio * 0.25;
        total = precio - descuento;

        cout << "su total con el 25% de descuento es :" << total << endl;
    }
    if (precio <= 10000) {
        descuento = precio * 0.10;
        total = precio - descuento;

        cout << "su total con el 10% de descuento es :" << total << endl;
    }

}
