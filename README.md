#include <iostream>
#include <string>
using namespace std;
int main()
{
	int x,i,j,k=0;
	cout<< "Введите кол-во верблюдов: ";
	cin >> x;
	k = k+x;
	string a = "был";
	string b = " верблюд";
	string c;
	i = x%10;
	j = x%100;
	if (((i==0)|| (i>=5 && i<=9))|| (j >= 11 && j<=14)) {
		a = a.append("о");
		b = b.append("ов");
	} else {
		if (i==1) {
			a = a.append(c);
			b = b.append(c);
		} else {
			a = a.append("а");
			b = b.append("а");
		}
	}
	cout<<"В караване "<<a<<" "<<k<<b<<endl;
	return 0;
}
