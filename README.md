# Ejercicio1


#include<iostream>
using namespace std;

int main() {
    int p, o, d, t;
    
    cout<<"que marca es\n";
    cout<<"1-Honda\n" ;
    cout<<"2-Yamaha\n" ;
    cout<<"3-Suzuki\n" ;
    cout<<"4-otra marca\n" ;
    cin>>o;
    
    switch(o) {
    
    case 1:
    cout<<"precio inicial ";
    cin>>p;
    d=p*0.05 ;
    t=p-d;
    cout<<"precio con el descuento "<<t<<endl;
    break;
    
    case 2:
    cout<<"precio inicial ";
    cin>>p;
    d=p*0.08;
    t=p-d;
    cout<<"precio con el descuento "<<t<<endl;
    break;
    
    case 3:
    cout<<"precio inicial ";
    cin>>p;
    d=p*0.1;
    t=p-d;
    cout<<"precio con el descuento "<<t<<endl;
    break;
    
    case 4:
    cout<<"precio inicial ";
    cin>>p;
    d=p*0.02;
    t=p-d;
    cout<<"precio con el descuento "<<t<<endl;
    break;
    
    
    
    
    } 
    return 0;
}












Ejercicio2



#include<iostream>
using namespace std;

int main(){
   int r;
   float p, a;
    
    cout <<" INGRESÉ EL RADIO ";
    
    cin >>r;
    
    p= 2*3.14*r;
    cout <<" EL PERÍMETRO ES "<<p<<endl;
    
    a= r*r * 3.14;
    cout <<"\n EL ÁREA ES "<<a<<endl;
    
    
    
    return 0;
}
