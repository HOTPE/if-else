#include <iostream>
using namespace std;
int main()
{
	int x;
	cin >> x;
	while (x--)
	{
		int a, b;
		cin >> a >> b;
		if (a == 0 && b == 0)
			cout << "YES" << endl;
		else if (a == 0 || b == 0)
			cout << "NO" << endl;
		else if (a > b * 2 || b > a * 2)
			cout << "NO" << endl;
		else
		{
			int tmp1 = 2 * a - b;
			int tmp2 = 2 * b - a;
			if (tmp1 % 3 == 0 || tmp2 % 3 == 0)
				cout << "YES" << endl;
			else
				cout << "NO" << endl;
		}
	}
	
	return 0;
}
