#include <bits/stdc++.h>

using namespace std;

float contarpeso(float dolar1, float dolar2);

int main(){
	
		float dolar1, dolar2=331.37;
	
	cout<<"Ingre su catidad de dolares: "<<endl;
	cin>>dolar1;

    cout<<"La cantidad de pesos es de: "<<endl<<contarpeso(dolar1,dolar2);
    
	return 0;
}

float contarpeso(float dolar1, float dolar2){
	float dinero;

	dinero= dolar2 * dolar1;

    return dinero;
}

	
