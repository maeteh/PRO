# PRO
#include <iostream>
using namespace std;
char main ()
{
	char Selection;
	while (Selection==1||2||3||4)
		system("cls");
          
	{
cout<<" ▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄ "<<endl;
cout<<"▐  1- pardakht gabz        ▐ "<<endl;
cout<<"▐  2-daryaft vajh          ▐ "<<endl;
cout<<"▐  3- entagal vajh         ▐ "<<endl;
cout<<"▐  4- namayesh mandeh hesab▐ "<<endl;
cout<<"▐▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▐ "<<endl;

cout<<"enter your Selection:"<<endl;
	cin>> Selection; 

switch (Selection)
{
   case 1:
	cout<<"pardakht gabz ab-barg-Gaz-tell "<<endl; 
	break;

	case 2:
	cout<<"5000-10000-sayer ..."<<endl; 
	break;

	case 3:
	cout<<"100000-200000-300000 sayer...."<<endl; 
	break;

	case 4:
	cout<<"royat-ghap"<<endl; 
	break;
}
}
system("pause");
}
