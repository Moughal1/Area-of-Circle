# Area-of-Circle
Assignment
#include<iostream.h>
class Circle
{
private:
float Radius;
public:
Circle():Radius(4){}
void getRadius()
{
cout<<"enter the value of Radius=";
cin>>Radius;
}
void showRadius()
{
cout<<"Radius="<<Radius<<endl;
}
float Area()
{
return 3.14*Radius*Radius;
}
};
int main()
{
Circle R1;
R1.showRadius();
R1.getRadius();
R1.showRadius();
cout<<R1.Area();
return o;
}
