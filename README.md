# POS-NEG-NEUTRO
//Criar um programa que obtenha um valor do usuário, e escreva se é positivo, negativo ou igual a zero

#include <iostream>
#include <string>

using namespace std; 
int main () {
int valor;
  cout << "Digite o número: ";
  cin >> valor;
 if (valor > 0) {
  cout << "O número escolhido é positivo.";
 }
 else if (valor < 0) {
  cout << "O número escolhido é negativo.";
 }
 else if (valor == 0) {
  cout << "O número escolhido é igual a zero."; 
 }
}
