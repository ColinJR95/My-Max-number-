
#include <iostream>
using namespace std;

int main() 
{
int num;
float inputs;
float max=0;
   std::cout << "How many numbers do you have?" << std::endl;
   std::cin >> num;
   //using for loop;
   for(int i=0;i<num;i++){
   cin>>inputs;
   if(inputs>max)
   max=inputs;
   }
   cout<<"The maximum is "<<max;
  
   return 0;
}
