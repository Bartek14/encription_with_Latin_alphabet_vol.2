# encription_with_Latin_alphabet_vol.2

#include <iostream>
#include <time.h>
#include <windows.h>
using namespace std;
main()
{srand(time(NULL));
char inputChar;
int randomizer,outNumb;
do {rand();
//number = inputChar- '0';
randomizer=rand();
    inputChar=cin.get();
    if (inputChar==32)
    {
        outNumb = 27*randomizer;
        cout<< outNumb<<",";
    }
    else
    {
        outNumb= inputChar - 'A' + 1;
    cout<<outNumb + 27* randomizer<<",";
    }
   }
    while(inputChar!=10);
return 0;}

