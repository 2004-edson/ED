# ED
**Negritas**

__italica__
```C++
#include <iostream>
#include <vector>
using namespace std;

void imprime(vector <int> v)
{
	for (auto elemento : v)
	{
		cout << elemento << " , ";
	}
	cout << endl;
	system("pause");
	system("cls");
}

int main()
{
	vector<int> v;

	//Llenar el vector con 0, cinco veces
	v.assign(5, 0);
	imprime(v);
}
```
