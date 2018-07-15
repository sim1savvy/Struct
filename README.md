# Struct
youTube (bucky)

#include <iostream>
using namespace std;

struct Newperson  //declaring struct (as newperson)
{
	char name[20]; // name and age are variables of newperson (CALLED MEMBER or FIELD)
	int age;
};

int main()     // main code
{
	Newperson savvy=     //using struct
  {
		"simran kaur",    //
		19
	};
	
	cout<<savvy.age<<endl;  // accessing struct

	return 0;
}


output:

Success	#stdin #stdout 0s 4388KB
19    // age is the output
