#include <iostream>
#include <conio.h>
#include <fstream>
#include <windows.h>
#include <string>
using namespace std;
void pertalite (double harga1){
 int pembagi = 10000;
 int *p;
 p = &pembagi;
 double liter = harga1 / pembagi;
 if (harga1 >= 0){
 cout <<" Keluaran : "<<liter<<" liter"<<endl;
 }else{
 cout <<" Nominal kurang dari 0"<<endl;
 }
}
void pertamax (double harga2){
 int pembagi = 13300;
 int *p;
 p = &pembagi;
 double liter = harga2 / pembagi;
 if (harga2 >= 0){
 cout <<" Keluaran : "<<liter<<" liter"<<endl;
 }else{
 cout <<" Nominal kurang dari 0"<<endl;
 }
}
void pertamaxturbo (double harga3){
 int pembagi = 15900;
 int *p;
 p = &pembagi;
 double liter = harga3 / pembagi;
 if (harga3 >= 0){
 cout <<" Keluaran : "<<liter<<" liter"<<endl;
 }else{
 cout <<" Nominal kurang dari 0"<<endl;
 }
}
void dexlite (double harga4){
 int pembagi = 16350;
 int *p;
 p = &pembagi;
 double liter = harga4 / pembagi;
 if (harga4 >= 0){
 cout <<" Keluaran : "<<liter<<" liter"<<endl;
 }else{
 cout <<" Nominal kurang dari 0"<<endl;
 }
}
void pertaminadex (double harga5){
 int pembagi = 16900;
 int *p;
 p = &pembagi;
 double liter = harga5 / pembagi;
 if (harga5 >= 0){
 cout <<" Keluaran : "<<liter<<" liter"<<endl;
 }else{
 cout <<" Nominal kurang dari 0"<<endl;
 }
}
void pertamaxgreen (double harga6){
 int pembagi = 15000;
 int *p;
 p = &pembagi;
 double liter = harga6 / pembagi;
 if (harga6 >= 0){
 cout <<" Keluaran : "<<liter<<" liter"<<endl;
 }else{
 cout <<" Nominal kurang dari 0"<<endl;
 }
}
void biosolar (double harga7){
 int pembagi = 6800;
 int *p;
 p = &pembagi;
 double liter = harga7 / pembagi;
 if (harga7 >= 0){
 cout <<" Keluaran : "<<liter<<" liter"<<endl;
 }else{
 cout <<" Nominal kurang dari 0"<<endl;
 }
}
string getNama(){
 string nama;
 cout <<"|Nama Pembeli:";
 getline(cin, nama);
 return nama;
}
string getPetugas(){
 string petugas;
 cout <<"|Nama Petugas:";
 getline(cin, petugas);
 return petugas;
}
int main(){
 int pilih;
 float harga1, harga2, harga3, harga4, harga5, harga6,
harga7;
 char ulang;
 do{
 string bahanBakar[] = {"Pertalite", "Pertamax", "Pertamax
Turbo", "Dexlite", "Pertamina Dex", "Pertamax Green 95", "Bio
solar"};
 cout <<"===================================="<<endl;
 cout <<"| PENGISIAN BAHAN BAKAR MINYAK |"<<endl;
 cout <<"===================================="<<endl;
 cout <<" Pilihan Bahan Bakar: "<<endl;

 for (int i = 0; i < sizeof(bahanBakar) /
sizeof(bahanBakar[0]); ++i){
 cout <<i + 1 <<". "<<bahanBakar[i]<<endl;
 }
 cout <<"===================================="<<endl;

 string nama = getNama();
 string petugas = getPetugas();
 cout <<"|Pilih Menu : ";
 cin >>pilih;
 cin.ignore();
 getch();
 system("cls");

 switch (pilih){
 case 1:
 {
 ofstream file("pembayaran.txt");
 if (!file.is_open()){
 cout <<"Pembayaran gagal"<<endl;
 return 1;
 }
 cout <<"===================================="<<endl;
 cout <<"| PERTALITE |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| Harga perliter: |"<<endl;
 cout <<"| Rp 10.000/liter |"<<endl;
 cout <<"===================================="<<endl;
 cout <<" Nama Pembeli : "<<nama<<endl;
 cout <<" Nama Petugas : "<<petugas<<endl;
 cout <<" Masukkan Nominal : Rp ";
 cin >>harga1;
 pertalite (harga1);
 getch();
 system("cls");

 file <<"===================================="<<endl;
 file <<"| PERTALITE |"<<endl;
 file <<"===================================="<<endl;
 file <<"Nama Pembeli : "<<nama<<endl;
 file <<"Nama Petugas : "<<petugas<<endl;
 file <<"Pembelian : Rp "<<harga1<<endl;
 file.close();
 cout <<"===================================="<<endl;
 cout <<"| BUKTI PEMBAYARAN |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| PERTALITE |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| Harga perliter: |"<<endl;
 cout <<"| Rp. 10.000/liter |"<<endl;
 cout <<"===================================="<<endl;
 cout <<" Nama Pembeli : "<<nama<<endl;
 cout <<" Nama Petugas : "<<petugas<<endl;
 cout <<" Pembelian : Rp "<<harga1<<endl;
 pertalite(harga1);
 break;
 }
 system("cls");
 case 2:
 {
 ofstream file("pembayaran.txt");
 if (!file.is_open()){
 cout <<"Pembayaran gagal"<<endl;
 return 1;
 }
 cout <<"===================================="<<endl;
 cout <<"| PERTAMAX |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| Harga perliter: |"<<endl;
 cout <<"| Rp 13.300/liter |"<<endl;
 cout <<"===================================="<<endl;
 cout <<" Nama Pembeli : "<<nama<<endl;
 cout <<" Nama Petugas : "<<petugas<<endl;
 cout <<" Masukkan Nominal : Rp ";
 cin >>harga2;
 pertamax (harga2);
 getch();
 system("cls");
 file <<"===================================="<<endl;
 file <<"| PERTAMAX |"<<endl;
 file <<"===================================="<<endl;
 file <<"Nama Pembeli: "<<nama<<endl;
 file <<"Nama Petugas: "<<petugas<<endl;
 file <<"Pembelian : Rp "<<harga2<<endl;
 file.close();
 cout <<"===================================="<<endl;
 cout <<"| BUKTI PEMBAYARAN |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| PERTAMAX |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| Harga perliter: |"<<endl;
 cout <<"| Rp. 13.300/liter |"<<endl;
 cout <<"===================================="<<endl;
 cout <<" Nama Pembeli : "<<nama<<endl;
 cout <<" Nama Petugas : "<<petugas<<endl;
 cout <<" Pembelian : Rp "<<harga2<<endl;
 pertamax(harga2);
 break;
 }
 system("cls");
 case 3:
 {
 ofstream file("pembayaran.txt");
 if (!file.is_open()){
 cout <<"Pembayaran gagal"<<endl;
 return 1;
 }
 cout <<"===================================="<<endl;
 cout <<"| PERTAMAX TURBO |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| Harga perliter: |"<<endl;
 cout <<"| Rp 15.900/liter |"<<endl;
 cout <<"===================================="<<endl;
 cout <<" Nama Pembeli : "<<nama<<endl;
 cout <<" Nama Petugas : "<<petugas<<endl;
 cout <<" Masukkan Nominal : Rp ";
 cin >>harga3;
 pertamaxturbo (harga3);
 getch();
 system ("cls");
 file <<"===================================="<<endl;
 file <<"| PERTAMAX TURBO |"<<endl;
 file <<"===================================="<<endl;
 file <<"Nama Pembeli: "<<nama<<endl;
 file <<"Nama Petugas: "<<petugas<<endl;
 file <<"Pembelian: Rp "<<harga3<<endl;
 file.close();
 cout <<"===================================="<<endl;
 cout <<"| BUKTI PEMBAYARAN |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| PERTAMAX TURBO |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| Harga perliter: |"<<endl;
 cout <<"| Rp. 15.900/liter |"<<endl;
 cout <<"===================================="<<endl;
 cout <<" Nama Pembeli : "<<nama<<endl;
 cout <<" Nama Petugas : "<<petugas<<endl;
 cout <<" Pembelian : Rp "<<harga3<<endl;
 pertamaxturbo(harga3);
 break;
 }
 system("cls");
 case 4:
 {
 ofstream file("pembayaran.txt");
 if (!file.is_open()){
 cout <<"Pembayaran gagal"<<endl;
 return 1;
 }
 cout <<"===================================="<<endl;
 cout <<"| DEXLITE |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| Harga perliter: |"<<endl;
 cout <<"| Rp 16.350/liter |"<<endl;
 cout <<"===================================="<<endl;
 cout <<" Nama Pembeli : "<<nama<<endl;
 cout <<" Nama Petugas : "<<petugas<<endl;
 cout <<" Masukkan Nominal : Rp ";
 cin >>harga4;
 dexlite (harga4);
 getch();
 system("cls");
 file <<"===================================="<<endl;
 file <<"| DEXLITE |"<<endl;
 file <<"===================================="<<endl;
 file <<"Nama Pembeli: "<<nama<<endl;
 file <<"Nama Petugas: "<<petugas<<endl;
 file <<"Pembelian : Rp "<<harga4<<endl;
 file.close();
 cout <<"===================================="<<endl;
 cout <<"| BUKTI PEMBAYARAN |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| DEXLITE |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| Harga perliter: |"<<endl;
 cout <<"| Rp. 16.350/liter |"<<endl;
 cout <<"===================================="<<endl;
 cout <<" Nama Pembeli : "<<nama<<endl;
 cout <<" Nama Petugas : "<<petugas<<endl;
 cout <<" Pembelian : Rp "<<harga4<<endl;
 dexlite(harga4);
 break;
 }
 system("cls");
 case 5:
 {
 ofstream file("pembayaran.txt");
 if (!file.is_open()){
 cout <<"Pembayaran gagal"<<endl;
 return 1;
 }
 cout <<"===================================="<<endl;
 cout <<"| PERTAMINA DEX |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| Harga perliter: |"<<endl;
 cout <<"| Rp 16.900/liter |"<<endl;
 cout <<"===================================="<<endl;
 cout <<" Nama Pembeli : "<<nama<<endl;
 cout <<" Nama Petugas : "<<petugas<<endl;
 cout <<" Masukkan Nominal : Rp ";
 cin >>harga5;
 pertaminadex (harga5);
 getch();
 system("cls");
 file <<"===================================="<<endl;
 file <<"| PERTAMINA DEX |"<<endl;
 file <<"===================================="<<endl;
 file <<"Nama Pembeli: "<<nama<<endl;
 file <<"Nama Petugas: "<<petugas<<endl;
 file <<"Pembelian : Rp "<<harga5<<endl;
 file.close();
 cout <<"===================================="<<endl;
 cout <<"| BUKTI PEMBAYARAN |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| PERTAMINA DEX |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| Harga perliter: |"<<endl;
 cout <<"| Rp. 16.900/liter |"<<endl;
 cout <<"===================================="<<endl;
 cout <<" Nama Pembeli : "<<nama<<endl;
 cout <<" Nama Petugas : "<<petugas<<endl;
 cout <<" Pembelian : Rp "<<harga5<<endl;
 pertaminadex(harga5);
 break;
 }
 system("cls");
 case 6:
 {
 ofstream file("pembayaran.txt");
 if (!file.is_open()){
 cout <<"Pembayaran gagal"<<endl;
 return 1;
 }
 cout <<"===================================="<<endl;
 cout <<"| PERTAMAX GREEN 95 |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| Harga perliter: |"<<endl;
 cout <<"| Rp 15.000/liter |"<<endl;
 cout <<"===================================="<<endl;
 cout <<" Nama Pembeli : "<<nama<<endl;
 cout <<" Nama Petugas : "<<petugas<<endl;
 cout <<" Masukkan Nominal : Rp ";
 cin >>harga6;
 pertamaxgreen (harga6);
 getch();
 system("cls");
 file <<"===================================="<<endl;
 file <<"| PERTAMAX GREEN 95 |"<<endl;
 file <<"===================================="<<endl;
 file <<"Nama Pembeli: "<<nama<<endl;
 file <<"Nama Petugas: "<<petugas<<endl;
 file <<"Pembelian : Rp "<<harga6<<endl;
 file.close();
 cout <<"===================================="<<endl;
 cout <<"| BUKTI PEMBAYARAN |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| PERTAMAX GREEN 95 |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| Harga perliter: |"<<endl;
 cout <<"| Rp. 15.000/liter |"<<endl;
 cout <<"===================================="<<endl;
 cout <<" Nama Pembeli : "<<nama<<endl;
 cout <<" Nama Petugas : "<<petugas<<endl;
 cout <<" Pembelian : Rp "<<harga6<<endl;
 pertamaxgreen(harga6);
 break;
 }
 system("cls");
 case 7:
 {
 ofstream file("pembayaran.txt");
 if (!file.is_open()){
 cout <<"Pembayaran gagal"<<endl;
 return 1;
 }
 cout <<"===================================="<<endl;
 cout <<"| BIO SOLAR |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| Harga perliter: |"<<endl;
 cout <<"| Rp 6.800/liter |"<<endl;
 cout <<"===================================="<<endl;
 cout <<" Nama Pembeli : "<<nama<<endl;
 cout <<" Nama Petugas : "<<petugas<<endl;
 cout <<" Masukkan Nominal : Rp ";
 cin >>harga7;
 biosolar (harga7);
 getch();
 system("cls");
 file <<"===================================="<<endl;
 file <<"| BIO SOLAR |"<<endl;
 file <<"===================================="<<endl;
 file <<"Nama Pembeli: "<<nama<<endl;
 file <<"Nama Petugas: "<<harga7<<endl;
 file <<"Pembelian : Rp "<<harga7<<endl;
 file.close();
 cout <<"===================================="<<endl;
 cout <<"| BUKTI PEMBAYARAN |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| BIO SOLAR |"<<endl;
 cout <<"===================================="<<endl;
 cout <<"| Harga perliter: |"<<endl;
 cout <<"| Rp. 6.800/liter |"<<endl;
 cout <<"===================================="<<endl;
 cout <<" Nama Pembeli : "<<nama<<endl;
 cout <<" Nama Petugas : "<<petugas<<endl;
 cout <<" Pembelian : Rp "<<harga7<<endl;
 biosolar(harga7);
 break;
 }
 system("cls");
 default:
 cout <<"===================================="<<endl;
 cout <<"| PILIHAN SALAH |"<<endl;
 cout <<"===================================="<<endl;
 system("cls");
 }
 cout <<" Tekan (y/Y) untuk kembali ke menu awal : ";
 cin >>ulang;
 cin.ignore();
 system ("cls");
 }while (ulang == 'y' || ulang == 'Y');
getch();
return 0;
