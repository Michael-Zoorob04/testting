
Odd or Even






#include <iostream>

using namespace std;

int main()
{
    int x;

    cout << "Enter a number: ";
    cin >> x;

    if (x % 2 == 0)
        cout << x << " is an even number.";
    else
        cout << x << " is an odd number.";
   
    return 0;
}
  
	
	
	
  
  Number checker
  
	
	
	
	
  
#include <iostream>
  
using namespace std;

int main()
{
    signed long x1 = 0;

    cout << "Enter a number: ";
    cin >> x1;
    if (x1 > 0)
    {
        cout << x1 << " is a positive number.\n\n";
    }
    else if (x1 < 0)
    {
        cout << x1 << " is a negative number.\n\n";
    }
    else
    {
        cout << x1 << " is zero.\n\n";
    }
    return 0;
}
                      
		      
		      
		      
                      
  Profit or Loss
                      
		      
		      
		      
		      
		      
		      
# include <iostream>

using namespace std;

int main()
{
	int x, y, profit, loss;
	cout << "Enter purchase price: " << endl;
	cin >> x;
	cout << "Enter selling price:" << endl;
	cin >> y;
	if (x > y)
	{
		profit = x - y;
		cout << "Loss: " << profit << endl;
	}
	else if (x > y)
	{
		loss = x - y;
		cout << "Profit: " << loss << endl;
	}
	else
	{
		cout << "No buy, No loss.";
	}
}
	
	
  
  
  Name that shape
  
  
  
	
#include <iostream>

using namespace std;

int main()
{
	int sidesofshape;
	cout << "Kindly enter the number of sides of the shape (3 - 10): ";
	cin >> sidesofshape;

	if (sidesofshape == 3) {
		cout << sidesofshape<< " sides is a triangle.";
	}
	else if (sidesofshape == 4) {
		cout << sidesofshape << " sides is a square.";
	}
	else if (sidesofshape == 5) {
		cout << sidesofshape << " sides is a pentagon.";
	}
	else if (sidesofshape == 6) {
		cout << sidesofshape << " sides is a Hexagon.";
	}
	else if (sidesofshape == 7) {
		cout << sidesofshape << " sides is a heptagon.";
	}
	else if (sidesofshape == 8) {
		cout << sidesofshape << " sides is an octagon.";
	}
	else if (sidesofshape == 9) {
		cout << sidesofshape << " sides is a Nonagon.";
	}
	else if (sidesofshape == 10) {
		cout << sidesofshape << " sides is a Decagon.";
	}
	else {
		cout << "Sorry, but that number of sides is beyond our expectations. 3-10 is only vaild.";
	}

	return 0;
}

                      
