
My simple multiplication table with for loop. I was trying to have some fun.
#include <iostream>
using namespace std;
int main()
{
    int ans;

    //Just trying to have some fun with for loop

    cout << "\t\tA multiplication table:\n\n"
         << "How many multiplication table do You want(1 to 12)\nResponse: ";
    cin >> ans;
    cout     << "\n\n 1\t2\t3\t4\t5\t6\t7\t8\t9\t10\t11\t12\n"
         << "____________________________________________________"
         << "____________________________________________________\n";

         for(int c = 1; c <= ans; c++)
         {
             cout << c << "| ";

             for(int i = 1; i <= ans; i++)
             {
                 cout << i * c << '\t';
             }
             cout << "\n";
         }

         return 0;
}


