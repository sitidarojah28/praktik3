# praktik3

latihan1 : Menentukan bilangan terbesar dari banyaknya bilangan
Alur Algoritma.
	1.Mendeklarasikan int i,max,a, dan x.
	2.mendeklarasikan variabel a dan x sebagai nilai inputan.
	3.Mendeklarasikan variabel i sebagai perulangan.
	4.Mendeklarasikan variabel max sebagai pengingat nilai.
	5.Membuat rumus perulangan untuk menentukan banyak bilangan yang akan di bandingkan
		for (i;i<a;i++)
	6.Menginputkan nilai a.
	7.menginputkan nilai x.
	8.Membandingkan nilai x dengan max
		if ( x> max) // jika x lebih besar dari max
	    	max= x   // maka nilai max adalah x
*Berikut kode lengkapnya

	int main()
{
    int i=0;
    int max=0;
    int a,x;

    cout << "Masukan Jumlah Bilangan :";
    cin >> a;

    for (i;i<a;i++){
        cout<< "Masukan Bilangan Ke-" << i+1 << ":";
        cin>> x;

        if (x > max)
            max = x;
    }
    cout << "Bilangan Terbesar Adalah :"<< max <<endl;
    return 0;
}

Berikut hasilnya 
![img](https://github.com/sitidarojah28/praktik3/blob/master/latihan1/Hasilnya.png)


Latihan2 #Mengurutkan bilangan dari yang terkecil sampai terbesar

Alur Algoritmanya
	1.Mendeklasrasikan int a,b,c sebagai variabel input
	2.Membandingkan setiap variabel untuk menentukan nilai yang terkceil sampai yang terbesar
	3.Dengan menggunkan rumus if dan percabangan
		if (a<b)
    		    {
       		       if (b<c)
                       cout<< a << "  " << b << "  " <<c;
		Jika a lebih kecil dari b dan jika b lebih kecil dari c maka yang akan ditampilkan
		a b c

*Berikut Kode Lengkapnya

int main()
{
    int a,b,c;
    cin>> a >> b >> c;
    if (a<b)
    {
        if (b<c)
            cout<< a << "  " << b << "  " <<c;
        else
        {
            if (a<c)
                cout<< a << "  " << c << "  " <<b;
            else
                cout << c << "  " << a << "  " <<b;
        }
    }
    else
    {
        if (a<c)
            cout << b << "  " << a << "  " << c;
        else
        {
            if ( b<c )
                cout << b << "  " << c << "  " <<a;
            else
                cout << c << "  " << b << "  " <<a;
        }
    }
    return 0;
}
![img](https://github.com/sitidarojah28/praktik3/blob/master/latihan2/hasilnya2.png)
![img](https://github.com/sitidarojah28/praktik3/blob/master/latihan2/hasilnya3.png)
1[img](https://github.com/sitidarojah28/praktik3/blob/master/latihan2/hasilnya4.png)

latihan3
-mendeklarasikan variable a, b dan c
-memasukan nilai kedalam variable (a, b dan c) 
-mencari nilai tengah dari sejumlah variable yang di inputkan menggunakan "if dan else"
-mencetak nilai tengah dari sejumlah variable yang telah di masukan 
berikut code lengkapnya :

#include

using namespace std; int main() { int a,b,c;

cout << " masukan nilai pertama : ";
cin >> a ;
cout << " masukan nilai kedua : ";
cin >> b ;
cout << " masukan nilai ketiga : ";
cin >> c ; 


if (a<b){
	if (b<c)
	cout << "nilai tengahnya adalah : "<< b ;
	else{
		if (a<c)
			cout << "nilai tengahnya adalah : "<<  c ;
		else
			cout << "nilai tengahnya adalah : "<< a ;
	}
}

else
{
	if (a<c)
		cout << "nilai tengahnya adalah : "<< a ;
	else
	{
		if(b<c)
		cout << "nilai tengahnya adalah : "<< c ;
		else
		cout << "nilai tengahnya adalah : "<< b ;
	}
}


return 0;
*berikut hasilnya
![img](https://github.com/sitidarojah28/praktik3/blob/master/latihan3/hasilnya5.png)
![img](https://github.com/sitidarojah28/praktik3/blob/master/latihan3/hasilnya6.png)
![img](https://github.com/sitidarojah28/praktik3/blob/master/latihan3/hasilnya7.png)