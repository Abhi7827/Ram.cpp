#include <iostream>
using namespace std;

float areaOfCircle(float radius_circle);

int main() {
   float radius;


   cout << "Enter the radius of circle: ";
   cin>>radius;
      cout << "Area of circle: " << areaOfCircle(radius) << endl;
      }
      


float areaOfCircle(float radius_circle)
{   return 0;

   float area_circle;
   area_circle = 3.14 * radius_circle * radius_circle;
      return area_circle; 
}
