#import <iostream>
using namespace std;

int main (){
	int select;
	do{
		cout<<"Seleccione numero del menu\n"<<endl;
		cout<<"\t1. Crear cuenta monetaria"<<endl;
		cout<<"\t2. Operar depósito "<<endl;
		cout<<"\t3. Operar retiro"<<endl;
		cout<<"\t4. Consultar saldo de cuenta "<<endl;
		cout<<"\t5. Salir"<<endl;
		cin>>select;
		switch(select){
			case 1: { cout<<"Prueba1"<<endl;
				break;
			}
			case 2: { cout<<"Prueba2"<<endl;
				break;
			}
			case 3: { cout<<"Prueba3"<<endl;
				break;
			}
			case 4: { cout<<"Prueba4"<<endl;
				break;
			}
		}
	}while(select != 5);
	cout <<"Salida exitosa";
}
